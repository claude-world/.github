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

完整且包含生命週期的正式清單位於
[ClaudeWorld Public Works](https://claude-world.com/zh-tw/open-source/)：
13 個活躍原創專案、3 個封存實驗與 1 個明示上游 fork。封存庫保留作為
lineage，但不包裝成持續維護中的產品。

### 開發工具包

| 專案 | Stars | 說明 |
|------|-------|------|
| **[director-mode-lite](https://github.com/claude-world/director-mode-lite)** | ![Stars](https://img.shields.io/github/stars/claude-world/director-mode-lite?style=flat-square) | Claude Code、Codex CLI 與 Grok Build 原生 adapters；35 個共用 skills、14 個 agent adapters、預設零 hooks 與可攜 session relay。 |
| **[agent-deck](https://github.com/claude-world/agent-deck)** | ![Stars](https://img.shields.io/github/stars/claude-world/agent-deck?style=flat-square) | 任務拆解、DAG 執行、agent 即時串流與 git 收尾的瀏覽器控制台。 |
| **[agentOS](https://github.com/claude-world/agentOS)** | ![Stars](https://img.shields.io/github/stars/claude-world/agentOS?style=flat-square) | 開源 iPhone 原生 agent host，整合工具、agents、channels 與多模型供應商。 |
| **[claude-agent](https://github.com/claude-world/claude-agent)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-agent?style=flat-square) | 組合記憶、skills、MCP servers 與內容流程的持久個人助理實驗。 |
| **[claude-world-examples](https://github.com/claude-world/claude-world-examples)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-world-examples?style=flat-square) | Claude Code 和 Director Mode 實戰範例與最佳實踐。 |
| **[discord-engagement-bot](https://github.com/claude-world/discord-engagement-bot)** | ![Stars](https://img.shields.io/github/stars/claude-world/discord-engagement-bot?style=flat-square) | 排程社群提示、討論與彙整的 Electron menubar 實驗。 |

### 安全

| 專案 | Stars | 說明 |
|------|-------|------|
| **[claude-skill-antivirus](https://github.com/claude-world/claude-skill-antivirus)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-skill-antivirus?style=flat-square) | Claude Code Skills 安全掃描器 — 9 引擎偵測 71K+ skills 中的惡意模式。 |

### MCP 伺服器與整合

| 專案 | Stars | 說明 |
|------|-------|------|
| **[cf-browser](https://github.com/claude-world/cf-browser)** | ![Stars](https://img.shields.io/github/stars/claude-world/cf-browser?style=flat-square) | Cloudflare Browser Rendering 代理 — 10 個 MCP 工具（截圖、PDF、Markdown、爬取、無障礙樹）。 |
| **[trend-pulse](https://github.com/claude-world/trend-pulse)** | ![Stars](https://img.shields.io/github/stars/claude-world/trend-pulse?style=flat-square) | 免費趨勢聚合器 — 20 個來源、零認證。CLI + Python 函式庫 + MCP Server。 |
| **[notebooklm-skill](https://github.com/claude-world/notebooklm-skill)** | ![Stars](https://img.shields.io/github/stars/claude-world/notebooklm-skill?style=flat-square) | NotebookLM 做研究，Claude 寫內容。研究到內容的自動化 pipeline，13 個 MCP 工具。 |
| **[claude-world-studio](https://github.com/claude-world/claude-world-studio)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-world-studio?style=flat-square) | 以 Agent SDK 與 MCP 串起趨勢探索、研究、內容合成與社群發布。 |

### 工具

| 專案 | Stars | 說明 |
|------|-------|------|
| **[skills-optimizer](https://github.com/claude-world/skills-optimizer)** | ![Stars](https://img.shields.io/github/stars/claude-world/skills-optimizer?style=flat-square) | 壓縮 Claude Code agents & skills — 6:1 壓縮比，語意驗證保真。 |
| **[claude-101](https://github.com/claude-world/claude-101)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-101?style=flat-square) | 27 個寫作、分析、程式與商務用確定性工具，提供 CLI 與 MCP。 |

### 封存與 Lineage

| 專案 | 狀態 | 說明 |
|------|------|------|
| [mcp-director-mode-server](https://github.com/claude-world/mcp-director-mode-server) | **已封存** | 教學 MCP server，保留作為實作歷史。 |
| [skill-universal](https://github.com/claude-world/skill-universal) | **已封存** | 跨 runtime skill 格式實驗，保留 lineage。 |
| [claude-code-rfcs](https://github.com/claude-world/claude-code-rfcs) | **已封存** | 社群 RFC 空間，保留為歷史紀錄。 |
| [sdd-mcp-fork-member](https://github.com/claude-world/sdd-mcp-fork-member) | **上游 fork** | 規格驅動 MCP lineage；不視為 ClaudeWorld 原創專案。 |

---

## 快速開始

```bash
# 安裝 Director Mode Lite
curl -fsSL https://raw.githubusercontent.com/claude-world/director-mode-lite/main/install.sh | bash -s .

# 掃描 skill 安全性
npx claude-skill-antivirus scan <skill-name>

# 透過 MCP 取得趨勢話題
pip install "trend-pulse[mcp]"
trend-pulse trending --geo TW --count 10
```

---

## 社群

<div align="center">

[**claude-world.com**](https://claude-world.com) &nbsp;•&nbsp;
[**Discord**](https://discord.com/invite/rBtHzSD288) &nbsp;•&nbsp;
[**GitHub Issues**](https://github.com/claude-world/director-mode-lite/issues)

由 [Claude World Taiwan](https://claude-world.com) 打造 🇹🇼

</div>
