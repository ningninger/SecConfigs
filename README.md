# SecConfigs

## 概述

`SecConfigs` 是一个专用于 `tai-e` 中污点分析的配置文件的仓库，旨在提供结构化且易于维护的安全配置。目前包含406条source，995条sink，以及138条transfer


## 配置文件说明

配置文件归属于其目录文件名的特定的安全分析，这些配置可以直接应用于 `tai-e` 环境中。配置文件使用 YAML 格式，便于阅读和编辑。


## 配置文件结构

```
taint-config/
│
├── infoleak/
│   ├── sink/           包含141条sink
│   ├── source/         包含158条source
│   └── transfer/       包含关于String的138条transfer  
│
├── injection/
│   ├── sink/           包含854条sink
│   ├── source/         包含248条source
│   └── transfer/       包含关于String的138条transfer
```