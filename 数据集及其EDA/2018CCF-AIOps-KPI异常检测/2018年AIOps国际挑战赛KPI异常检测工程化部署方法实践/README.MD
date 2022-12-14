## 2018年AIOps国际挑战赛KPI异常检测工程化部署方法实践

---
### **作者简介**

作者：鱼丸粗面（zhuoyin94@163.com）。整体采用了[此项目](https://github.com/MichaelYin1994/python-style-guide)的编码规范，逐步完善中（20220617）。

---
### **系统环境与组件依赖**

**系统环境:**
- Ubuntu 20.04 LTS
- GPU: NVIDIA Corporation GP104GL [Quadro P5000](16G)
- CPU: Intel® Core™ i9-9920X CPU @ 3.50GHz × 24
- RAM: 94G
- CUDA: 11.4
- swap: 96G

**开源组件:**
- OpenMLDB: 用于stream形式数据的实时特征工程。
- cAdivisor: 用于容器状态监控。
- Triton inference server: 用于serving XGBoost模型与DL-based模型。
- Prometheus + Grafana: 用于容器状态的可视化监控。

---
### **源代码说明**
- **start_openmldb_cluster.sh**：启动openmldb的docker container service，注意提前修改`/work/openmldb/conf/taskmanager.properties`的`spark.master`的local线程数，采用多线程写入。
- **preprocessing_train_test.py**：对原始比赛数据进行重新预处理、数据切分、重新存储。
- **create_offline_table.py**：创建离线表 && 将离线数据导入数据库中。
- **compute_offline_feats.py**：读取sql脚本 && 执行sql脚本，创建离线特征组。
- **train_xgb.py**：读取离线特征组 && 训练XGBoost模型 && 导出模型基本参数。
- **deploy_realtime_fe.py**：读取sql脚本（与offline feats相同） && 创建在线表 && 导入在线数据 && 部署在线特征脚本。
- **deploy_triton_server.py && start_triton_xgb_server.sh**：生成Inference Server的配置文件 && 部署Triton Inference Server后端。
- **deploy_inference_pipeline.py**：Flask部署Inference Pipeline，Flask Server接收数据 --> Preprocessing --> Openmldb特征工程 && 实时数据插入 --> Postprocessing -->  返回inference结果。

### **Todo List**
- 配置的yaml文件进行统一管理
- XGBoost Early Stopping的官方Metric的njit实现
- 单元测试部分对于部署的特征工程的正确性测试
- Triton inference server的XGBoost模型inference测试
- 刨除Openmldb的window特征，特征工程对原始数据的前处理和后处理脚本部分

---
### **References**

[1] https://github.com/MichaelYin1994/tianchi-pakdd-aiops-2021

[2] Lam, Siu Kwan, Antoine Pitrou, and Stanley Seibert. "Numba: A llvm-based python jit compiler." Proceedings of the Second Workshop on the LLVM Compiler Infrastructure in HPC. 2015.

[3] https://github.com/johannfaouzi/pyts

[4] https://github.com/blue-yonder/tsfresh

[5] Goldstein M, Dengel A. Histogram-based outlier score (hbos): A fast unsupervised anomaly detection algorithm[J]. KI-2012: Poster and Demo Track, 2012: 59-63.

[6] Bu, Jiahao, et al. "Rapid deployment of anomaly detection models for large number of emerging kpi streams." 2018 IEEE 37th International Performance Computing and Communications Conference (IPCCC). IEEE, 2018.

[7] Ma M, Zhang S, Pei D, et al. Robust and rapid adaption for concept drift in software system anomaly detection[C]//2018 IEEE 29th International Symposium on Software Reliability Engineering (ISSRE). IEEE, 2018: 13-24.

[8] Li, Zhihan, et al. "Robust and rapid clustering of kpis for large-scale anomaly detection." 2018 IEEE/ACM 26th International Symposium on Quality of Service (IWQoS). IEEE, 2018.

[9] Li, Zeyan, Wenxiao Chen, and Dan Pei. "Robust and unsupervised kpi anomaly detection based on conditional variational autoencoder." 2018 IEEE 37th International Performance Computing and Communications Conference (IPCCC). IEEE, 2018.

[10] Liu, Dapeng, et al. "Opprentice: Towards practical and automatic anomaly detection through machine learning." Proceedings of the 2015 Internet Measurement Conference. 2015.

[11] Zhao, Nengwen, et al. "Label-less: A semi-automatic labelling tool for kpi anomalies." IEEE INFOCOM 2019-IEEE Conference on Computer Communications. IEEE, 2019.

