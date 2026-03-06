<img width="2502" height="1290" alt="image" src="https://github.com/user-attachments/assets/a92f9292-d95d-4d03-8ee0-dac9f8d16d6d" />
﻿---

## English

### Introduction

Earth Ripples is an interactive historical map website that visualizes global political boundaries over time.  
It allows users to explore from 3000 BCE to 2000 CE and observe how civilizations, dynasties, empires, and modern states changed geographically.

URL: www.earthripples.com

Run locally for a smoother experience.

### Key Features

- Timeline navigation with year-based controls
- Dynamic historical boundary rendering by year
- Search and locate specific polities
- Detail panel for polity period and related links
- Toggleable historical event markers
- Bilingual UI (Chinese / English)
- Responsive layout for desktop and mobile

### Data Coverage (Verified)

- Time range: `-3000` to `2000`
- Chunk span: `25` years
- Total chunks: `218`
- Total polities: `1522`

### Run Locally

This repository is a prebuilt static site (`index.html + assets + data`). No build step is required.

1. Open the project directory
2. Start a local static server (choose one)

```bash
# Python 3
python -m http.server 8000
```

```bash
# Node.js
npx serve .
```

```bash
# PHP
php -S localhost:8000
```

3. Open:

```text
http://localhost:8000
```

### License

This project is licensed under the GNU General Public License v3.0 (GPL-3.0). See the `LICENSE` file for details.

---
# Earth Ripples - Interactive Historical Map

[中文](#中文) | [English](#english)

---

## 中文

### 项目简介

Earth Ripples 是一个可交互的历史地图网站，用时间轴展示全球政权边界在不同时期的变化。  
用户可以从公元前 3000 年浏览到公元 2000 年，查看文明、王朝、帝国和现代国家的空间演变。

网站链接: www.earthripples.com

本地运行获得更流畅的体验。

### 主要特性

- 时间轴浏览：支持按年跳转和连续拖动
- 动态地图：按年份加载对应历史边界
- 政权检索：可搜索并定位具体政权
- 详情面板：展示政权名称、存续时间和相关链接
- 历史事件标记：支持显示/隐藏
- 双语界面：支持中文与英文切换
- 移动端适配：桌面和移动端均可访问

### 数据覆盖（已核验）

- 时间范围：`-3000` 到 `2000`
- 时间分块：每 `25` 年 1 个 chunk
- 分块总数：`218`
- 政权总数：`1522`

### 本地运行

这是一个已构建完成的静态站点（`index.html + assets + data`），无需 `npm install`。

1. 进入项目目录
2. 启动本地静态服务器（任选一种）

```bash
# Python 3
python -m http.server 8000
```

```bash
# Node.js
npx serve .
```

```bash
# PHP
php -S localhost:8000
```

3. 打开浏览器访问：

```text
http://localhost:8000
```

### 项目结构

```text
earthripples/
├─ index.html
├─ logo.svg
├─ assets/
├─ data/
│  ├─ polity_index.json
│  └─ chunks/
│     ├─ chunks_index.json
│     └─ chunk_*.json
├─ LICENSE
└─ README.md
```

### 许可证

本项目采用 GNU General Public License v3.0（GPL-3.0）开源。详见 `LICENSE` 文件。
