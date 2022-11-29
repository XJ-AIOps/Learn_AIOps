# XJ-AIOps

Materials about Artificial Intelligence for IT Operations (AIOps).

- [Researchers](#researchers)
- [Industrial Materials](#industrial-materials)
  - [Competitions](#competitions)
  - [White Papers](#white-papers)
  - [Blogs &amp; Tutorials &amp; Magazines](#blogs--tutorials--magazines)
  - [Companies](#companies)
- [Academic Materials](#academic-materials)
  - [Talks](#talks)
  - [Workshops](#workshops)
- [Papers](#papers)
  - [Survey &amp; Empirical Study](#survey--empirical-study)
  - [Benchmarks](#the-benchmarks)
  - [Knowledge Graph for AIOps](#knowledge-graph-for-aiops)
  - [Microservices and Serverless](#microservices-and-serverless)
  - [Dependency and Tracing](#dependency-and-tracing)
  - [Anomaly and Failure Detection](#anomaly-and-failure-detection)
  - [Incident and Alarm Management](#incident-and-alarm-management)
  - [Node, Disk, and Storage](#node-disk-and-storage)
  - [VM Analysis and Management](#vm-analysis-and-management)
  - [Deployment](#deployment)
- [Competitions](#competitions)
  - [Tsinghua 清华 CCF 国际AIOps大赛](#CCF国际AIOps挑战赛)
  - [Alibaba-智能运维大赛](#阿里巴巴)
  - [华为通信智能运维大赛](#华为)
- [Datasets](#datasets)
  - [CUHK 香港中文大学](#cuhk-香港中文大学)
  - [Microsoft 微软](#microsoft-微软)
  - [Tsinghua 清华 CCF 国际AIOps大赛](#tsinghua-清华)
  - [Google 谷歌](#google-谷歌)
  - [Backblaze 云备份和存储供应商](#backblaze-云备份和存储供应商)
  - [Alibaba-智能运维大赛](#alibaba-智能运维大赛数据集)
  - [AIOps2022通信网络智能运维大赛数据集](#)
  - GAIA-DataSet
  - 华为网络运维数据集
- Tools, Models and Systems
- Community
- Internet articles
- [Others](#others)
  - [Courses](#courses)
- Reference

## 一.Researchers

| China (& HK SAR)                                      |                                                                                          |                                                                         |                                                     |
| :---------------------------------------------------- | :--------------------------------------------------------------------------------------- | :---------------------------------------------------------------------- | :-------------------------------------------------- |
| [Michael R. Lyu](http://www.cse.cuhk.edu.hk/lyu/), CUHK  | [Dongmei Zhang](https://www.microsoft.com/en-us/research/people/dongmeiz/), Microsoft       | [Pengfei Chen](http://sdcs.sysu.edu.cn/content/3747), SYSU                 | [Dan Pei](https://netman.aiops.org/~peidan/), Tsinghua |
| [Pengfei Chen](http://www.dds-sysu.tech/Teachers), SYSU  | [Xin Peng](https://cspengxin.github.io/), Fudan                                             |                                                                         |                                                     |
|                                                       |                                                                                          |                                                                         |                                                     |
| **USA**                                         |                                                                                          |                                                                         |                                                     |
| [Ryan Huang](https://www.cs.jhu.edu/~huang/), JHU        | [Yingnong Dang](https://scholar.google.com.hk/citations?user=InqtwxcAAAAJ&hl=en), Microsoft | [Christina Delimitrou](https://www.csl.cornell.edu/~delimitrou/), MIT EECS |                                                     |
| **Europe**                                      |                                                                                          |                                                                         |                                                     |
| [Odej Kao](https://www.cit.tu-berlin.de/kao/), TU Berlin |                                                                                          |                                                                         |                                                     |
| **Australia**                                   |                                                                                          |                                                                         |                                                     |
| [Hongyu Zhang](http://hongyujohn.github.io/), UON        |                                                                                          |                                                                         |                                                     |

### Dan Pei-Tsinghua(裴丹-清华)团队

- [个人主页](https://netman.aiops.org/~peidan/)
- [谷歌主页](https://sc.panda321.com/citations?hl=zh-CN&user=i_zA1VsAAAAJ&view_op=list_works&sortby=pubdate)
- [NetMan实验室官网](https://netman.aiops.org/publications/)
- [实验室Github](http://github.com/NetManAIOps)

### 中山大学 陈鹏飞团队

- [个人主页](http://www.dds-sysu.tech/Teachers)
- [谷歌主页](https://xueshu.studiodahu.com/citations?hl=zh-CN&user=g9tdjgQAAAAJ&view_op=list_works&sortby=pubdate)
- [实验室主页](http://www.dds-sysu.tech/)
- [实验室Github](https://github.com/IntelligentDDS)

## 二. Industrial Materials

### White Papers

- [VMware] [Proactive Incident and Problem Management](https://docplayer.net/8854482-Proactive-incident-and-problem-management.html)
- [GREATOPS 高效运维社区] [《企业级 AIOps 实施建议》白皮书](https://pic.huodongjia.com/ganhuodocs/2018-04-16/1523873064.74.pdf)
- [Awesome Open Source] [Aiops Handbook](https://awesomeopensource.com/project/chenryn/aiops-handbook)

### Blogs & Tutorials & Magazines

- [Tsinghua University] [清华裴丹：AIOps落地的15条原则](https://mp.weixin.qq.com/s/Ov1gQlQ0mRpk58cNL_YlVg)
- [Tsinghua University] [清华裴丹：AIOps效果落地最后一公里](https://mp.weixin.qq.com/s/VhaRfvjc839bAXBMfzv11g)
- [Alibaba Cloud] [基于大数据的智能网络分析-齐天](https://developer.aliyun.com/article/590290)
- [Tsinghua University] [清华裴丹：AIOps效果落地最后一公里](https://mp.weixin.qq.com/s/VhaRfvjc839bAXBMfzv11g)
- [Moogsoft] [What is AIOps?](https://www.moogsoft.com/resources/aiops/guide/everything-aiops/)
- [Microsoft] [Advancing Azure service quality with artificial intelligence: AIOps](https://azure.microsoft.com/en-us/blog/advancing-azure-service-quality-with-artificial-intelligence-aiops/)

### Companies

- [Datadog](https://www.datadoghq.com/): A monitoring and security platform for cloud applications
- [必示 bizseer](https://www.bizseer.com/)
- [听云 TINGYUN](https://www.tingyun.com/lp.html): 端到端的全平台应用性能管理系统
- [Loom Systems](https://www.loomsystems.com/)

## 三. Academic Materials

### Talks

- [Michael R. Lyu] [Reliability-Driven AIOps for Cloud Resilience (Keynote talk at ICSE &#39;21)](http://ariselab.cse.cuhk.edu.hk/assets/files/ICSE2021_keynote_lyu.pdf)

### Workshops

- [ICSE21 Workshop on Cloud Intelligence](http://cloudintelligenceworkshop.org/index.html)
- [AAAI-20 Workshop on Cloud Intelligence](http://cloudintelligenceworkshop.org/2020/index.html)
- [AIOPS 2020 (International Workshop on Artificial Intelligence for IT Operations)](https://aiopsworkshop.github.io/)

## 四. Papers

### Survey & Empirical Study

- [arXiv '21] [Experience Report: Deep Learning-based System Log Analysis for Anomaly Detection](https://arxiv.org/abs/2107.05908)
- [CSUR '21] [A Survey on Automated Log Analysis for Reliability Engineering](https://arxiv.org/abs/2009.07237)
- [ESEC/FSE '20] [Towards intelligent incident management: why we need it and how we make it](https://dl.acm.org/doi/abs/10.1145/3368089.3417055)
- [arXiv '20] [A Systematic Mapping Study in AIOps](https://arxiv.org/abs/2012.09108)
- [ICSE '19] [AIOps: Real-World Challenges and Research Innovations](https://ieeexplore.ieee.org/document/8802836)
- [ISSRE '16] [Experience Report: System Log Analysis for Anomaly Detection](https://ieeexplore.ieee.org/abstract/document/7774521)
- [ASE '13] [Software analytics for incident management of online services: An experience report](https://ieeexplore.ieee.org/document/6693105)

### The benchmarks

- [arXiv '22] [Constructing Large-Scale Real-World Benchmark Datasets for AIOps](https://arxiv.org/abs/2208.03938)
- [ASPLOS '19] [An Open-Source Benchmark Suite for Microservices and Their Hardware-Software Implications for Cloud and Edge Systems](https://dl.acm.org/doi/10.1145/3297858.3304013)

### Knowledge Graph for AIOps

- [ICSE-SEIP '22] [Mining Root Cause Knowledge from Cloud Service Incident Investigations for AIOps](https://arxiv.org/abs/2204.11598)
- [ICSE-SEIP '21] [Neural knowledge extraction from cloud service incidents](https://dl.acm.org/doi/abs/10.1109/ICSE-SEIP52600.2021.00031)
- [arXiv '21] [SoftNER: Mining Knowledge Graphs From Cloud Incidents](https://arxiv.org/abs/2101.05961)
- [APPLSCI '20] [A Causality Mining and Knowledge Graph Based Method of Root Cause Diagnosis for Performance Anomaly in Cloud Applications](https://www.mdpi.com/2076-3417/10/6/2166)

### Microservices and Serverless

- [ASPLOS '21] [Sage: Practical &amp; Scalable ML-Driven Performance Debugging in Microservices](https://dl.acm.org/doi/abs/10.1145/3445814.3446700)
- [ICDCS '21] [Defuse: A Dependency-Guided Function Scheduler to Mitigate Cold Starts on FaaS Platforms](https://ieeexplore.ieee.org/document/9546470)
- [FSE '20] [Graph-based trace analysis for microservice architecture understanding and problem diagnosis](https://dl.acm.org/doi/10.1145/3368089.3417066)
- [OSDI '20] [FIRM: An Intelligent Fine-grained Resource Management Framework for SLO-Oriented Microservices](https://www.usenix.org/conference/osdi20/presentation/qiu)
- [ESEC/FSE '19] [Latent Error Prediction and Fault Localization for Microservice Applications by Learning from System Trace Logs](https://dl.acm.org/doi/10.1145/3338906.3338961)
- [TSE '18] [Fault Analysis and Debugging of Microservice Systems: Industrial Survey, Benchmark System, and Empirical Study](https://ieeexplore.ieee.org/document/8580420/)

### Dependency and Tracing

- [ASE '21] [AID: Efficient Prediction of Aggregated Intensity of Dependency in Large-scale Cloud Systems](https://arxiv.org/abs/2109.04893) [[code](https://github.com/OpsPAI/aid)]
- [NSDI '07] [X-Trace: A Pervasive Network Tracing Framework](https://www.usenix.org/conference/nsdi-07/x-trace-pervasive-network-tracing-framework)
- [HotNets '06] [Discovering Dependencies for Network Management](https://www.microsoft.com/en-us/research/wp-content/uploads/2006/11/hotnets06.pdf)

### Anomaly and Failure Detection

- [ICSE '22] [Adaptive Performance Anomaly Detection for Online Service Systems via Pattern Sketching](https://arxiv.org/abs/2201.02944) [[code](https://github.com/OpsPAI/ADSketch)]
- [KDD '19] [Time-Series Anomaly Detection Service at Microsoft](https://dl.acm.org/doi/10.1145/3292500.3330680)
- [OSDI '18] [Capturing and Enhancing In Situ System Observability for Failure Detection](https://www.usenix.org/conference/osdi18/presentation/huang)
- [ESEC/FSE '18] [Identifying Impactful Service System Problems via Log Analysis](https://dl.acm.org/doi/10.1145/3236024.3236083)
- [CCS '17] [DeepLog: Anomaly Detection and Diagnosis from System Logs through Deep Learning](https://dl.acm.org/doi/10.1145/3133956.3134015)

### Incident and Alarm Management

- [DSN '22] [Characterizing and Mitigating Anti-patterns of Alerts in Industrial Cloud Systems](https://arxiv.org/abs/2204.09670)
- [USENIX ATC '21] [Fighting the Fog of War: Automated Incident Detection for Cloud Systems](https://www.usenix.org/conference/atc21/presentation/li-liqun)
- [ASE '21] [Graph-based Incident Aggregation for Large-Scale Online Service Systems](https://arxiv.org/abs/2108.12179)
- [ASE '21] [Groot: An Event-graph-based Approach for Root Cause Analysis in Industrial Settings](https://arxiv.org/abs/2108.00344)
- [SIGCOMM '20] [Scouts: Improving the Diagnosis Process Through Domain-customized Incident Routing](https://dl.acm.org/doi/10.1145/3387514.3405867)
- [ASE '20] [How Incidental are the Incidents?: Characterizing and Prioritizing Incidents for Large-Scale Online Service Systems](https://dl.acm.org/doi/10.1145/3324884.3416624)
- [ESEC/FSE '20] [Identifying linked incidents in large-scale online service systems](https://dl.acm.org/doi/10.1145/3368089.3409768)
- [ESEC/FSE '20] [Efficient incident identification from multi-dimensional issue reports via meta-heuristic search](https://dl.acm.org/doi/abs/10.1145/3368089.3409741)
- [ESEC/FSE '20] [Real-time incident prediction for online service systems](https://dl.acm.org/doi/abs/10.1145/3368089.3409672)
- [ESEC/FSE '20] [How to mitigate the incident? an effective troubleshooting guide recommendation technique for online service systems](https://dl.acm.org/doi/abs/10.1145/3368089.3417054)
- [ICSE '20] [Understanding and Handling Alert Storm for Online Service Systems](https://dl.acm.org/doi/10.1145/3377813.3381363)
- [HotOS '19] [What bugs cause production cloud incidents?](https://dl.acm.org/doi/10.1145/3317550.3321438)
- [ASE '19] [Continuous Incident Triage for Large-Scale Online Service Systems](https://dl.acm.org/doi/10.1109/ASE.2019.00042)
- [ICSE '19] [An empirical investigation of incident triage for online service systems](https://dl.acm.org/doi/10.1109/ICSE-SEIP.2019.00020)
- [WWW '19] [Outage Prediction and Diagnosis for Cloud Service Systems](https://dl.acm.org/doi/10.1145/3308558.3313501)
- [KDD '14] [Correlating Events with Time Series for Incident Diagnosis](https://dl.acm.org/doi/10.1145/2623330.2623374)

### Node, Disk, and Storage

- [DSN '21] [General Feature Selection for Failure Prediction in Large-scale SSD Deployment](https://ieeexplore.ieee.org/document/9505157)
- [TOSEM '20] [Predicting Node Failures in an Ultra-Large-Scale Cloud Computing Platform: An AIOps Solution](https://dl.acm.org/doi/10.1145/3385187)
- [ICDCS '20] [Toward Adaptive Disk Failure Prediction via Stream Mining](https://ieeexplore.ieee.org/document/9355640)
- [VLDB '20] [Diagnosing root causes of intermittent slow queries in cloud databases](https://dl.acm.org/doi/abs/10.14778/3389133.3389136)
- [USENIX ATC '19] [IASO: A Fail-Slow Detection and Mitigation Framework for Distributed Storage Services](https://www.usenix.org/conference/atc19/presentation/panda)
- [NSDI '18] [Deepview: Virtual Disk Failure Diagnosis and Pattern Detection for Azure](https://www.usenix.org/conference/nsdi18/presentation/zhang-qiao)
- [ESEC/FSE '18] [Predicting Node Failure in Cloud Service Systems](https://dl.acm.org/doi/10.1145/3236024.3236060)
- [USENIX ATC '18] [Improving Service Availability of Cloud Systems by Predicting Disk Error](https://www.usenix.org/conference/atc18/presentation/xu-yong)

### VM Analysis and Management

- [NSDI '22] [CloudCluster: Unearthing the Functional Structure of a Cloud Service](https://www.usenix.org/conference/nsdi22/presentation/pang)
- [OSDI '20] [Predictive and Adaptive Failure Mitigation to Avert Production Cloud VM Interruptions](https://www.usenix.org/conference/osdi20/presentation/levy)

### Deployment

- [SOSP '21] [Understanding and Detecting Software Upgrade Failures in Distributed Systems](https://dl.acm.org/doi/10.1145/3477132.3483577)
- [NSDI '20] [Gandalf: An Intelligent, End-To-End Analytics Service for Safe Deployment in Large-Scale Cloud Infrastructure](https://www.usenix.org/conference/nsdi20/presentation/li)

## 五. Competitions

### CCF国际AIOps挑战赛

- [AIOps Challenge] [A series of AIOps competitions hosted by Tsinghua University](http://iops.ai/)

### 阿里巴巴

- [第三届阿里云磐久智维算法大赛](https://tianchi.aliyun.com/competition/entrance/531947/introduction?spm=5176.12281949.1003.1.48ff2448lH1gSZ)
- [PAKDD2021 第二届阿里云智能运维算法大赛](https://tianchi.aliyun.com/competition/entrance/531874/introduction?spm=5176.12281957.0.0.41ed3eafuIEMR0)
- [PAKDD2020 阿里巴巴智能运维算法大赛](https://tianchi.aliyun.com/competition/entrance/231775/introduction?spm=5176.12281957.0.0.41ed3eafuIEMR0)

### 华为

- [AIOps 2022 通信网络智能运维大赛](https://www.aiops.sribd.cn/home/statement)

## 六. Datasets

### CUHK 香港中文大学

- [CUHK] [Loghub](https://github.com/logpai/loghub)

### Microsoft 微软

- [Microsoft Azure] [Azure Public Dataset](https://github.com/Azure/AzurePublicDataset)

### Tsinghua 清华

- [Tsinghua] [2018 AIOps Challenge Dataset](https://github.com/NetManAIOps/KPI-Anomaly-Detection)
- [Tsinghua] [2019 AIOps Challenge Dataset](https://github.com/NetManAIOps/MultiDimension-Localization)
- [Tsinghua] [2020 AIOps Challenge Dataset](https://github.com/NetManAIOps/AIOps-Challenge-2020-Data)

### Google 谷歌

- [Google] [Cluster Traces](https://github.com/google/cluster-data)

### Backblaze 云备份和存储供应商

- [Backblaze] [Hard Drive Dataset](https://www.backblaze.com/b2/hard-drive-test-data.html)

### Alibaba 智能运维大赛数据集

- [Alibaba] [SMART Dataset of PAKDD CUP 2020](https://pan.baidu.com/share/link?shareid=189977&uk=4278294944#list/path=%2FS.M.A.R.T.dataset)
- [Alibaba] [SSD SMART logs and failure data](https://github.com/alibaba-edu/dcbrain/tree/master/ssd_open_data)

### Ceph Drive Telemetry Data

- [Ceph Drive] [kaggle](https://www.kaggle.com/datasets/chauhankaranraj/ceph-drive-telemetry-data)

### GAIA-DataSet

- [GAIA](https://github.com/CloudWise-OpenSource/GAIA-DataSet)

## 七. Tools、Models and Systems

- [Log Analytics] [LogPAI](https://github.com/logpai)
- [AI for Cloud Operation] [OpsPAI](https://github.com/OpsPAI)
- [Outlier Detection] [PyOD](https://github.com/yzhao062/pyod)
- [Anomaly Detection] [ADTK](https://github.com/arundo/adtk)
- [Anomaly Detection] [PySAD](https://github.com/selimfirat/pysad)
- [Online Machine Learning] [River](https://riverml.xyz/)
- [Online Machine Learning] [scikit-multiflow](https://scikit-multiflow.readthedocs.io/)
- [Fault Injection] [Chaos Mesh](https://github.com/chaos-mesh/chaos-mesh)
- [Fault Injection] [ChaosBlade](https://github.com/chaosblade-io/chaosblade)
- [Container Monitoring] [cAdvisor](https://github.com/google/cadvisor)
- [Performance Monitoring] [Netdata](https://www.netdata.cloud/)
- [Anomaly Detection Labeling Tool] [Microsoft TagAnomaly](https://github.com/Microsoft/TagAnomaly)
- [Serverless App Dev. Framework] [AWS Serverless Application Model (AWS SAM)](https://github.com/aws/serverless-application-model)
- [Fudan] [Train Ticket (A Benchmark Microservice System)](https://github.com/FudanSELab/train-ticket) 该项目是一个基于微服务架构的火车票预订系统，包含41个微服务。
- [Weaveworks] [Sock Shop (A Microservices Demo Application)](https://microservices-demo.github.io/) 袜子店模拟了一个销售袜子的电子商务网站中面向用户的部分。它的目的是帮助演示和测试微服务和云原生技术。

## 八. Community

- [云智慧] [CloudWise-OpenSource](https://www.cloudwise.ai/)

## 九. Internet articles

- [基于深度学习的运维日志领域新进展](https://zhuanlan.zhihu.com/p/586626228)
- [从实验室到用户桌面，深度解析AI落地实践之路](https://www.51cto.com/article/719959.html)

## 十. Others

### Courses

- [Coursera] [Cloud-Based Network Design &amp; Management Techniques](https://www.coursera.org/learn/cloud-based-network-design-and-management)
- [Tsinghua] [AIOps Course of Tsinghua](https://netman.aiops.org/courses/advanced-network-management-spring2021-course/)

## 十一. Reference

- [OpsPAI] [https://github.com/WeibinMeng/log-anomaly-detection](https://github.com/OpsPAI/awesome-AIOps)
- [WeibinMeng] [https://github.com/WeibinMeng/log-anomaly-detection](https://github.com/WeibinMeng/log-anomaly-detection)
- [awesome-AIOps] [https://github.com/linjinjin123/awesome-AIOps](https://github.com/linjinjin123/awesome-AIOps)
