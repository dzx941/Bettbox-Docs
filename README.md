# 📦 Bettbox-Docs

> **Bettbox (原名 LiClash)** 官方多语言使用指南 —— 现代化的 Android 代理工具文档。

[![Docsify](https://img.shields.io/badge/Powered%20by-Docsify-42b983?style=flat-square&logo=docsify)](https://docsify.js.org/)
[![License: MIT](https://img.shields.io/badge/Code_License-MIT-blue.svg?style=flat-square)](LICENSE)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/Content_License-CC%20BY--NC--SA%204.0-lightgrey.svg?style=flat-square)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![I18n](https://img.shields.io/badge/Language-CN%20%7C%20EN-orange?style=flat-square)](#-多语言支持--i18n-support)

---

## 🌐 访问地址 (Live Demo)

👉 **[点击进入 Bettbox 官方文档](https://bettbox.dpdns.org)** *(由 Cloudflare + GitHub Pages 强力驱动)*

---

## ✨ 项目特性

* **多语言支持**：原生中/英文切换，支持多语言路由别名。
* **现代视觉**：支持 **Material You** 风格，随系统自动切换 **深色/浅色模式**。
* **流畅体验**：GitHub 图标与 UI 组件完美适配暗黑模式，提供平滑的过渡动画。
* **极致性能**：基于 Docsify 构建，无需预编译，静态托管，访问极速。
* **CDN 加速**：核心资源通过 GCore (jsDelivr) 加速，确保全球范围内稳定访问。

---
## 🚀 本地预览 (Local Development)

如果你想在本地修改并实时预览文档效果，请按照以下步骤操作：

### 1. 安装环境
确保你的电脑已安装 [Node.js](https://nodejs.org/)。

### 2. 克隆仓库
```bash
git clone [https://github.com/dzx941/Bettbox-Docs.git](https://github.com/dzx941/Bettbox-Docs.git)
cd Bettbox-Docs
```
### 3. 安装工具
在终端执行以下命令安装 Docsify CLI：
```
npm i docsify-cli -g
 ```
### 4. 预览文档
运行预览服务：
```
docsify serve .
```
打开浏览器访问：http://localhost:3000 修改 .md 文件后页面将 **自动实时刷新。**
## 📂 目录结构

```text
.
├── index.html          # 文档入口与核心配置 (多语言/暗黑模式逻辑)
├── _sidebar.md         # 中文侧边栏
├── README.md           # 中文首页 (当前文件即仓库介绍)
├── getting-started.md  # 中文快速开始
├── en/                 # 英文文档根目录
│   ├── _sidebar.md     # 英文侧边栏
│   ├── README.md       # 英文首页
│   └── ...             # 其他英文文档
└── guide/              # 功能指南目录 (中/英子目录)
```
---

## 📜 许可协议 (License)
本项目采用双重许可协议保护：

代码部分（包含 index.html 逻辑与 CSS 样式）采用 [MIT License](LICENSE) 许可。

文档内容（包含所有 .md 格式的文字与图片说明）采用 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh-hans) 许可。
