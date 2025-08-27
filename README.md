# sleepy

> fork 于 [sleepy](https://github.com/sleepy-project/sleepy)

一个用于 ~~*视奸*~~ 查看个人在线状态 (以及正在使用软件) 的 Flask 应用，让他人能知道你不在而不是故意吊他/她

[**功能**](#功能) / [**演示**](#preview) / [**部署**](#部署--更新) / [**服务端配置**](#服务器配置) / [**使用**](#使用) / [**Client**](#client) / [**API**](#api) / [**关于**](#关于)

## 功能

- [x] 自行设置在线状态 *(活着 / 似了 等, 也可 **[自定义](./setting/README.md#status_listjson)** 状态列表)*
- [x] 实时更新设备使用状态 *(包括 是否正在使用 / 打开的应用名, 通过 **[client](./client/README.md)** 主动推送)*
- [x] 美观的展示页面 [见 [Preview](#preview)]
- [x] 开放的 Query / Metrics [接口](./doc/api.md), 方便统计
- [x] 支持 HTTPS (需要自行配置 SSL 证书)

### 部署地址

**[Lian Alive?](https://qlive.yeastar.xin)**

## 部署 / 更新

请移步 **[部署教程](./doc/deploy.md)** 或 **[更新教程](./doc/update.md)** *(多图警告)*

## 客户端

搭建完服务端后，你可在 **[`/client`](./client/README.md)** 找到客户端 (用于**手动更新状态**/**自动更新设备打开应用**)

*目前已有 [Windows](./client/README.md#windevice), [Linux](./client/README.md#linux), [IOS / MacOS](./client/README.md#iosmacos), [Android](./client/README.md#autoxjsscript), [油猴脚本](./client/README.md#browserscript) 等客户端*

## API

详细的 API 文档见 [doc/api.md](./doc/api.md).
