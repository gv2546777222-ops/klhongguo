# 考拉红果剧场

Android、iOS 与 macOS 最新版：**1.4.12（58）**。

## Android / iOS / macOS 1.4.12（58）

Android 同步 iOS 桌面客户端短信登录、设备注册、账号会话和额外短信验证；保留网页及二维码登录。

| 平台 | 安装包 | 完整工程 |
| --- | --- | --- |
| Android 8.0+ / 64 位 | [APK](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.12/Hongguo-Android-1.4.12-release.apk) | [Android 工程](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.12/Hongguo-Android-1.4.12-source.zip) |
| iOS 15.0+ / arm64 | [待签名 IPA](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.12/Hongguo-iOS-1.4.12-unsigned.ipa) | [iOS 工程](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.12/Hongguo-iOS-1.4.12-source.zip) |
| macOS / Apple Silicon | [桌面版](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.12/Hongguo-macOS-1.4.12-arm64.zip) | [macOS 工程](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.12/Hongguo-macOS-1.4.12-source.zip) |

[发布说明](https://github.com/gv2546777222-ops/klhongguo/releases/tag/v1.4.12) · [SHA256 校验](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.12/SHA256SUMS-1.4.12.txt)

Android 保持原签名，可覆盖安装；iOS 需自行签名，macOS 为自签名构建。Android 169 项源码测试、9 项 JVM 测试、22 项模拟器设备测试以及构建和安装启动通过。短信登录使用隔离测试数据，未发送真实短信；实体设备和真实账号未全面验收。苹果端验证记录随源码提供。各组件来源和权利说明见下方许可声明及源码包。

## Android / iOS 1.4.10（56）

累计同步苹果 **1.4.7–1.4.10**：推荐等待页改为简洁动效，缓存未看候选并提前准备下一条详情和播放地址；滑动确认立即暂停旧视频。停滞先唤醒，再按预算恢复原集与进度；竖屏等比铺满到进度条触控区域顶部；修复浏览两分钟后“加载更多”丢失游标及失败后重试错页。

| 平台 | 安装包 | 完整工程 |
| --- | --- | --- |
| Android 8.0+ / 64 位 | [APK](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.10/Hongguo-Android-1.4.10-release.apk) | [Android 工程](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.10/Hongguo-Android-1.4.10-source.zip) |
| iOS 15.0+ / arm64 | [待签名 IPA](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.10/Hongguo-iOS-1.4.10-unsigned.ipa) | [iOS 工程](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.10/Hongguo-iOS-1.4.10-source.zip) |

[发布说明](https://github.com/gv2546777222-ops/klhongguo/releases/tag/v1.4.10) · [统一 SHA256](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.10/SHA256SUMS-1.4.10.txt)

Android 保持原签名可覆盖安装；165 项源码测试、9 项 JVM、21 项原生仪器测试及构建通过。真实视频受控故障验证同集恢复和主动暂停；推荐连续切换、画幅、评论、进度定位、自动下一集、兼容完整视频与目录分页回归通过。iOS 使用苹果端已验收的 1.4.10（56）原包，本轮核对与对应源码一致；145 项源测试及真实播放 / 画幅 / 分页为苹果对话已执行记录。两端仍保留 V5 播放、四导航、近期去重和既有账号功能。

原偶发卡顿未在实体设备自然复现；网络或解码仍可能等待。一次推荐首屏失败经重试成功，实体 vivo / iPhone、所有片源与私人账号写入未全面验收。开源应用代码与独立来源协议镜像的权利区别继续有效，详见下方来源声明与工程内 LICENSE-NOTICE.md / UPSTREAM.md / image-provenance.json。

## Android / iOS 1.4.6（52）

同步苹果端最新推荐首页：原品牌栏与首页 / 剧场 / 搜索 / 我的四个导航共用，推荐 / 真人剧 / 漫剧直接播放。上下滑动换剧，完整剧集进入原播放器；返回首页继续下一条，重启后跳过近期已看内容，并兼容原有本机观看记录。

| 平台 | 安装包 | 完整工程 |
| --- | --- | --- |
| Android 8.0+ / 64 位 | [APK](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.6/Hongguo-Android-1.4.6-release.apk) | [Android 工程](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.6/Hongguo-Android-1.4.6-source.zip) |
| iOS 15.0+ / arm64 | [待签名 IPA](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.6/Hongguo-iOS-1.4.6-unsigned.ipa) | [iOS 工程](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.6/Hongguo-iOS-1.4.6-source.zip) |

[发布说明](https://github.com/gv2546777222-ops/klhongguo/releases/tag/v1.4.6) · [统一 SHA256](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.6/SHA256SUMS-1.4.6.txt)

Android 保持原签名可覆盖安装；保留 V5 播放修复、解码恢复与应用内更新，更新提示不会被原生视频遮挡。158 项源码测试、6 项 JVM、19 项原生仪器测试、类型检查和构建通过；11 个真实推荐场景及普通播放 / 进度定位 / 自动下一集回归通过。iOS 使用已验收的 1.4.6（52）原包，苹果端完成 138 项源码测试及真实播放、导航、重启去重验证，本轮核对原包与对应源码一致。

推荐来自设备推荐源，不承诺与官方登录账号个性化排序一致；实体 vivo / iPhone、全部片源和私人账号写入未全面验收。开源应用代码与独立来源协议镜像的权利区别继续有效，详见下方来源声明及工程中的 LICENSE-NOTICE.md / UPSTREAM.md / image-provenance.json。

## Android / iOS 1.4.4（50）

同步苹果端最新 V5 播放修复：新播放器接口、设备配置、实际正文与 Field13 / Medusa / Helios 签名，修复旧模型接口空响应。网页兼容旧请求空正文后可有界回退到 V5；进度、暂停状态、画质、完整时长与来源缓存隔离保持原规则。

| 平台 | 安装包 | 完整工程 |
| --- | --- | --- |
| Android 8.0+ / 64 位 | [APK](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.4/Hongguo-Android-1.4.4-release.apk) | [Android 工程](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.4/Hongguo-Android-1.4.4-source.zip) |
| iOS 15.0+ / arm64 | [待签名 IPA](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.4/Hongguo-iOS-1.4.4-unsigned.ipa) | [iOS 工程](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.4/Hongguo-iOS-1.4.4-source.zip) |

[发布说明](https://github.com/gv2546777222-ops/klhongguo/releases/tag/v1.4.4) · [统一 SHA256](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.4/SHA256SUMS-1.4.4.txt)

Android 保持原签名可覆盖安装；iOS 需自行签名。Android 146 项源码测试、6 项 JVM、18 项原生仪器测试与构建通过，真实验证第 60 集播放、拖动续播、自动第 61 集、兼容编码及网页兼容完整视频定位。iOS 采用已验收的 1.4.4（50）原包，126 项源码测试、3 项真实网络原生播放测试与 Release 构建通过；本次核对原包与最终源码一致。

组件来源不同：开源应用代码保持原许可；操作者提供的客户端协议镜像保留原权利，不被重新许可为 GPL，也不主张原权利人已授予公开再分发许可。因此不能将此兼容构建称为全 GPL 的公开实现。来源与权利说明见工程内 LICENSE-NOTICE.md、UPSTREAM.md 和 v5/image-provenance.json。

实体 vivo / iPhone、全部片源与私人账号写入未全面验收；依赖非公开上游协议，仍可能需要后续维护。

## Android / iOS 1.4.3（49）

两端同步完整播放签名、空响应短退避与有界互补接口，提供自动 / App / 网页兼容线路。切换保留当前集、进度、倍速和暂停状态，缓存按来源隔离；同画质备用地址与完整时长校验避免把试看当正片。Android 保留已有解码兼容恢复与应用内更新。

| 平台 | 安装包 | 完整源码 |
| --- | --- | --- |
| Android 8.0+ / 64 位 | [APK](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.3/Hongguo-Android-1.4.3-release.apk) | [Android 源码](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.3/Hongguo-Android-1.4.3-source.zip) |
| iOS 15.0+ / arm64 | [待签名 IPA](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.3/Hongguo-iOS-1.4.3-unsigned.ipa) | [iOS 源码](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.3/Hongguo-iOS-1.4.3-source.zip) |

[发布说明](https://github.com/gv2546777222-ops/klhongguo/releases/tag/v1.4.3) · [统一 SHA256](https://github.com/gv2546777222-ops/klhongguo/releases/download/v1.4.3/SHA256SUMS-1.4.3.txt)

Android 沿用原签名，可覆盖安装；iOS 需自行签名。Android 143 项逻辑测试、6 项 JVM、18 项原生仪器测试与构建通过，真实网络完成续播、切集、暂停换线与完整兼容视频定位。iOS 使用已验收的 1.4.3（49）原包，123 项逻辑测试、3 项最终真实 UIKit 播放、2173 项 MP4/CENC 和 URLSession 检查及构建通过。各源码内保留具体证据、诊断复核及限制。

两条线路仍依赖同一上游，间歇空响应可能发生；实体 vivo X200s、实体 iPhone、全部片源和真实账号互动未全面验收。

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

应用开源代码采用 GPL-3.0-only，保留原始项目署名和第三方许可；1.4.4 起包含的独立来源协议镜像不被该许可覆盖，详见上述来源与权利说明。取源和协议模块参考 [jackotom/hongguo-drama](https://github.com/jackotom/hongguo-drama)，账号 / 收藏协议另参考 [tsukiyo-zero/hongguoTV](https://github.com/tsukiyo-zero/hongguoTV)。完整修订和变更说明见源码包内 vendor/hongguo/UPSTREAM.md。

本项目为独立客户端。
