# TDKit — Terminal Development Kit

**Author:** nyu3321225  
**GitHub:** https://github.com/nyu3321225  
**Version:** v1.0.0-beta  
**License:** MIT  

## English

### Introduction
TDKit is a lightweight CLI tool for Android Termux. It provides environment checking, tool installation, storage monitoring, IP lookup, and project scaffolding in a single script.

### Features
- Environment check for 22 development tools
- Category-based tool installer
- Storage usage display
- Public IP address lookup
- Project skeleton creation (Python, Node.js, Generic)

### Installation

bash
wget https://raw.githubusercontent.com/nyu3321225/tdkit-beta/main/tdkit/tdkit 

cp tdkit /data/data/com.termux/files/usr/bin/tdkit

chmod +x /data/data/com.termux/files/usr/bin/tdkit

tdkit

### Usage
Run `tdkit` for interactive menu.  
`tdkit -e` for environment check.  
`tdkit -i` for install mode.

### Uninstall
bash

rm /data/data/com.termux/files/usr/bin/tdkit

---

## 中文

### 简介
TDKit 是一款专为 Android Termux 设计的轻量级 CLI 工具，集环境检测、工具安装、存储监控、IP查询、项目骨架创建于一体。

### 功能
- 检测 22 种开发工具
- 按分类安装工具
- 显示存储使用情况
- 获取公网 IP 地址
- 创建项目骨架（Python、Node.js、通用）

### 安装
bash

wget https://raw.githubusercontent.com/nyu3321225/tdkit-beta/main/tdkit/tdkit 

cp tdkit /data/data/com.termux/files/usr/bin/tdkit

chmod +x /data/data/com.termux/files/usr/bin/tdkit

tdkit

### 使用
运行 `tdkit` 进入交互菜单。  
`tdkit -e` 直接检查环境。  
`tdkit -i` 直接安装工具。

### 卸载
bash

rm /data/data/com.termux/files/usr/bin/tdkit

---

## License / 许可证
MIT License — Copyright (c) 2026 nyu3321225

---


---

## Upcoming Patch Notice

**v1.0.1-beta** — Estimated release: Next Mon–Tue (subject to change)

### What's Changed

| Area | v1.0.0-beta | v1.0.1-beta |
|------|-------------|-------------|
| Language | Chinese only | Chinese / English toggle |
| First launch | No prompt | User agreement (Yes / No) |
| Menu display | Duplicate numbering | Fixed |
| Tool detection | Errors on no --version | Graceful fallback |
| Stability | Baseline | Improved |

### Why the delay?

Not abandoned. Just one person working on it.  
Testing takes time, especially when you're the only tester.  
Better late than broken.

### Status

Minor patch. No breaking changes.  
Timeline is tentative.

---

## 更新预告

**v1.0.1-beta** — 预计发布时间：下周周一至周二（可能变动）

### 更新对比

| 模块 | v1.0.0-beta | v1.0.1-beta |
|------|-------------|-------------|
| 语言 | 仅中文 | 中英双语切换 |
| 首次启动 | 无提示 | 用户协议确认（Yes / No） |
| 菜单显示 | 编号重复 | 已修复 |
| 工具检测 | 无版本号时报错 | 降级处理 |
| 稳定性 | 基础 | 优化 |

### 为什么拖这么久？

没鸽。只是一个人在做。  
测试需要时间，尤其是当你只有一个测试员的时候。  
晚点发，也比发个坏的强。

### 状态说明

小幅补丁更新，不涉及破坏性变更。  
发布时间为暂定。

— Maintainer

---

## Pre-release Surprise / 提前更新惊喜 🎉

**v1.0.1-beta** has been pushed ahead of schedule!

### What's New / 新增内容

| Category | Item | Status |
|----------|------|--------|
| 🌐 Language | Bilingual menu (Chinese / English) | ✅ Done |
| 📜 Agreement | User agreement prompt (Yes / No) | ✅ Done |
| 🌍 Network | Internal IP detection (fallback methods) | ✅ Done |
| 💡 Advice | Smart install suggestions | ✅ Done |
| 🔧 Fix | Duplicate menu numbering | ✅ Done |
| 🔧 Fix | Tool detection graceful fallback | ✅ Done |

### Known Bug / 已知问题

| Bug | Description | Fix ETA |
|-----|-------------|---------|
| 🔄 Init loop | User agreement & language selection repeats on every launch | Next patch (Mon) |

The initialization prompt currently runs every time you start TDKit.  
A detection mechanism will be added soon to remember your previous choice.

初始化选择目前每次启动都会重复。  
将在下个补丁中加入记忆功能，不再重复询问。

---

### 更新对比

| 模块 | v1.0.0-beta | v1.0.1-beta |
|------|-------------|-------------|
| 语言 | 仅中文 | 中英双语切换 |
| 首次启动 | 无提示 | 用户协议确认 (Yes/No) |
| 菜单显示 | 编号重复 | 已修复 |
| 工具检测 | 无版本号时报错 | 降级处理 |
| 内网 IP | 不支持 | 支持 (多种方式) |
| 智能建议 | 不支持 | 支持 |
| 初始化流程 | 直接进菜单 | 每次询问协议+语言 ⚠️ |

### Coming in next patch / 下个补丁预告

- Fix: initialization loop (remember user choice)
- Stability improvements

— Maintainer
