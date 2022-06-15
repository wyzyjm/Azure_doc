# Azure 简介

-   Azure 是一个云平台, 提供许多服务, 这些服务可以单独使用也可以配套使用

## Azure 服务 - JS 人员常用

-   DevOps
    -   项目管理
-   Authentication and authorization
    -   身份验证
-   Containers
    -   容器
-   VMs
    -   虚拟机
-   Databases
    -   数据库
-   Storage

    -   存储

-   Hosting
-   Search
    -   搜索
-   Cognitive services
-   Metrics and logging
    -   指标和日志

## 使用前提

创建 Azure 账户

## 准备开发环境

1. VScode
    - Azure Tools
    - Docker
2. Git
3. Node.js
    - NVM 管理 node 版本
    - Docker 容器安装 node 环境
4. Azure CLI
5. 本地 CLI
    - Static Web App CLI
    - Azure Functions Core Tools

## 使用 Azure SDK

-   所有 Azure SDK 都支持 js 调用, 安装对应的 NPM 包就行

## 托管方案

1.  Azure Static Web Apps 托管前端
    -   React
    -   Vue
2.  Azure app service 托管后端
    -   node.js + express + postgreSQL, 只有 Nodejs 的情况
    -   容器化部署, 适用于项目环境比较复杂的情况
3.  Azure Virtual Machines 托管 Linux 应用程序
4.  Azure Functions 托管无服务 API
