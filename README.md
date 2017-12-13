# Wawaji from Agora

*Read this in other languages: [English](README.en.md)*


### 因为业务需求的多样性，我们目前采用分支来区分各个场景的示例代码
#### 每个场景均包含 H5 功能

- master 一般默认分支 目前留空

- rtc-only 只包含实时音视频通讯部分(需要自己集成娃娃机控制功能，H5 页面需要自己部署)

- rtc-simple-control 包含客户端应用结合娃娃机控制功能(应用直接控制娃娃机，已经集成多家娃娃机供应商控制代码，无需部署服务端程序，H5 页面需要自己部署)

- solution 完整的方案(包含完整的客户端应用和服务端程序，已经集成多家娃娃机供应商控制代码，需要自己部署服务端程序，可支持不同娃娃机供应商同时在线)

### 根据不同的场景，以上示例代码都需要做不同的配置才可以运行

- **注意，本娃娃机项目需要开发者增加娃娃机控制协议**
- **为了安全，建议大家在正式环境中启用 [动态密钥鉴权](https://document.agora.io/cn/1.14/instruction/key.html) 机制**

这个开源示例项目演示了如何利用 Agora 视频 SDK，实现抓娃娃游戏当中的音视频部分功能。

不同平台参看项目内的 README.md 文档

点击 [官网](https://www.agora.io/cn/zhuawawa/) 查看更多信息

# 如需进一步了解，请联系 400 632 6626。
