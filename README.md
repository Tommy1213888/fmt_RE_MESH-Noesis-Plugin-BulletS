# fmt_RE_MESH-Noesis-Plugin

> RE Engine 模型/贴图/动画 Noesis 导入导出插件（个人修改版）

⚠️ **学习自用，请勿售卖或商用，风险自负**

📖 [Wiki 文档](https://github.com/AniBullet/fmt_RE_MESH-Noesis-Plugin-BulletS/wiki) ｜ 🔧 [BsKeyTools 远端脚本](https://github.com/AniBullet/BsKeyTools)

---

## 支持游戏

| 游戏 | Mesh | Tex | Motlist |
|------|:----:|:---:|:------:|
| Resident Evil 7 | ✅ | ✅ | ✅ |
| Resident Evil 2 Remake | ✅ | ✅ | ✅ |
| Resident Evil 3 Remake | ✅ | ✅ | ✅ |
| Resident Evil 4 Remake | ✅ | ✅ | ✅ |
| Resident Evil 8 (Village) | ✅ | ✅ | ✅ |
| Resident Evil 9 | ✅ | ✅ | ✅ |
| Resident Evil ReVerse | ✅ | ✅ | ✅ |
| Devil May Cry 5 | ✅ | ✅ | ✅ |
| Monster Hunter Rise / Sunbreak | ✅ | ✅ | ✅ |
| Monster Hunter Wilds | ✅ | ✅ | ✅ |
| Monster Hunter Stories 3 | ✅ | ✅ | ✅ |
| Street Fighter 6 | ✅ | ✅ | ✅ |
| Dragon's Dogma 2 | ✅ | ✅ | ✅ |
| Dead Rising Deluxe Remaster | ✅ | ✅ | ✅ |
| ExoPrimal | ✅ | ✅ | ✅ |
| Apollo Justice: Ace Attorney Trilogy | ✅ | ✅ | ✅ |
| **Onimusha: Way of the Sword** | ✅ | ✅ | ✅ |
| Pragmata | ✅ | ✅ | ✅ |

## 安装

1. 下载 [Noesis](https://www.richwhitehouse.com/index.php?content=inc_projects.php&showproject=91)
2. 将 `fmt_RE_Motion_Rel.py` 放入 `[Noesis]/plugins/python/` 目录
3. 重启 Noesis

## 使用说明

- 支持 `.mesh` / `.tex` / `.motlist` 文件的导入导出
- 导入 motlist 时弹出选择窗口，可选择加载指定 clip 或全部
- `Tools > RE Engine > Auto Load All Motions` 切换自动加载全部动画
- 设置 `bAutoLoadMotions = True` 永久跳过弹窗
- 命令行传入 `-noprompt` 或 `-b` 跳过弹窗，适配批量调用
- `-fbxmultitake` 参数可分离多动画轨道导出

## 相关链接

- [REEM 使用指南](https://residentevilmodding.boards.net/thread/15374/noesis-maxscript-custom-physics-guide)
- [插件详细说明](https://residentevilmodding.boards.net/thread/13501/exporting-custom-models-dmc5-noesis)

## 致谢

- [alphazolam](https://github.com/alphazolam/fmt_RE_MESH-Noesis-Plugin) — 原仓库作者
- [Gh0stblade](https://github.com/Gh0stblade) — 初版插件作者
- [RE-Engine-Lib](https://github.com/kagenocookie/RE-Engine-Lib) — 格式参考

## 反馈

问题反馈请提交 [Issue](../../issues) 或加入 [Modding Haven](https://discord.gg/acCRqRyUB2)
