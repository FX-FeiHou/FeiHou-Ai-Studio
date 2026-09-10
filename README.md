# 花果山AI灵境坊

本仓库仅发布 Windows 客户端更新包、版本清单与说明。

## 获取更新

从 [Releases](https://github.com/FX-FeiHou/feihou-ai-studio-releases/releases/latest) 下载发布文件。

- 已接通在线更新的客户端：打开启动器的更新面板，检查更新、下载并安装。可以自动选择线路，也可手动选择 GitHub 或 Cloudflare R2。
- 尚未配置在线更新的 1.1.0–1.1.3 客户端：下载 `FeiHou-Windows-1.1.4-update.zip`，在启动器更新面板中选择本地更新包并安装。此次安装后即可接收后续在线更新。
- 更新包适用于已有完整程序文件夹的 Windows 客户端，不能作为独立安装包运行；不要手动解压到程序目录。
- 安装前完成或停止正在运行的生成任务；安装时客户端需要关闭并重启。
- 更新替换程序文件，保留 API 配置、模型列表、画布、素材和生成结果。为重要作品保留独立备份。

## 下载线路

- GitHub Releases：官方发布文件。
- Cloudflare R2：`https://img.fei-hou.net/lingjing-updates/windows/` 下的同一签名更新包。

客户端下载后验证签名和 SHA-256，线路仅负责传输，不能绕过校验。R2 和 GitHub 的可达性取决于所在网络，不承诺固定下载速度。

## 安全

此仓库不存放个人 API Key、用户素材、运行缓存或更新签名私钥。更新包中的业务程序文件是客户端运行所需内容。
