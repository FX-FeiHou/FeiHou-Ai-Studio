<p align="center"><img src="assets/banner.webp" alt="花果山AI灵境坊" width="100%"></p>

# FeiHou-Ai-Studio

花果山AI灵境坊 Windows 客户端的安装包、更新包、版本清单与说明。当前版本：**`2.1.15`**

## 📥 下载完整安装包（2.1.15）

三个地址是同一个文件，任选一个能下载的即可：

- 🐙 [GitHub 下载](https://github.com/FX-FeiHou/FeiHou-Ai-Studio/releases/download/v2.1.15/FeiHou-Windows-2.1.15-full.zip)
- ☁️ [Cloudflare R2 下载](https://img.fei-hou.net/lingjing-updates/windows/full/FeiHou-Windows-2.1.15-full.zip)
- 🚀 [香港服务器下载](https://auth.fei-hou.net/updates/windows/full/FeiHou-Windows-2.1.15-full.zip)

文件名 `FeiHou-Windows-2.1.15-full.zip`，约 38 MiB，SHA-256：`2942621096c650691f5c3de941d7edf60ef4d6d851379533ee3becd256cf0b5b`

> ⚠️ **2.1.0 以下的旧版本（如 1.6.7、1.x、2.0.0）建议直接下载上面的完整包，替换旧版客户端。** 步骤见下方「从旧版客户端换成新版」。

## 首次安装

1. 下载上面的完整包，**完整解压**到一个新文件夹（不要放在系统盘的 Program Files 等需要管理员权限的目录）。
2. 双击「花果山AI灵境坊.exe」启动，保留同目录的 `app` 文件夹。
3. 已包含 Windows Python 运行环境和在线更新配置，登录账号或填写 API Key 后即可使用。

GitHub 自动生成的 Source code ZIP/TAR 是发布说明仓库，不是客户端。

## 从旧版客户端换成新版（2.1.0 以下推荐）

1. 在旧客户端里完成或停止正在进行的生成任务，然后在托盘图标上右键退出（完全退出）。
2. 把新版完整包解压到一个新文件夹。
3. 把旧版客户端里的个人数据复制到新版相同位置（有提示是否替换时选「替换」）：
   - `app\data`（API 配置、画布、模型列表等）
   - `app\output`
   - `app\assets` 里的 `input`、`output`、`library`、`uploads`（素材与生成结果）
   - `app\workflows\custom`（如果有自定义工作流）
4. 双击新版的「花果山AI灵境坊.exe」启动，确认画布和作品都在之后，再删除旧版文件夹。

## 在线更新

- 1.1.4 及以上的客户端都可以在线更新：打开启动器的更新面板，检查更新、下载并安装，会自动选择 Cloudflare R2、香港服务器或 GitHub 线路。
- 也可以从 [Releases](https://github.com/FX-FeiHou/FeiHou-Ai-Studio/releases/latest) 下载 `FeiHou-Windows-2.1.15-update.zip`，在启动器更新面板中选择本地更新包安装。更新包不能作为独立安装包运行，也不要手动解压到程序目录。
- 更新会保留 API 配置、模型列表、画布、素材和生成结果。安装后请完全退出客户端（含托盘）再重新打开。

## 2.1.13 ～ 2.1.15 更新内容

- 修复从网上下载完整包、用 Windows 自带解压后，启动时报「未能加载 Microsoft.Web.WebView2.WinForms……不支持操作」无法打开的问题。（2.1.15）
- 修复本地 ComfyUI 生成 Easy H3 视频时，报「当前 ComfyUI 没有 xflow/gpt-5.5」导致无法生成的问题。（2.1.14）
- 修复 Google 登录出错、部分账号无法登录的问题。（2.1.13）

2.1.12 及更早的更新内容见 [Releases](https://github.com/FX-FeiHou/FeiHou-Ai-Studio/releases)。

## 安全

此仓库不存放个人 API Key、用户素材、运行缓存或更新签名私钥。
