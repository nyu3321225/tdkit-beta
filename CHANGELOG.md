# Changelog

## [1.0.0-beta] - 2026-06-14

### Added
- Initial beta release
- Environment check: detect 22 development tools with version display
- Category-based installer: Basic, Media, Terminal Enhancement, Network, Development
- Storage monitor: display disk usage for internal storage and home directory
- IP lookup: retrieve public IPv4/IPv6 address via curl
- Project scaffold: generate Python, Node.js, and generic project skeletons
- Color-coded terminal output for better readability
- Command-line flags: -e (direct env check), -i (direct install mode)

### Test Results

| Test Case | Status | Detail |
|-----------|--------|--------|
| Environment Check | ✅ Pass | 22/22 tools detected |
| Category Installer | ✅ Pass | All 5 categories skipped correctly |
| Storage Monitor | ✅ Pass | Total 934G, 42% used |
| IP Lookup | ✅ Pass | IPv6 retrieved successfully |
| Project Scaffold | ✅ Pass | Python project created under ./ |

### Known Issues
- `select` menu shows duplicate numbering in some Termux builds (cosmetic only)
- Some tools lack `--version` support; falls back to "installed" without version string
- Public IP retrieval may fail on networks without internet access
- Project scaffold currently supports 3 templates

### Notes
- Tested on Android Termux
- Requires wget or curl for installation
- Zero external dependencies after installation
