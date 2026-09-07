# 星空保卫战 · Space Shooter

> 单文件 HTML 太空射击游戏 · 致敬《雷电 2》

![glances](https://img.shields.io/badge/HTML5-single--file-orange) ![glances](https://img.shields.io/badge/no--deps-zero-blue) ![glances](https://img.shields.io/badge/license-MIT-green)

## 🎮 在线试玩

**[👉 点击这里开始游戏](https://zhangw51.github.io/space-shooter/)**

> 由 GitHub Pages 提供托管,无需下载,直接打开浏览器就能玩。

## 🕹️ 操作

| 操作 | 按键 |
|---|---|
| 移动 | `← → ↑ ↓` / `W A S D` |
| 射击 | `空格` / `J` / 鼠标/触屏按住 |
| 炸弹清屏 | `X` / `B` |
| 暂停 | `P` / `Esc` |
| 静音 | `M` |

> 💡 手机/平板:用手指拖动飞船即可,自动开火。

## ⚔️ 武器 & 道具

- **V 散弹** — 红色火神炮,扇形弹幕,可升级到 Lv8(最多 9 发)
- **L 激光** — 蓝色贯穿光束,等级越高越粗越伤
- **T 跟踪激光** — 紫色弧线光束,锁定敌机后越绷越直
- **B 炸弹** — 清屏 + 敌弹清空(最多 7 枚)
- **S 护盾** — 抵消一次伤害
- **♥ 生命** — 上限 5

## 🌊 波次

- 共无限波,每 5 波刷新一个 BOSS
- 击败 BOSS 一次性掉 2 个道具
- 最高分自动存 localStorage

## 📁 文件结构

```
space-shooter/
├── index.html      # 游戏主体(单文件,无外部依赖)
└── README.md
```

## 🛠️ 本地运行

直接双击 `index.html` 用浏览器打开即可,无需任何构建步骤。

## 📜 License

MIT
