# Gclm Agent

桌面端 AI Agent 客户端。基于 Tauri 2 + Rust + React + TypeScript。

> 源代码仓库（私有）：[gclm/gclm-agent](https://github.com/gclm/gclm-agent)
>
> 本仓库用于发布构建产物。如需报告问题或查看源码，请联系仓库管理员。

## 下载

前往 [Releases](https://github.com/gclm/agent/releases/latest) 页面下载最新版本。

| 平台 | 格式 | 说明 |
|------|------|------|
| macOS (Apple Silicon) | `.dmg` | `aarch64` universal binary |
| macOS (Intel) | `.dmg` | `x86_64` 包含在 universal 中 |
| Windows | `.exe` | NSIS 安装包（x86_64） |

### macOS 首次打开提示「无法验证开发者」

应用未签名，需要右键 → 「打开」→「打开」确认。

## 自动发版

本仓库通过 GitHub Actions 自动构建：

1. 源代码仓库打版本 tag（如 `v0.1.0`）
2. 通过 webhook 触发本仓库的 Release workflow
3. 在 macOS / Windows runner 上构建安装包
4. 自动创建 Release 草稿，管理员确认后发布

详见 [`.github/workflows/release.yml`](.github/workflows/release.yml)。

## License

Private — all rights reserved.
