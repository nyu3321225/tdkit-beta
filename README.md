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

## Upcoming Patch Notice

**v1.0.1-beta** — Estimated release: Next Mon–Tue (subject to change)

### Planned Changes

- Bilingual menu (Chinese / English selection on startup)
- User agreement prompt (Yes / No) on first launch
- Fix: duplicate menu numbering in `select`
- Fix: improved fallback for tools without `--version`
- General stability improvements

### Status

This is a minor patch update. No breaking changes expected.  
Release timeline is tentative and may shift depending on testing results.

---

## 更新预告

**v1.0.1-beta** — 预计发布时间：下周周一至周二（可能变动）

### 计划更新内容

- 中英双语菜单（启动时选择语言）
- 首次启动时用户协议确认（Yes / No）
- 修复：`select` 菜单编号重复问题
- 修复：对不支持 `--version` 的工具做降级处理
- 稳定性优化

### 状态说明

本次为小幅补丁更新，不涉及破坏性变更。  
发布时间为暂定，可能根据测试结果调整。

— Maintainer
