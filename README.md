# Taffy Wiki Tool

Taffy Wiki Tool 是面向 Windows 的录播检索与 Wiki 辅助工具。

## 下载

请从本仓库的 Releases 页面下载带有 `win64-nuitka.zip` 后缀的版本，并使用同一 Release 中的 `SHA256SUMS.txt` 校验文件完整性。

## 发布包内容

- `TaffySearchTool.exe`：Windows 可执行程序；
- 程序运行所需的 DLL 和资源文件；
- `使用指南.md`：可由作者维护的指南文档；
- `release_manifest.json`：逐文件大小和 SHA256 清单。

公开分发仓库不包含 Python 源码。纯净发布包不预置运行缓存、API 配置、个人设置、日志或生成文件；这些内容只会在用户首次启动和配置后写入本地应用目录。

## 数据位置

默认情况下，缓存和设置保存在应用程序所在目录的 `data` 文件夹内，图片保存在同级 `picture` 文件夹内。首次启动时程序会初始化所需缓存，再引导用户填写 API Key。

## 作者

- [Bilibili 主页](https://space.bilibili.com/361655499)
- [Taffy Wiki](https://acetaffy.org/)
