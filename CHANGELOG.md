# Changelog

All notable changes to this project will be documented in this file.

## [v1.0.1-ui] - 2026-06-14 (Beta)

### Added
| Feature | Description |
|---------|-------------|
| Bilingual Menu | Chinese / English selection on startup |
| User Agreement | Yes/No prompt on first launch |
| Internal IP Detection | Three fallback methods (ip → arp → ping) |
| Smart Suggestions | Auto-detect missing tools after environment check |
| Git Daily Report | Analyze any local repository's commit history |
| Trust Confirmation | Confirm before reading repository data |

### Fixed
| Bug | Description |
|-----|-------------|
| Menu Numbering | Duplicate numbers in select statements |
| Tool Detection Crash | Error when --version flag is unsupported |
| Initialization Loop | Repeated prompts on every launch |
| Syntax Error | Script failure due to incomplete sed edits |

### Changed
- Complete UI overhaul with borders, colors, and aligned layout
- Storage usage now displays formatted output with labels
- Updated installation path to src/ directory

## [v1.0.0-beta] - 2026-06-14

### Added
- Initial public release
- Environment check for 22 development tools
- Category-based tool installer (5 categories)
- Storage usage display
- Public IP lookup
- Project skeleton creation (Python, Node.js, Generic)
- MIT License
