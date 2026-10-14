# whatevertools Inspector — 下载

**whatevertools Inspector** 的公开分发仓库(只放 macOS 二进制,无源码)。

一个独立的 macOS 调试器:加载单独一个 uTools 插件包(`.upxs` / `.upx` / `.asar` / `.zip` / 目录),
用 [whatevertools](https://whatevertools.mowtwo.com) 运行时跑起来,带日志、API 调用跟踪和开发者工具。

- 仅 **Apple Silicon(arm64)**。
- **版本不稳定**,会随 uTools 版本变化而失效,仅供调试自查。
- 只针对离线固定密钥的开发者包;不公开解密细节,也不绕过任何付费校验。

## 下载

👉 **[Releases](https://github.com/mowtwo/whatevertools-inspector-dist/releases/latest)**

## 首次打开(免签说明)

二进制只做 ad-hoc 签名、未经 Apple 公证,首次打开会被 Gatekeeper 拦。任选其一:

- 右键 App →「打开」→ 再点「打开」;或
- 终端执行:`xattr -dr com.apple.quarantine "/Applications/whatevertools Inspector.app"`
