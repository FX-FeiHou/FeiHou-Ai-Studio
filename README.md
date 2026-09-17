# FeiHou-Ai-Studio



本仓库发布花果山AI灵境坊 Windows 与 macOS 客户端的安装包、版本清单与说明。



## 客户端下载



- [GitHub 下载](https://github.com/FX-FeiHou/FeiHou-Ai-Studio/releases/download/v1.6.6/FeiHou-Ai-Studio-Win-1.6.6-full.zip)

- [夸克网盘下载](https://pan.quark.cn/s/327190b9484c)



## 首次安装



打开 [完整安装包发布页](https://github.com/FX-FeiHou/FeiHou-Ai-Studio/releases/tag/v1.6.6)，选择 `FeiHou-Ai-Studio-Win-1.6.6-full.zip`（约 35 MiB）。完整解压后双击“花果山AI灵境坊.exe”，保留同目录的 app 文件夹。已包含 Windows Python 环境和在线更新配置，API Key 需自行填写。



GitHub 自动生成的 Source code ZIP/TAR 是发布说明仓库，不是客户端。



## 获取更新



从 [Releases](https://github.com/FX-FeiHou/FeiHou-Ai-Studio/releases/latest) 下载发布文件。



- 已接通在线更新的客户端：打开启动器的更新面板，检查更新、下载并安装。可以自动选择线路，也可手动选择 GitHub 或 Cloudflare R2。

- 尚未配置在线更新的 1.1.0–1.1.3 客户端：下载 `FeiHou-Windows-1.6.6-update.zip`，在启动器更新面板中选择本地更新包并安装。此次安装后即可接收后续在线更新。

- 更新包适用于已有完整程序文件夹的 Windows 客户端，不能作为独立安装包运行；不要手动解压到程序目录。

- 安装前完成或停止正在运行的生成任务；安装时客户端需要关闭并重启。

- 更新替换程序文件，保留 API 配置、模型列表、画布、素材和生成结果。为重要作品保留独立备份。





## macOS 版

macOS 13 及以上（Apple Silicon 与 Intel 通用）到 [macOS 完整包发布页](https://github.com/FX-FeiHou/FeiHou-Ai-Studio/releases/tag/mac-v1.6.6) 下载 `FeiHou-Mac-Universal-1.6.6.zip`（约 79 MiB），完整解压后双击「花果山AI灵境坊.app」。包里已含 arm64 与 Intel 两套 Python 环境，启动器按当前芯片自动选择。

macOS 版标记为 **pre-release**，不出现在 `releases/latest`，也不影响 Windows 客户端的更新线路。它使用独立的 macOS 更新清单（`lingjing-updates/mac/stable/update.json`）；程序内「检查更新」只提示新版本并打开下载页，**不自动安装**。换版本时退出程序后整体替换 app 文件夹与 .app 即可，个人配置与作品保留在 app 内。

本包未做 Apple 开发者签名与公证，首次打开可能需要在「系统设置 → 隐私与安全性」中选择「仍要打开」。

## 安全



此仓库不存放个人 API Key、用户素材、运行缓存或更新签名私钥。更新包中的业务程序文件是客户端运行所需内容。
