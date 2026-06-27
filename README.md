# Gclm Agent

桌面端 AI Agent 客户端。基于 Tauri 2 + Rust + React + TypeScript。

## 下载

前往 [Releases](https://github.com/gclm/agent/releases/latest) 页面下载最新版本。

| 平台 | 格式 | 说明 |
|------|------|------|
| macOS (Apple Silicon) | `.dmg` | universal binary (aarch64 + x86_64) |
| macOS (Intel) | `.dmg` | 包含在 universal binary 中 |
| Windows | `.exe` | NSIS 安装包（x86_64） |

### macOS 首次打开提示「无法验证开发者」

应用未签名，需要右键 → 「打开」→「打开」确认。

## 自动构建

本仓库通过 GitHub Actions 在 macOS / Windows runner 上自动构建安装包，并以 Draft Release 形式发布。详见 [`.github/workflows/release.yml`](.github/workflows/release.yml)。

## License

Private — all rights reserved.
