# 杨桃 YangTao

一只装在口袋里的小伙伴：会眨眼、聊天、互动，也可以作为机器人收音的手机录音笔。

## App 下载 · 两款选一个

| 版本 | 安装包 | 大小 | 功能 |
| --- | --- | ---: | --- |
| 离线转写版 | [asr.apk](https://github.com/zhishuir/yangtao-companion-download/releases/download/v1.6.7-offline/asr.apk) | 约 63MB | 机器人收音、手机保存/播放/删除、离线中文转写 |
| 离线摘要版 | [model.apk](https://github.com/zhishuir/yangtao-companion-download/releases/download/v1.6.7-offline/model.apk) | 约 479MB | 转写版全部功能，加手机离线生成标题、要点和待办 |

两款均内置所需模型，无需另外下载识别模型、申请云账号或填写 API Key。摘要版首次使用建议手机预留至少 2GB 空间。**离线处理在手机上运行，不是 ESP32 本机运行大模型**；录音时手机与机器人仍须处在可以互访的同一局域网。

支持目标为 Android 8.0 及以上 ARM64 手机；不同安卓或鸿蒙 APK 运行环境的表现以真机测试为准。两款使用同一应用包名、同一签名，不能并排安装。已有同签名旧版请覆盖升级，别先卸载，以免丢失本机录音和积分。摘要版可覆盖转写版；从摘要版回到转写版可能受到系统禁止降级安装的限制。

**App 1.6.8 更新**：两款均移除首页和帮助页的“首次使用：配网与激活”页面；保留机器人地址连接与普通换网帮助。两款都可以覆盖此前公开的 1.6.6/1.6.7 同签名版本。下载文件名及地址不变，原有二维码仍有效。固定下载入口的标签 `v1.6.7-offline` 不代表当前 APK 内部版本。

录音需机器人配套 **yt-1.6.8-recording-r1** 固件；旧固件不支持录音接口。安装 App 不会自动升级机器人固件。

## 使用与打印

- [完整使用指南](USER_GUIDE.md)：介绍 App 连接、录音、转写、离线摘要、时钟、天气互动、提醒与小游戏。
- [新版 16 面说明书 · 105×99mm](yangtao-manual-16p-105x99mm.pdf)：封面后展示绘制的 App 页面，不再包含首次激活专页；正常阅读顺序，可交打印店拼版。
- [16 个单页 PDF 打印包](yangtao-manual-16-single-pages.zip)：方便打印店逐页排版、双面装订。
- [新增功能双面页](yangtao-new-features-front-back.pdf)：离线摘要、时钟与天气互动。
- [下载页与更新记录](https://github.com/zhishuir/yangtao-companion-download/releases/tag/v1.6.7-offline)
- [安装包校验与版本信息](APP_MANIFEST.json)

联网 AI 对话与手机离线转写/摘要是不同能力。云端聊天仍需机器人联网并激活；本地动画不依赖云端大模型。天气表情仅为互动动画，不是实时天气预报。
