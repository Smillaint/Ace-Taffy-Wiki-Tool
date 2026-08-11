# 安全说明

请只从本仓库 GitHub Releases 下载发布包，并在运行前对照 `SHA256SUMS.txt` 校验 ZIP 文件。

应用内更新还会验证 GitHub Release 资产 digest 与包内 `release_manifest.json` 的逐文件 SHA256；清单不一致、夹带用户数据或包含越界路径的更新包会被拒绝。

程序不会在 Release 中预置 API Key。请勿公开包含 `data/settings.ini`、`.env`、操作日志或个人生成内容的文件。

公开版使用 Nuitka standalone 构建，不随包发布 Python 源码。任何本地可执行程序仍可能被分析，因此不应把凭据或其他秘密硬编码进程序或缓存。
