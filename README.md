# MLOps_template



A template of the MLOps_project.

Project Organization

--------------------

    ├── README.md          <-  项目描述
    ├── data
    │   ├── cache      <- 用于数据缓存
    │   ├── external       <- 第三方数据
    │   ├── interim        <- 已经转换的中间数据。
    │   ├── processed      <- 用于传入模型的最终的、规范化的数据集。
    │   └── raw            <- 原始数据
    │
    ├──  logs              <- 用于存放模型日志
    │
    ├── models             <- 用于存放模型文件
    │   ├── pretrained      <-  pretrained model
    │   └── trained            <-fine-tuned model
    │
    ├── notebooks          <- 用于存放 jupyter 文件
    │
    ├──  output         <- 用于存放模型训练结果
    │
    ├── requirements.txt   <- 依赖环境
    │
    ├── src                <- 用于此项目的源代码
    │   ├──__init__.py    <- 将src变为Python模块
    │   │
    │   ├── data           <- 下载、生成或转换数据的脚本
    │   │
    │   ├── models         <- 用于存储模型相关文件
    │   │
    │   └──  utils  <- 用于存储辅助工具相关代码
    │
    └── .env            <- 用于存储环境变量的简单配置文件
