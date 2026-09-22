**目录：**

- [中文版](README.md)
- [英文版](README.en.md)
- [日文版](README.ja.md)

# HANDHELD MATRIX V3.0

8 款主流掌机的多维对比仪表盘：搜索、筛选、打分、雷达图对比，帮你挑出最适合自己的游戏掌机。

![HANDHELD MATRIX 仪表盘](./docs/screenshot.png)

🔗 **在线使用**：[keng0nion.github.io/HANDHELD-MATRIX-V3.0](https://keng0nion.github.io/HANDHELD-MATRIX-V3.0/)

---

## 功能

- **设备卡片**：8 款掌机的价格、续航、重量、屏幕、硬件参数一览，附性能 / 续航 / 屏幕三维评分条
- **MATRIX 选择台**：按名称 / 品牌 / 别名 / CPU 模糊搜索（Fuse.js），价格与重量双滑块筛选，一键预设指令（性能狂、纯主机、OLED ONLY、120Hz+、<500g、<¥1500）
- **MATRIX COMPARE**：勾选多台设备进入对比面板，雷达图（Chart.js）+ 参数对比表 + TOGGLE DIFF 差异高亮
- **导出海报**：html2canvas 一键把当前视图导出为图片
- **深色 / 浅色主题切换**，HUD 时钟与系统状态装饰

---

## 收录设备

| 设备 | 品牌 | 类别 | 价格 |
|---|---|---|---|
| Steam Deck OLED | Valve | PC 掌机 | ¥4,200 |
| ROG Ally X | ASUS | PC 掌机 | ¥5,800 |
| Legion Go 2 | Lenovo | PC 掌机 | ¥5,800 |
| AYANEO 2S | AYANEO | PC 掌机 | ¥5,500 |
| GPD WIN 4 (2025) | GPD | PC 掌机 | ¥5,300 |
| Switch OLED | Nintendo | 主机 | ¥2,200 |
| Miyoo Mini Plus | Miyoo | 复古掌机 | ¥400 |
| Retroid Pocket 4 Pro | Retroid | 复古掌机 | ¥1,300 |

价格与参数以 `devices.json` 数据为准（人民币计价）。

---

## 本地运行

纯静态单页：clone 后直接双击打开 `index.html`，或用任意静态服务器托管整个目录。

- `index.html` — 页面与全部逻辑
- `devices.json` — 掌机参数数据

外部 CDN 依赖（Fuse.js、Chart.js、nouislider、html2canvas、Lucide、vanilla-tilt），首次打开需联网。

---

## License

[MIT](./LICENSE)
