# 考拉红果剧场

iOS 与 Android 统一版本：**1.0.2**。

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
