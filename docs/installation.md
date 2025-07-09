# Shenyu部署指南

## ‌一、环境准备
### 系统配置
> -  服务器：鲲鹏服务器
> -  操作系统：Huawei Cloud EulerOS 2.0 64bit 
> - CPU: 2vCPUs 或更高
> - RAM: 4GB 或更大
> - Disk: 至少 40GrB

### 前置条件
> -  运行环境：JDK1.8+

## ‌二、安装部署部署

### 下载安装包

#### 下载启动 Apache ShenYu Admin

```bash
cd /opt
wget https://archive.apache.org/dist/shenyu/2.5.1/apache-shenyu-2.5.1-admin-bin.tar.gz
tar -zxvf apache-shenyu-2.5.1-admin-bin.tar.gz
cd apache-shenyu-2.5.1-admin-bin/bin
./start.sh
```

#### 下载启动 Apache ShenYu Admin
```bash
cd /opt
wget https://archive.apache.org/dist/shenyu/2.5.1/apache-shenyu-2.5.1-bootstrap-bin.tar.gz
tar -zxvf apache-shenyu-2.5.1-bootstrap-bin.tar.gz
cd apache-shenyu-2.5.1-bootstrap-bin/bin
./start.sh
```