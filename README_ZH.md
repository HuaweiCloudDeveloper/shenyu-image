 <h1 align="center">ShenYu网关</h1>
  <p align="center">
    <a href="README.md"><strong>English</strong></a> | <strong>简体中文</strong>
  </p>


## 目录

- [仓库简介](#项目介绍)
- [前置条件](#前置条件)
- [镜像说明](#镜像说明)
- [获取帮助](#获取帮助)
- [如何贡献](#如何贡献)

## 项目介绍

[shenyu](https://github.com/apache/shenyu)  是一个异步、高性能、跨语言、响应式的API网关，支持多种协议和插件化扩展，主要用于流量管理、API治理及可观测性。本商品基于鲲鹏服务器的Huawei Cloud EulerOS 2.0 64bit系统，提供开箱即用的shenyu。

## 核心特性

- **协议支持‌：** 兼容 Dubbo 、 Spring Cloud 、gRPC、 Motan 、 SOFA 、 Tars 等主流协议。
- **‌流量管理‌：** 支持动态流量控制、熔断、限流（支持Hystrix）、黑白名单过滤等功能，并提供可视化界面操作。 
- **‌可观测性‌：** 集成 SkyWalking 实现分布式链路追踪和性能监控，支持跟踪、指标、日志记录。 
- **扩展性‌：** 插件热插拔机制，支持自定义开发插件，适配复杂业务场景。

本项目提供的开源镜像商品 [**shenyu网关**](https://marketplace.huaweicloud.com/contents/564d306e-87f0-4ba3-b4b4-5dd57a915468#productid=OFFI1141938188136427520) 已预先安装2.5.1版本的shenyu及其相关运行环境，并提供部署模板。快来参照使用指南，轻松开启“开箱即用”的高效体验吧。


> **系统要求如下：**
> - CPU: 2vCPUs 或更高
> - RAM: 4GB 或更大
> - Disk: 至少 40GB

## 前置条件
[注册华为账号并开通华为云](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## 镜像说明

| 镜像规格                                                                                                   | 特性说明 | 备注 |
|--------------------------------------------------------------------------------------------------------| --- | --- |
| [shenyu-2.5.1-kunpeng](https://github.com/HuaweiCloudDeveloper/shenyu-image/tree/shenyu-2.5.1-kunpeng) | 基于鲲鹏服务器 + Huawei Cloud EulerOS 2.0 64bit 安装部署 |  |

## 获取帮助
- 更多问题可通过 [issue](https://github.com/HuaweiCloudDeveloper/shenyu-image/issues) 或 华为云云商店指定商品的服务支持 与我们取得联系
- 其他开源镜像可看 [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## 如何贡献
- Fork 此存储库并提交合并请求
- 基于您的开源镜像信息同步更新 README.md