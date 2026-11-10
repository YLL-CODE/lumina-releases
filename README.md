# Lumina

Lumina（原「绘意」）是对话式 AI 图片创作桌面工具。本仓库仅提供发布说明、软件包与校验文件；应用保持闭源，未授予开源许可。

## 下载

[前往 Releases 下载 Windows x64 测试版](https://github.com/YLL-CODE/lumina-releases/releases)

下载 Lumina-版本号-win-x64.zip，完整解压后运行 Lumina.exe。不要只复制 exe，也不要直接在压缩包中运行。GitHub 自动提供的 Source code 压缩包仅包含本说明仓库，不是应用安装包或应用源码。

## 首次使用

真实 AI 需要联网和服务商额度。在首页或「设置 → 服务商与模型」导入维护者私下提供的 .lumina-config（兼容 .huiyi-config），查看摘要后确认。软件包不含密钥。配置文件包含服务凭据，请勿上传到本仓库、公开转发或附在问题反馈中。

## 升级与数据

先等待任务结束，在「设置 → 工作区」创建完整备份，正常退出旧版。把新版解压到新文件夹后运行；同一 Windows 用户继续使用 %APPDATA%\HuiyiStudio 中的会话、作品和配置。不要同时运行两份版本。普通作品备份不含密钥，换电脑需重新导入配置。

旧版指向原发布仓库，必须从本页手动下载新版一次。新版「设置 → 关于与更新」使用此仓库查询，更新仍需手动下载、解压和启动，没有自动安装功能。

## 测试范围

当前提供 Windows x64 预览版，目标基线为 Windows 10 22H2。0.2.8-preview.2 尚未完成 Windows 实机验收，未进行代码签名。请阅读每个发行版的已验证项目和限制，并保留备份；旧版本的测试结果不代表新版本已验收。

每个发行版附 SHA256SUMS.txt 和 huiyi-release.json（兼容性保留的更新协议文件名）。可用 PowerShell Get-FileHash -Algorithm SHA256 核对 ZIP。

反馈请附版本号、系统版本、错误提示和复现步骤，并去除密钥及私人图片。
