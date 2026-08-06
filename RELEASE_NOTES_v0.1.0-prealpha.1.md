# v0.1.0-prealpha.1 — macOS Universal

这是《任何人都能看懂并上手的 EMBA 课程！》第一次公开提供下载的 macOS 体验版本。

## 下载与安装

- 下载 DMG，打开后将游戏拖入 `Applications`。
- 支持 Apple Silicon `arm64` 与 Intel `x86_64`。
- 当前使用 ad-hoc 签名，尚未进行 Apple Developer ID 公证。如果 macOS 首次阻止打开，请在 Finder 的“应用程序”中右键游戏，选择“打开”，再确认一次。

## 发布前验证

- 完整回归：58 套件，385 passed，0 failed，0 broken。
- 异步表现专项：23 passed，0 failed。
- DMG 镜像校验通过。
- Universal 双架构检查通过。
- 挂载后的签名结构与无界面启动检查通过。

## 文件校验

- 文件：`任何人都能看懂并上手的EMBA课程_v0.1.0-prealpha.1_macOS_Universal.dmg`
- 大小：346,573,554 bytes（约 330.5 MiB）
- SHA-256：`0f1ef9a27aa32f52d60caa72f8a068b9a5ffd39723d26300eb4657dd6a3921f5`

## 发行边界

这是 pre-alpha 体验版本，尚未经过 Apple 公证、应用商店审核或大规模兼容性测试。本仓库当前只发布安装包与说明，不公开源代码，也不决定项目源码许可证。
