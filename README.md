# Taffy Wiki Tool

Taffy Wiki Tool 是面向 Windows 的录播检索与 Wiki 辅助工具。

## 下载

请从本仓库的 Releases 页面下载带有 `win64-nuitka.zip` 后缀的版本，并使用同一 Release 中的 `SHA256SUMS.txt` 校验文件完整性。

已经安装正式版的用户可以直接使用应用内的“一键更新并重启”。程序会验证发布包和逐文件清单，只替换程序文件，并保留本地设置、API Key、缓存、日志与图片。

## 发布包内容

- `TaffySearchTool.exe`：Windows 可执行程序；
- 程序运行所需的 DLL 和资源文件；
- 应用内置的项目简介与使用指南；
- `release_manifest.json`：逐文件大小和 SHA256 清单。

公开分发仓库不包含 Python 源码。纯净发布包不预置运行缓存、API 配置、个人设置、日志或生成文件；这些内容只会在用户首次启动和配置后写入本地应用目录。

## 数据位置

默认情况下，缓存和设置保存在应用程序所在目录的 `data` 文件夹内，图片保存在同级 `picture` 文件夹内。首次启动时程序会先显示使用指南，再初始化所需缓存并引导用户填写 API Key。

自动更新不会覆盖 `data` 与 `picture`。更新失败时，独立更新器会尝试恢复旧版程序文件。

## 作者

- [Bilibili 主页](https://space.bilibili.com/361655499)
- [Taffy Wiki](https://acetaffy.org/)
