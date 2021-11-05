# Android 示例项目

_[English](README.md) | 中文_

## 简介

该仓库包含了使用 RTC XXX SDK 的示例项目。

**项目运行效果图**

## 项目结构

此项目使用一个单独的 app 实现了多种功能。

| 功能                                             | 位置                                                                                                                    |
| ------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------- |
| 功能描述                                         | 源文件链接                  |
| 功能描述                                         | 源文件链接                  |
| ...                                              | ...                  |

## 如何运行示例项目

### 前提条件

- 
- 

### 运行步骤

**从拉取仓库到成功运行的全部步骤**

1. 
2. 
3. 编辑 XXX 文件，进行以下操作：（设置 App ID 和 Token 的 config 文件）

   - 将 `YOUR APP ID` 替换为你的 App ID。
   - 将 `YOUR ACCESS TOKEN` 替换为你的 Access Token。

   ```xml
   <string name="agora_app_id" translatable="false">YOUR APP ID</string>
   <string name="agora_access_token" translatable="false">YOUR ACCESS TOKEN</string>
   ```

   > 参考 [校验用户权限](https://docs.agora.io/cn/Agora%20Platform/token) 了解如何获取 App ID 和 Token。你可以获取一个临时 token，快速运行示例项目。
   >
   > 生成 Token 使用的频道名必须和加入频道时使用的频道名一致。

   > 为提高项目的安全性，Agora 使用 Token（动态密钥）对即将加入频道的用户进行鉴权。
   >
   > 临时 Token 仅作为演示和测试用途。在生产环境中，你需要自行部署服务器签发 Token，详见[生成 Token](https://docs.agora.io/cn/Interactive%20Broadcast/token_server)。

4. 

一切就绪。你可以自由探索示例项目，体验 SDK 的丰富功能。

## 反馈

如果你有任何问题或建议，可以通过 issue 的形式反馈。

## 参考文档

- [RTC Java SDK 产品概述](https://docs.agora.io/cn/Interactive%20Broadcast/product_live?platform=Android)
- [RTC Java SDK API 参考](https://docs.agora.io/cn/Interactive%20Broadcast/API%20Reference/java/index.html)

## 相关资源

- 你可以先参阅[常见问题](https://docs.agora.io/cn/faq)
- 如果你想了解更多官方示例，可以参考[官方 SDK 示例](https://github.com/AgoraIO)
- 如果你想了解声网 SDK 在复杂场景下的应用，可以参考[官方场景案例](https://github.com/AgoraIO-usecase)
- 如果你想了解声网的一些社区开发者维护的项目，可以查看[社区](https://github.com/AgoraIO-Community)
- 若遇到问题需要开发者帮助，你可以到[开发者社区](https://rtcdeveloper.com/) 提问
- 如果需要售后技术支持, 你可以在[Agora Dashboard](https://dashboard.agora.io) 提交工单

## 代码许可

示例项目遵守 MIT 许可证。
