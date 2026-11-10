# 考拉红果剧场

Android 与 iOS 最新版：**1.4.1（47）**。

## Android / iOS 1.4.1（47）

两端统一版本与构建号，修复旧接口空响应导致无法播放。iOS 同步当前 GET 取址和匿名注册 Cookie 传递，已在模拟器实际验证播放、进度定位、播完自动进入下一集，以及此前 ByteVC2 剧集的兼容媒体播放。

| 平台 | 安装包 | 完整源码 |
| --- | --- | --- |
| Android 8.0+ / 64 位 | [APK](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.1/Hongguo-Android-1.4.1-release.apk) | [Android 源码](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.1/Hongguo-Android-1.4.1-source.zip) |
| iOS 15.0+ / arm64 | [待签名 IPA](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.1/Hongguo-iOS-1.4.1-unsigned.ipa) | [iOS 源码](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.1/Hongguo-iOS-1.4.1-source.zip) |

[发布说明](https://github.com/gv2546777222-ops/klhongguo/releases/tag/v1.4.1) · [统一 SHA256](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.1/SHA256SUMS-1.4.1.txt)

Android 保持原签名可覆盖安装；iOS 需自行签名。iOS 104 项共享测试、2 项真实网络播放 UI 测试、Cookie / 流式检查及构建通过；Android 120 项共享测试、6 项 JVM、构建 / lint 和最终包覆盖安装启动通过。Android 的 7 个真实播放场景 / 17 项仪器测试是在相同播放实现的前一构建上完成，本轮未全部重跑。实体设备、真实账号互动和全部剧集未全面验证；具体证据见各源码内 1.4.1 验证记录。

以下保留历史版本说明。

## iOS 1.4.0

底部导航改为“我的”，移除播放页右上角清屏快捷按钮，重新整理评论正文、点赞、回复和输入栏。包含截至 1.3.8 的播放与兼容片源修复。

[下载待签名 IPA](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.0/Hongguo-iOS-1.4.0-unsigned.ipa) · [完整 iOS 源码](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.0/Hongguo-iOS-1.4.0-source.zip) · [发布说明](https://github.com/gv2546777222-ops/klhongguo/releases/tag/v1.4.0) · [SHA256](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.0/SHA256SUMS-iOS-1.4.0.txt)

iOS 15.0+（arm64），需要自行签名。99 项共享测试及 2 项 iOS 模拟器 UI 测试通过；评论截图使用本地示例数据。实体设备、真实账号互动和全部片源未全面验证，完整范围见源码内 docs/VERIFICATION-1.4.0.md。

## Android 1.3.9

启动与返回应用时检查正式更新，有新版自动提示；APK 在应用内下载、显示进度并可取消，校验后调用系统安装界面。播放器设置移除重复选集，底部导航改为“我的”，保留剧情简介展开和播放兼容恢复。

[下载 Android APK](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.3.9/Hongguo-Android-1.3.9-release.apk) · [完整 Android 源码](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.3.9/Hongguo-Android-1.3.9-source.zip) · [发布说明](https://github.com/gv2546777222-ops/klhongguo/releases/tag/v1.3.9) · [SHA256](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.3.9/SHA256SUMS)

沿用原签名，可覆盖安装，Android 8.0+（arm64-v8a / x86_64）。首次安装本版后，后续更新可在应用内完成；首次可能需允许本应用安装更新。114 项共享测试、17 项 Android 仪器测试、6 项 JVM 测试与实际下载验证通过，实体机未验证。完整工程、对应 FFmpeg 源码和许可在源码 ZIP 内。

以下保留历史双端 1.0.2 的下载与说明。

支持剧集搜索、热播推荐、相关季、弹幕、公开评论、前后各两集缓存、自动换季 / 热播续播、账号入口与收藏同步。页面底部可检查本仓库的正式 Releases 更新。

1.0.2 改进评论预览：竖屏视频在上、评论在下，横屏左右分区；阅读和收起评论保留播放器及播放状态，滚动评论不切集。iOS 同步安全区域、账号导入归属修复，并按实际包含 IPA 的正式版本检查更新。

## 下载 1.0.2

| 平台 | 安装包 | 完整源码 |
| --- | --- | --- |
| Android 8.0+（64 位） | [APK](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.0.2/Hongguo-Android-1.0.2-release.apk) | [Android 源码](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.0.2/Hongguo-Android-1.0.2-source.zip) |
| iOS 15+ | [待签名 IPA](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.0.2/Hongguo-iOS-1.0.2-unsigned.ipa) | [iOS 源码](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.0.2/Hongguo-iOS-1.0.2-source.zip) |

[发布说明与全部附件](https://github.com/gv2546777222-ops/klhongguo/releases/tag/v1.0.2) · [Android SHA256](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.0.2/SHA256SUMS) · [iOS SHA256](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.0.2/SHA256SUMS-iOS-1.0.2.txt)

安卓 APK 沿用原签名，可覆盖旧版。iOS IPA 需使用自己的工具签名安装。完整工程、构建脚本、固定的 FFmpeg 源码、许可及验证记录包含在各平台源码 ZIP 内。

## 验证范围

安卓源码、原生地址校验、账号隔离、真实视频续播、缓存和覆盖升级回归通过。iOS 的验证记录随对应源码提供。实体设备、私人账号及与官方收藏的真实互通仍需安装后自行登录验收；可播放范围和季关系取决于来源实际返回的数据。

## 许可与来源

采用 GPL-3.0-only，保留原始项目署名和第三方许可。取源和协议模块参考 [jackotom/hongguo-drama](https://github.com/jackotom/hongguo-drama)，账号 / 收藏协议另参考 [tsukiyo-zero/hongguoTV](https://github.com/tsukiyo-zero/hongguoTV)。完整修订和变更说明见源码包内 vendor/hongguo/UPSTREAM.md。

本项目为独立客户端。
