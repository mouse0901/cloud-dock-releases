# 云屿 Cloud Dock

云屿是面向 Windows 的百度网盘与夸克网盘聚合客户端。

## 下载

- [下载 v0.6.2 测试版](https://github.com/mouse0901/cloud-dock-releases/releases/tag/v0.6.2)
- 测试版请在 [Releases](https://github.com/mouse0901/cloud-dock-releases/releases) 页面选择带有 `Pre-release` 标记的版本。

推荐普通用户下载 `CloudDock-版本号-Setup-x64.exe`。便携版 ZIP 适合免安装试用，但自动安装更新仅在安装版中启用。

## 安全校验

每个版本都附带 `CHECKSUMS.sha256`。应用内更新还会验证固定在客户端中的 RSA 公钥签名、文件大小与 SHA-256；校验失败时不会启动安装程序。

`channels/` 仅保存应用读取的签名更新清单，不包含账号、Cookie 或网盘文件。
