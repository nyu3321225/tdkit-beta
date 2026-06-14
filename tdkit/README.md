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
