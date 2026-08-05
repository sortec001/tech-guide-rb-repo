# TechGuide（RebornBuddy）分发库

RebornBuddy 版「技术攻略」编译产物分发仓库。

## 安装

1. 将 `TechGuideLoader` 放入 `RebornBuddy\Routines\TechGuideLoader\`
2. 将 `TechGuide.dll` 与 `Version.txt` 放入 `RebornBuddy\Routines\TechGuide\`
3. 在 RebornBuddy 中选择战斗循环 **「技术攻略 PVE」**（Loader 入口，勿直接选 TechGuide.dll）

## 手动更新

打开职业/基础设置 → **「检查更新」**：从本仓库拉取 `version.json`，如有新版本则下载 `release/TechGuide/latest.zip` 覆盖本地 DLL。

下载需可访问 GitHub（建议本地代理 `127.0.0.1:7897`）。更新后请**重选战斗循环或重启 RebornBuddy** 生效。

## 仓库内容

| 路径 | 说明 |
|------|------|
| `version.json` | 版本号、更新说明、下载地址 |
| `release/TechGuide/latest.zip` | `TechGuide.dll` + `Version.txt` |

## 免责

仅供学习研究，请遵守当地法律法规与游戏用户协议。
