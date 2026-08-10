# Taffy Wiki Tool

Taffy Wiki Tool 是面向 Windows 的录播检索与 Wiki 辅助工具。

## 下载

请从本仓库的 Releases 页面下载带有 `win64-nuitka.zip` 后缀的版本，并使用同一 Release 中的 `SHA256SUMS.txt` 校验文件完整性。

## 发布包内容

- `TaffySearchTool.exe`：Windows 可执行程序；
- 程序运行所需的 DLL 和资源文件；
- `data/cache`：随版本发布的录播、分类与 Wiki 缓存；
- `settings.example.ini`：不含 API Key 的配置示例；
- `使用指南.md`：可由作者维护的指南文档；
- `release_manifest.json`：逐文件大小和 SHA256 清单。

公开分发仓库不包含 Python 源码。首次启动后产生的 API Key、个人设置、日志和生成文件只保存在用户本地，不属于 Release 内容。

## 数据位置

默认情况下，缓存和设置保存在应用程序所在目录的 `data` 文件夹内，图片保存在同级 `picture` 文件夹内。升级时请保留自己的设置与生成内容，并以新版本自带缓存为基础运行。

## 作者

- [Bilibili 主页](https://space.bilibili.com/361655499)
- [Taffy Wiki](https://acetaffy.org/)
