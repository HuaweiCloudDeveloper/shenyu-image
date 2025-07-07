<h1 align="center">ShenYu Gateway</h1>
<p align="center">
    <strong>English</strong> | <a href="README_ZH.md">简体中文</a>
</p>

## Table of Contents

- [Repository Introduction](#project-introduction)
- [Prerequisites](#prerequisites)
- [Image Description](#image-description)
- [Get Help](#get-help)
- [How to Contribute](#how-to-contribute)

## Project Introduction

[shenyu](https://github.com/apache/shenyu) is an asynchronous, high-performance, cross-language, and reactive API gateway that supports multiple protocols and plug-in extensions. It is mainly used for traffic management, API governance, and observability. This product is based on the Huawei Cloud EulerOS 2.0 64-bit system of Kunpeng servers, providing an out-of-the-box Shenyu solution.

## Core Features

- **Protocol Support**: Compatible with mainstream protocols such as Dubbo, Spring Cloud, gRPC, Motan, SOFA, and Tars.
- **Traffic Management**: Supports dynamic traffic control, circuit breaking, rate limiting (supports Hystrix), black and white list filtering, etc., and provides a visual interface for operation.
- **Observability**: Integrates SkyWalking to implement distributed traceability and performance monitoring, supporting tracing, metrics, and logging.
- **Extensibility**: Adopts a hot-pluggable mechanism for plugins, supporting custom plugin development to adapt to complex business scenarios.

The open-source image product [**ShenYu Gateway**](https://marketplace.huaweicloud.com/intl/hidden/contents/784e14bb-7e44-45b1-a0ad-a756a82a685e) provided by this project has pre-installed ShenYu version 2.5.1 and its related operating environment, and provides deployment templates. Refer to the usage guide and start your "out-of-the-box" efficient experience now!

> **System Requirements**:
> - CPU: 2vCPUs or higher
> - RAM: 4GB or more
> - Disk: At least 40GB

## Prerequisites

[Register a Huawei account and activate Huawei Cloud](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## Image Description

| Image Specification                                                                                                   | Feature Description | Remarks |
|-----------------------------------------------------------------------------------------------------------------------| --- | --- |
| [shenyu-2.5.1-kunpeng](https://github.com/HuaweiCloudDeveloper/shenyu-image/tree/shenyu-2.5.1-kunpeng) | Installed and deployed based on Kunpeng servers + Huawei Cloud EulerOS 2.0 64-bit |  |

## Get Help

- For more questions, you can contact us via [issues](https://github.com/HuaweiCloudDeveloper/shenyu-image/issues) or the service support of the specified product in the Huawei Cloud Marketplace.
- For other open-source images, refer to [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos).

## How to Contribute

- Fork this repository and submit a merge request.
- Synchronously update README.md based on your open-source image information.