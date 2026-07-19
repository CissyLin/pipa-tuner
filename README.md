# 🎵 琵琶练琴伴侣 — Pipa Practice Companion

🥚 蛋蛋 & Cissy 联合出品 · v2.0

琵琶调音器 + 节拍器，纯前端 Web 应用，支持 PWA 安装。

## 📱 功能

### 🎯 调音器
- 标准定弦：**A₂ — D₃ — E₃ — A₃**
- 实时麦克风音高检测 + 扇形偏差表盘
- 参考音播放

### 🥁 节拍器
- BPM 范围 40-208
- 可调拍号（1-16 拍，单位拍可选）
- 三态节拍点：重音 / 轻音 / 休止
- 打拍测速
- 🚀 跟练模式（阶梯上升 / 起伏练习 / 挑战模式）
- 📋 自定义预设（4 个默认：轮指/弹挑/扫弦/快速）
- 📊 练习日志（自动记录 / 连续天数 / 一键恢复）

### 🎨 主题
- 深蓝 / 木纹 / 紫兰迪 三种配色

## 📂 文件说明

| 文件 | 用途 |
|------|------|
| `index.html` | 主应用（v2.0） |
| `usage-guide.html` | 使用指南 |
| `manifest.json` | PWA 配置 |
| `sw.js` | Service Worker |
| `icon.svg` / `icon-192.png` / `icon-512.png` | 应用图标 |
| `vercel.json` | Vercel 部署配置 |
| `server.js` | 本地开发服务器 |
| `README.md` | 本文件 |

## 🚀 本地运行

```bash
node server.js
# 访问 http://localhost:8765
```

## 🌐 在线访问

GitHub Pages: https://cissylin.github.io/pipa-tuner/
