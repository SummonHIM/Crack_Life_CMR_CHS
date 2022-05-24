# Crack_Life_CMR_CHS
Crack-Life: Campaign Mode Remake unofficial chinese support

半裂命：战役模式重置版非官方汉化

*半裂命包含许多暴力粗口，若感到不适请尽快离开。*

原作者：Mr Binka

# Downloads
- [原生 GitHub 下载](https://github.com/SummonHIM/Crack_Life_CMR_CHS/archive/master.zip)
- [GHProxy 大陆加速下载](https://ghproxy.com/https://github.com/SummonHIM/Crack_Life_CMR_CHS/archive/master.zip)
- 游戏下载网址：[点击此处](https://www.moddb.com/mods/crack-life-campaign-mode-remake)

# How to ues?
1. 点击[下载](#downloads)按钮，下载汉化文件。
2. 将 `cracklifecmr` 文件夹全部拷贝进游戏目录里。
3. 打开并登陆 Steam，确保其语言为中文。
4. 运行游戏。

# Feature
- 菜单汉化（大部分来源于 Source 引擎中的官方汉化）
- 游戏内标题汉化
- 字幕汉化（全字幕 + 部分语音效果）

# Map Changelog
- lvl2: 在通用环境实体 `worldssmallestcup` 旁增加命令实体 `worldssmallestcup_subtitle` 并用逻辑中继实体 `triggercup` 执行 `cc_emit #newsounds/worldssmallestcup.wav` 命令。[（Bug 详情）](https://developer.valvesoftware.com/wiki/Closed_Captions:zh-cn#.E5.9C.A8.E4.BD.A0.E7.9A.84.E5.9C.B0.E5.9B.BE.E9.87.8C.E6.92.AD.E6.94.BE.E5.B8.A6.E6.9C.89.E5.AD.97.E5.B9.95.E7.9A.84.E9.9F.B3.E9.A2.91)
- lvl7a: 在通用环境实体 `daddyspeak` 旁增加命令实体 `daddyspeak_subtitle` 并用逻辑中继实体 `break_mm` 执行 `cc_emit #newsounds/vendingmachine.wav` 命令。[（Bug 详情）](https://developer.valvesoftware.com/wiki/Closed_Captions:zh-cn#.E5.9C.A8.E4.BD.A0.E7.9A.84.E5.9C.B0.E5.9B.BE.E9.87.8C.E6.92.AD.E6.94.BE.E5.B8.A6.E6.9C.89.E5.AD.97.E5.B9.95.E7.9A.84.E9.9F.B3.E9.A2.91)
- lvl10: 在逻辑编排场景实体 `comdevice_murica3` 旁增加命令实体 `comdevice_murica_subtitle` 并用 7 种触发式实体与 1 种按钮式实体执行 `cc_emit` 命令。
- lvl11: 在逻辑编排场景实体 `comdevice_lvl11_2` 旁增加命令实体 `comdevice_lvl11_subtitle` 并用 2 种触发式实体执行 `cc_emit` 命令。
- lvl21: 在逻辑编排场景实体 `comdevice_3_lvl21` 旁增加命令实体 `cmd_cc_emit` 并用 3 种触发式实体执行 `cc_emit` 命令。
- lvl22: 在逻辑中继实体 `turret_trap_mm` 旁增加命令实体 `cmd_cc_emit` 并用 3 种触发式实体执行 `cc_emit` 命令。
- lvl22: 在门实体 `final_door1` 上方增加命令实体 `cmd_cc_emit` 并用 2 种触发式实体执行 `cc_emit` 命令。
- creditscmr: 在逻辑中继实体 `credits_titles_mm` 旁增加命令实体 `cmd_cc_emit` 并用逻辑中继实体 `credits_titles_mm` 执行 `cc_emit` 命令。

# Other
汉化的并不太好，请求大佬们指点。欢迎Pull requests/Issues
