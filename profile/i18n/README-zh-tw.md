<div align="center">

# Claude World

**精通 Claude Code 的開源工具生態系**

<a href="../README.md">English</a> • 繁體中文 • <a href="README-ja.md">日本語</a>

[![Website](https://img.shields.io/badge/網站-claude--world.com-blue?style=flat-square)](https://claude-world.com)
[![Discord](https://img.shields.io/badge/Discord-加入社群-7289da?style=flat-square&logo=discord&logoColor=white)](https://discord.com/invite/rBtHzSD288)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)

</div>

---

## 開源專案

### 開發工具包

| 專案 | Stars | 說明 |
|------|-------|------|
| **[director-mode-lite](https://github.com/claude-world/director-mode-lite)** | ![Stars](https://img.shields.io/github/stars/claude-world/director-mode-lite?style=flat-square) | 不寫程式碼 — 指揮 Claude 寫。25 commands、14 agents、29 skills + TDD Auto-Loop。 |
| **[claude-world-examples](https://github.com/claude-world/claude-world-examples)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-world-examples?style=flat-square) | Claude Code 和 Director Mode 實戰範例與最佳實踐。 |

### 安全

| 專案 | Stars | 說明 |
|------|-------|------|
| **[claude-skill-antivirus](https://github.com/claude-world/claude-skill-antivirus)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-skill-antivirus?style=flat-square) | Claude Code Skills 安全掃描器 — 9 引擎偵測 71K+ skills 中的惡意模式。 |

### MCP 伺服器

| 專案 | Stars | 說明 |
|------|-------|------|
| **[cf-browser](https://github.com/claude-world/cf-browser)** | ![Stars](https://img.shields.io/github/stars/claude-world/cf-browser?style=flat-square) | Cloudflare Browser Rendering 代理 — 9 個 MCP 工具（截圖、PDF、Markdown、爬取）。 |
| **[trend-pulse](https://github.com/claude-world/trend-pulse)** | ![Stars](https://img.shields.io/github/stars/claude-world/trend-pulse?style=flat-square) | 免費趨勢聚合器 — 15 個來源、零認證。CLI + Python 函式庫 + MCP Server。 |
| **[mcp-director-mode-server](https://github.com/claude-world/mcp-director-mode-server)** | ![Stars](https://img.shields.io/github/stars/claude-world/mcp-director-mode-server?style=flat-square) | Director Mode 教學用 MCP Server — TDD、Auto-Cycle、SpecKit 示範。 |

### 工具

| 專案 | Stars | 說明 |
|------|-------|------|
| **[skills-optimizer](https://github.com/claude-world/skills-optimizer)** | ![Stars](https://img.shields.io/github/stars/claude-world/skills-optimizer?style=flat-square) | 壓縮 Claude Code agents & skills — 6:1 壓縮比，語意驗證保真。 |
| **[skill-universal](https://github.com/claude-world/skill-universal)** | ![Stars](https://img.shields.io/github/stars/claude-world/skill-universal?style=flat-square) | 寫一次 Skill，到處運行 — Claude Code、Agent SDK、OpenClaw。 |
| **[claude-code-rfcs](https://github.com/claude-world/claude-code-rfcs)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-code-rfcs?style=flat-square) | 社群驅動的 Claude Code 架構提案。 |

---

## 快速開始

```bash
# 安裝 Director Mode Lite
curl -fsSL https://raw.githubusercontent.com/claude-world/director-mode-lite/main/install.sh | bash -s .

# 掃描 skill 安全性
npx claude-skill-antivirus scan <skill-name>

# 透過 MCP 取得趨勢話題
npx trend-pulse trending --geo TW --count 10
```

---

## 社群

<div align="center">

[**claude-world.com**](https://claude-world.com) &nbsp;•&nbsp;
[**Discord**](https://discord.com/invite/rBtHzSD288) &nbsp;•&nbsp;
[**GitHub Issues**](https://github.com/claude-world/director-mode-lite/issues)

由 [Claude World Taiwan](https://claude-world.com) 打造 🇹🇼

</div>
