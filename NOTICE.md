# TDKit Notice / 重要公告

## Before Installation / 安装前须知

You need:
- Termux installed
- Internet connection
- `wget` or `curl` (curl usually pre-installed)

That's it. TDKit itself has zero dependencies.

你只需要：
- 已安装 Termux
- 网络连接
- `wget` 或 `curl`（Termux 通常自带 curl）

除此之外，TDKit 本身零依赖，装完即用。

## If wget is missing / 如果缺少 wget


bash

pkg install wget -y

Or use curl instead:
bash

curl -Lo /data/data/com.termux/files/usr/bin/tdkit https://raw.githubusercontent.com/nyu3321225/tdkit-beta/main/tdkit/tdkit 

chmod +x /data/data/com.termux/files/usr/bin/tdkit

tdkit

## Disclaimer / 免责声明

This is a beta release. Use at your own risk.  
本工具为测试版本，使用风险自负。

## Contact / 联系方式

GitHub Issues: https://github.com/nyu3321225/tdkit-beta/issues

---

## Required Dependencies / 必要依赖

TDKit 本身是零依赖脚本，但以下功能需要系统工具支持：

| 功能 | 依赖 | 安装命令 |
|------|------|----------|
| 环境检查 | bash（自带） | 无需安装 |
| 工具安装 | pkg（自带） | 无需安装 |
| 存储查看 | df（自带） | 无需安装 |
| 公网 IP | curl（通常自带） | `pkg install curl -y` |
| 内网 IP | ip（来自 iproute2） | `pkg install iproute2 -y` |
| 下载脚本 | wget 或 curl | `pkg install wget -y` |

### Recommended / 推荐安装
bash

pkg install iproute2 curl wget -y

这三样装好，TDKit 所有功能都能正常使用。

### Note / 说明

- `iproute2` 提供 `ip` 命令，用于获取内网 IP 地址
- `curl` 用于获取公网 IP 地址
- `wget` 用于下载脚本（安装时用）
- 以上均为常见系统工具，不影响 TDKit 本身的零依赖特性
