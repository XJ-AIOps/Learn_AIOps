## Reference

[官网介绍][http://docs.aiops.cloudwise.com/zh/gaia/dataset-description.html#micross](http://docs.aiops.cloudwise.com/zh/gaia/dataset-description.html#micross)

[社区中介绍][http://bbs.aiops.cloudwise.com/](http://bbs.aiops.cloudwise.com/)

[Github上简介][https://github.com/CloudWise-OpenSource/GAIA-DataSet](https://github.com/CloudWise-OpenSource/GAIA-DataSet)

[知乎网][https://zhuanlan.zhihu.com/p/404102376](https://zhuanlan.zhihu.com/p/404102376)

## 概述

包含四类数据:
1. metric data, 系统基础指标数据, 系统基础指标的实时体现，亦反应了服务在运行过程中，对系统造成的影响的实时反应。对系统指标实时的监控，能有效的反应系统或服务的状态，对系统异常进行检测和预警。
2. trace data：调用链数据，记录的是每个请求在整个服务中的调用链路和请求状况，比如请求经过哪些服务，再飞哥服务的响应时长，请求在每个服务上的状态。
3. business data：业务日志，系统过服务行为的最近本的体现，能最细粒度的体现系统或服务在每时每刻的行为状况，再系统或服务发生故障时，为运维人员排查故障提供详细的依据。
4. run data: 整个模拟系统故障注入的日志记录数据，为运维人员在对模拟系统故障排查的结果提供对比，为各种智能运维算法效果优劣提供依据。

### metric data, 指标数据集概述

每个压缩包代表一个服务节点的基础指标数据，包括cpu、memory、disk等一系列指标。

### trace data, 调用链数据

调用链数据，记录的是每个请求在整个服务中的调用链路和请求状况，比如请求经过哪些服务，在各个服务上的响应时长，请求在每个服务上的状态。

### business data, 业务日志数据集

business data：业务日志，系统过服务行为的最近本的体现，能最细粒度的体现系统或服务在每时每刻的行为状况，再系统或服务发生故障时，为运维人员排查故障提供详细的依据。

### run data, 故障日志记录数据集

整个模拟系统故障注入的日志记录数据，为运维人员在对模拟系统故障排查的结果提供对比，为各种智能运维算法效果优劣提供依据。

