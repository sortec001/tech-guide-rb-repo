# TechGuide（RebornBuddy）分发库

RebornBuddy 版「技术攻略」编译产物分发仓库。

## 安装

1. 将 `TechGuideLoader` 放入 `RebornBuddy\Routines\TechGuideLoader\`
2. 将 `TechGuide.dll` 与 `Version.txt` 放入 `RebornBuddy\Routines\TechGuide\`（或首次由 Loader 自动下载）
3. 在 RebornBuddy 中选择战斗循环 **「技术攻略 PVE」**（Loader 入口，勿直接选 TechGuide.dll）

## 自动更新

Loader 启动时经代理拉取本仓库 `version.json`，若有新版本则下载 `release/TechGuide/latest.zip` 覆盖 DLL。

关闭自动更新：基础设置取消「自动更新」，或在 `Routines\TechGuide\` 放置空文件 `auto-update.off`。

## 仓库内容

| 路径 | 说明 |
|------|------|
| `version.json` | 版本号、更新说明、下载地址 |
| `release/TechGuide/latest.zip` | `TechGuide.dll` + `Version.txt` |

## 免责

仅供学习研究，请遵守当地法律法规与游戏用户协议。
