<div align="center">

# Claude World

**Open-source tools for mastering Claude Code**

<a href="i18n/README-zh-tw.md">繁體中文</a> • <a href="i18n/README-ja.md">日本語</a>

[![Website](https://img.shields.io/badge/Website-claude--world.com-blue?style=flat-square)](https://claude-world.com)
[![Discord](https://img.shields.io/badge/Discord-Join%20Community-7289da?style=flat-square&logo=discord&logoColor=white)](https://discord.com/invite/rBtHzSD288)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)

</div>

---

## Projects

The canonical lifecycle-aware inventory is the
[ClaudeWorld Public Works registry](https://claude-world.com/open-source/):
13 active original projects, 3 archived experiments, and 1 labeled upstream
fork. Archived repositories remain visible for lineage but are not presented as
maintained products.

### Development Toolkit

| Project | Stars | Description |
|---------|-------|-------------|
| **[director-mode-lite](https://github.com/claude-world/director-mode-lite)** | ![Stars](https://img.shields.io/github/stars/claude-world/director-mode-lite?style=flat-square) | Native Claude Code, Codex CLI, and Grok Build adapters with 35 shared skills, 14 agent adapters, zero Director Mode hooks by default, and portable session relay. |
| **[agent-deck](https://github.com/claude-world/agent-deck)** | ![Stars](https://img.shields.io/github/stars/claude-world/agent-deck?style=flat-square) | Browser command center for task decomposition, DAG execution, live agent streams, and git finalization. |
| **[agentOS](https://github.com/claude-world/agentOS)** | ![Stars](https://img.shields.io/github/stars/claude-world/agentOS?style=flat-square) | Open-source iPhone-native agent host with tools, agents, channels, and multiple model providers. |
| **[claude-agent](https://github.com/claude-world/claude-agent)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-agent?style=flat-square) | Persistent personal-assistant experiment combining memory, skills, MCP servers, and content workflows. |
| **[claude-world-examples](https://github.com/claude-world/claude-world-examples)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-world-examples?style=flat-square) | Practical examples & best practices for Claude Code and Director Mode. |
| **[discord-engagement-bot](https://github.com/claude-world/discord-engagement-bot)** | ![Stars](https://img.shields.io/github/stars/claude-world/discord-engagement-bot?style=flat-square) | Electron menubar experiment for scheduled community prompts, discussions, and roundups. |

### Security

| Project | Stars | Description |
|---------|-------|-------------|
| **[claude-skill-antivirus](https://github.com/claude-world/claude-skill-antivirus)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-skill-antivirus?style=flat-square) | Security scanner for Claude Code Skills — 9 engines detect malicious patterns across 71K+ skills. |

### MCP Servers & Integrations

| Project | Stars | Description |
|---------|-------|-------------|
| **[cf-browser](https://github.com/claude-world/cf-browser)** | ![Stars](https://img.shields.io/github/stars/claude-world/cf-browser?style=flat-square) | Cloudflare Browser Rendering proxy — 10 MCP tools (screenshot, PDF, markdown, scrape, a11y, crawl). |
| **[trend-pulse](https://github.com/claude-world/trend-pulse)** | ![Stars](https://img.shields.io/github/stars/claude-world/trend-pulse?style=flat-square) | Free trending topics aggregator — 20 sources, zero auth. CLI + Python library + MCP Server. |
| **[notebooklm-skill](https://github.com/claude-world/notebooklm-skill)** | ![Stars](https://img.shields.io/github/stars/claude-world/notebooklm-skill?style=flat-square) | NotebookLM does the research, Claude writes the content. Research-to-content pipeline with 13 MCP tools. |
| **[claude-world-studio](https://github.com/claude-world/claude-world-studio)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-world-studio?style=flat-square) | Agent SDK and MCP content operation connecting trend discovery, research, synthesis, and social publishing. |

### Utilities

| Project | Stars | Description |
|---------|-------|-------------|
| **[skills-optimizer](https://github.com/claude-world/skills-optimizer)** | ![Stars](https://img.shields.io/github/stars/claude-world/skills-optimizer?style=flat-square) | Compress Claude Code agents & skills — 6:1 compression with semantic verification. |
| **[claude-101](https://github.com/claude-world/claude-101)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-101?style=flat-square) | 27 deterministic computation tools for writing, analysis, coding, and business, packaged as CLI and MCP. |

### Archive & Lineage

| Project | Status | Description |
|---------|--------|-------------|
| [mcp-director-mode-server](https://github.com/claude-world/mcp-director-mode-server) | **Archived** | Teaching MCP server retained as implementation history. |
| [skill-universal](https://github.com/claude-world/skill-universal) | **Archived** | Cross-runtime skill-format experiment retained for lineage. |
| [claude-code-rfcs](https://github.com/claude-world/claude-code-rfcs) | **Archived** | Community RFC space retained as an historical record. |
| [sdd-mcp-fork-member](https://github.com/claude-world/sdd-mcp-fork-member) | **Upstream fork** | Public fork retained for specification-driven MCP lineage; not claimed as an original ClaudeWorld project. |

---

## Quick Start

```bash
# Install Director Mode Lite
curl -fsSL https://raw.githubusercontent.com/claude-world/director-mode-lite/main/install.sh | bash -s .

# Scan a skill for security
npx claude-skill-antivirus scan <skill-name>

# Get trending topics via MCP
pip install "trend-pulse[mcp]"
trend-pulse trending --geo TW --count 10
```

---

## Community

<div align="center">

[**claude-world.com**](https://claude-world.com) &nbsp;•&nbsp;
[**Discord**](https://discord.com/invite/rBtHzSD288) &nbsp;•&nbsp;
[**Discussions**](https://github.com/orgs/claude-world/discussions)

Made by [Claude World Taiwan](https://claude-world.com) 🇹🇼

</div>
