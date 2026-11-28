<p align="center"><img src="assets/banner.webp" alt="花果山AI灵境坊" width="100%"></p>

# FeiHou-Ai-Studio

花果山AI灵境坊 Windows / macOS 客户端的安装包、更新包、版本清单与说明。当前版本：**`3.0.0`**

## 📥 下载完整安装包（3.0.0）

三个地址是同一个文件，任选一个能下载的即可：

- 🐙 [GitHub 下载](https://github.com/FX-FeiHou/FeiHou-Ai-Studio/releases/download/v3.0.0/FeiHou-Windows-3.0.0-full.zip)
- ☁️ [Cloudflare R2 下载](https://img.fei-hou.net/lingjing-updates/windows/full/FeiHou-Windows-3.0.0-full.zip)
- 🚀 [香港服务器下载](https://auth.fei-hou.net/updates/windows/full/FeiHou-Windows-3.0.0-full.zip)

文件名 `FeiHou-Windows-3.0.0-full.zip`，约 74 MiB，SHA-256：`fcd9ad08f5376d40cfad8e610cbe613399bb1ef95cdf21e29442f2a4dcf71cb2`

> ⚠️ **2.1.0 以下的旧版本（如 1.6.7、1.x、2.0.0）建议直接下载上面的完整包，替换旧版客户端。** 步骤见下方「从旧版客户端换成新版」。

## 🍎 macOS 客户端（3.2.0）

两个地址是同一个文件，任选一个能下载的即可：

- 🐙 [GitHub 下载](https://github.com/FX-FeiHou/FeiHou-Ai-Studio/releases/download/mac-v3.2.0/FeiHou-Mac-Universal-3.2.0.zip)
- ☁️ [Cloudflare R2 下载](https://img.fei-hou.net/lingjing-updates/mac/3.2.0/FeiHou-Mac-Universal-3.2.0.zip)

文件名 `FeiHou-Mac-Universal-3.2.0.zip`，约 119 MiB，SHA-256：`f0c7ce00535354ba13b48c6c2d0834ff980f038b5c7c00f5cad24aacfeea9e9c`

- macOS 13 或更高，Apple 芯片（M 系列）与 Intel 芯片通用；功能与 Windows 3.2.0 一致。
- 完整解压后双击「花果山AI灵境坊.app」，保留同目录的 `app` 文件夹；请放在「应用程序」或「文稿」等可写位置。
- 未做 Apple 开发者签名：首次打开被拦下时，到「系统设置 → 隐私与安全性」点「仍要打开」；提示「已损坏」时按包内「使用说明.txt」处理。
- **1.6.6 的旧 Mac 版不能直接升级**：退出程序后，用新包整体替换「花果山AI灵境坊.app」和 `app` 文件夹（先把旧版 `app/data`、`app/output`、`app/assets` 里的个人数据复制过去）。
- 3.2.0 起 Mac 版支持在线更新：工具栏「检查更新」→「立即更新」，只下载改动的部分。

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
- 也可以从 [Releases](https://github.com/FX-FeiHou/FeiHou-Ai-Studio/releases/latest) 下载 `FeiHou-Windows-3.0.0-update.zip`，在启动器更新面板中选择本地更新包安装。更新包不能作为独立安装包运行，也不要手动解压到程序目录。
- 更新会保留 API 配置、模型列表、画布、素材和生成结果。安装后请完全退出客户端（含托盘）再重新打开。

## 3.0.0 更新内容

- **全新首页**：顶部是 Agent 输入框，说需求就能新建画布开工；下面是创作灵感和全部技能。
- **画布 Agent 停靠右侧**：能建节点、选模型、设比例和时长、修改和删除节点、自动打组排版；可以添加自己的本地 Agent（OpenAI 兼容接口）。
- **技能与插件页**：电商组图、SKU 换色、KOC 种草、详情页、产品广告、电商海报等电商技能；小肥猴的 H3、舞蹈、数字人、MV 技能；以及上百个创作技能。
- **API 站功能在客户端里原生可用**：AI 工作室（视频导演、视频复刻、动作迁移、短剧、MV、舞台等）、AI 工具箱、音频、账号与充值、发现。
- **新模型**：MAGI-2（国内 / 海外版）；MiniMax H3 小肥猴 V8 版、小肥猴版人物替换 / 动作迁移（每次 ¥0.35）；H3 金鱼特调改名「特调版」。
- **模型菜单**：改成「品牌 | 模型」两栏并标出价格；图像模型按 OpenAI、Google、阿里、字节排序。
- **界面**：新标题栏、新启动图标；浅色主题底色加深；拖动窗口不再卡顿。
- **画布**：新节点自动打组且组框不会被撑破；点节点不再变形；组内节点更紧凑并显示连线；节点下的输入框缩放有上下限；右键「替换媒体」。
- **反馈**改用 API 站工单系统，提交后提示成功或失败，可以查看客服回复。

2.9.0 及更早的更新内容见 [Releases](https://github.com/FX-FeiHou/FeiHou-Ai-Studio/releases)。

## 安全

此仓库不存放个人 API Key、用户素材、运行缓存或更新签名私钥。
