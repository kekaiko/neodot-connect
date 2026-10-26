<p align="center"><img src="public/brand.svg" alt="NeoDot Connect" width="96"></p>

# NeoDot Connect

NeoDot AI 官方跨平台极简配置器。一键打通 Claude Code 与 OpenAI Codex：选择中转站、选择客户端、输入 API Key、勾选模型，一键注入配置。

**v0.1.6** · [Releases 下载](https://github.com/neodot-ai/neodot-connect/releases) · [问题反馈](https://github.com/neodot-ai/neodot-connect/issues) · [MIT 开源许可](LICENSE)

---

## 一键下载

| 操作系统 | 下载链接 | 打开与使用方式 |
| :--- | :--- | :--- |
| **Windows 10 / 11 · x64** | [Windows 免安装便携版 (.zip)](https://github.com/neodot-ai/neodot-connect/releases/latest/download/NeoDot-Connect-Windows-x64-portable.zip) | 解压后双击运行 `NeoDot Connect.exe` |
| **macOS · Apple Silicon** | [macOS 压缩包 (.zip)](https://github.com/neodot-ai/neodot-connect/releases/latest/download/NeoDot-Connect-macOS-arm64.zip) | 解压后打开 `NeoDot Connect.app`，可拖入「应用程序」 |

> **提示**：本软件发布于 [GitHub Releases](https://github.com/neodot-ai/neodot-connect/releases)。解压即用，无须配置复杂的 Python、Node.js 或 Rust 环境。

---

## 4 步快速接入

1. **选择中转站**：默认内置 **NeoDot AI** (`https://ai.neodot.shop`)，您也可以添加其他第三方兼容节点。
2. **选择目标客户端**：支持 Claude (Desktop / CLI Code) 与 OpenAI Codex (Desktop / CLI / VS Code)。
3. **填写 API Key**：在 [NeoDot AI 控制台](https://ai.neodot.shop/keys) 创建并复制您的密钥，点击获取模型列表。
4. **一键导入生效**：勾选常用模型并设定默认项，点击「导入」。完全退出目标客户端并重启，即可开始对话！

---

## 安全与隐私保障

- **零密钥上传**：您的 API Key 仅保留在您本机的客户端配置文件中，绝不上传任何云端服务器；
- **一键原状恢复**：点击右上角「恢复原配置」，随时无损撤销所有配置，保留历史备份；
- **宽松开源许可**：核心遵循 MIT 宽松协议，代码全公开、透明可审计。

---

## 本地开发与编译

```bash
# 1. 安装依赖
pnpm install

# 2. 启动本地开发调试
pnpm dev

# 3. 本地打包
pnpm build:windows # Windows 免安装打包
pnpm build:macos   # macOS Apple Silicon 打包
```

© NeoDot AI · [https://neodot.shop](https://neodot.shop) · 官方文档：[https://neodot.shop/connect](https://neodot.shop/connect)
