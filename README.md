# TDKit — Terminal Development Kit

**Version:** v1.0.1-ui (Beta)  
**License:** MIT  
**Author:** nyu3321225  

---

## Overview

TDKit is a lightweight CLI toolkit for Android Termux.  
It helps developers quickly set up development environments, manage tools, monitor storage, check network info, and generate project scaffolds — all from a single terminal interface.

---

## Quick Install
bash

wget https://raw.githubusercontent.com/nyu3321225/tdkit-beta/main/src/tdkit 

cp tdkit /data/data/com.termux/files/usr/bin/tdkit

chmod +x /data/data/com.termux/files/usr/bin/tdkit

tdkit

---

## Features

| Category | Feature | Description |
|----------|---------|-------------|
| 🔍 Environment | Tool Detection | Check 22 development tools with version display |
| 📦 Installer | Category-Based | Install tools by category (Basic, Media, Terminal, Network, Dev) |
| 💾 Storage | Usage Monitor | Display internal storage and home directory usage |
| 🌐 Network | IP Lookup | Get public IP and internal IP (with fallback methods) |
| 🏗️ Scaffold | Project Generator | Create Python, Node.js, or Generic project skeletons |
| 📊 Report | Git Daily Report | Analyze today's commits in any local repository |
| 🌍 Language | Bilingual | Switch between Chinese and English on startup |
| 💡 Advice | Smart Suggestions | Auto-detect missing tools and suggest installation |

---

## Usage

| Command | Description |
|---------|-------------|
| `tdkit` | Launch interactive menu |
| `tdkit -e` | Direct environment check |
| `tdkit -i` | Direct install mode |

---

## Version Comparison

| Feature | v1.0.0-beta (Stable) | v1.0.1-ui (Beta) |
|---------|---------------------|-------------------|
| Language | Chinese only | Chinese / English toggle |
| First Launch | No prompt | User agreement (Yes/No) |
| Menu Display | Clean | Clean + colored UI |
| Tool Detection | Basic | With graceful fallback |
| Internal IP | Not supported | Supported (3 methods) |
| Smart Suggestions | Not supported | Supported |
| Git Daily Report | Not supported | Supported |
| UI Design | Plain text | Borders, colors, alignment |

---

## Project Structure
tdkit-beta/

├── src/

│   └── tdkit          # Main executable script

├── README.md           # This file

├── CHANGELOG.md        # Version history

└── LICENSE             # MIT License

---

## License

MIT License — Copyright (c) 2026 nyu3321225  
See [LICENSE](LICENSE) for full text.
