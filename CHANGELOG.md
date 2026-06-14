# Changelog / 更新日志

## [v1.0.0-beta] - 2026-06-14

### Added / 新增
- 首次发布，内部测试版
- 环境检查：检测 22 种开发工具
- 分类安装：按 5 个分类选装工具
- 存储监控：显示内部存储和家目录使用情况
- IP 查询：获取公网 IPv4/IPv6 地址
- 项目骨架：支持 Python、Node.js、通用项目模板

### Test Results / 测试结果

Test Date: 2026-06-14  
Tester: nyu3321225  
Device: Android Termux  
Model: GLM-4-Flash (Free Tier)

| Feature | Status | Notes |
|---------|--------|-------|
| Environment Check | ✅ Pass | 22/22 tools detected |
| Tool Installer | ✅ Pass | All categories skip correctly |
| Storage Monitor | ✅ Pass | 934G total, 42% used |
| IP Lookup | ✅ Pass | IPv6 retrieved successfully |
| Project Scaffold | ✅ Pass | Python project created |

### Known Issues / 已知问题
- `select` menu shows duplicate numbering (cosmetic only)
- Some tools lack `--version` support (falls back gracefully)
- Public IP may fail on restricted networks
