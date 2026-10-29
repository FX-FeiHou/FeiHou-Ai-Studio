<p align="center"><img src="assets/banner.webp" alt="花果山AI灵境坊" width="100%"></p>

# FeiHou-Ai-Studio

花果山AI灵境坊 Windows 客户端的安装包、更新包、版本清单与说明。当前版本：**`2.2.8`**

## 📥 下载完整安装包（2.2.8）

三个地址是同一个文件，任选一个能下载的即可：

- 🐙 [GitHub 下载](https://github.com/FX-FeiHou/FeiHou-Ai-Studio/releases/download/v2.2.8/FeiHou-Windows-2.2.8-full.zip)
- ☁️ [Cloudflare R2 下载](https://img.fei-hou.net/lingjing-updates/windows/full/FeiHou-Windows-2.2.8-full.zip)
- 🚀 [香港服务器下载](https://auth.fei-hou.net/updates/windows/full/FeiHou-Windows-2.2.8-full.zip)

文件名 `FeiHou-Windows-2.2.8-full.zip`，约 38 MiB，SHA-256：`b61ecf8bea0426d87cd529115638c6c1ec8abd952bb4960a6bd000bc7a5e8198`

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
- 也可以从 [Releases](https://github.com/FX-FeiHou/FeiHou-Ai-Studio/releases/latest) 下载 `FeiHou-Windows-2.2.8-update.zip`，在启动器更新面板中选择本地更新包安装。更新包不能作为独立安装包运行，也不要手动解压到程序目录。
- 更新会保留 API 配置、模型列表、画布、素材和生成结果。安装后请完全退出客户端（含托盘）再重新打开。

## 2.2.1 ～ 2.2.8 更新内容

- **修复客户端内充值看不到支付页**：点「支付宝支付」后支付宝收款码直接显示在充值框里，也可以点「在浏览器中打开」付款；之前没显示出来的订单都没有付款。（2.2.8）
- 窗口最大化后，右上角按钮显示「向下还原」图标；本地 H3 模型设置保存到本机，更新后不用重新设置；注册按 API 站规则提示（用户名不超过 20 位、密码 8～20 位）；制作包里 audio_files 的音色参考也能导入；切回影视工坊自动刷新项目列表。（2.2.8）
- **修复登录后出图全部失败、报「invalid or disabled API token」**：每台电脑自动使用自己的专用 API Key「花果山画布-本机编号」，不再借用账号里其他工具（如 WorkBuddy）的 Key。更新后请退出账号、重新登录一次。（2.2.7）
- 窗口右上角的「日志」按钮在所有界面都能打开生成日志；API Key 失效时报错里会提示处理办法。（2.2.6）
- 修复客户端注册时部分用户一直提示验证码错误或已过期的问题。（2.2.5）
- 影视工坊上传图片后列表不再跳回顶部，输入提示词时不再丢光标。（2.2.4）
- 自带的「全自动影视」技能升级到 1.7.1、「数字人 H3 / Seedance」技能升级到 1.5.1。（2.2.3）
- 修复画布用久了频繁卡死、无响应的问题。（2.2.2）
- 修复画布里点「充值」后提示「你还未配置支付接口商户！」的问题。（2.2.1）

2.2.0 及更早的更新内容见 [Releases](https://github.com/FX-FeiHou/FeiHou-Ai-Studio/releases)。

## 安全

此仓库不存放个人 API Key、用户素材、运行缓存或更新签名私钥。
