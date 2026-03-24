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

### Content & Automation

| Project | Stars | Description |
|---------|-------|-------------|
| **[notebooklm-skill](https://github.com/claude-world/notebooklm-skill)** | ![Stars](https://img.shields.io/github/stars/claude-world/notebooklm-skill?style=flat-square) | NotebookLM does the research, Claude writes the content. Research-to-content pipeline with 13 MCP tools. |
| **[claude-world-studio](https://github.com/claude-world/claude-world-studio)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-world-studio?style=flat-square) | AI-powered content pipeline: trend discovery → research → social publishing. Built with Claude Agent SDK + MCP. |
| **[trend-pulse](https://github.com/claude-world/trend-pulse)** | ![Stars](https://img.shields.io/github/stars/claude-world/trend-pulse?style=flat-square) | Free trending topics aggregator — 20 sources, zero auth. CLI + Python library + MCP Server. |

### Development Toolkit

| Project | Stars | Description |
|---------|-------|-------------|
| **[director-mode-lite](https://github.com/claude-world/director-mode-lite)** | ![Stars](https://img.shields.io/github/stars/claude-world/director-mode-lite?style=flat-square) | Don't write code — direct Claude to write it. 25 commands, 14 agents, 29 skills with TDD Auto-Loop. |
| **[claude-agent](https://github.com/claude-world/claude-agent)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-agent?style=flat-square) | Persistent personal assistant powered by Claude Code — autonomous memory, 13 skills, 4 MCP servers. |
| **[claude-world-examples](https://github.com/claude-world/claude-world-examples)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-world-examples?style=flat-square) | Practical examples & best practices for Claude Code and Director Mode. |

### Security

| Project | Stars | Description |
|---------|-------|-------------|
| **[claude-skill-antivirus](https://github.com/claude-world/claude-skill-antivirus)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-skill-antivirus?style=flat-square) | Security scanner for Claude Code Skills — 9 engines detect malicious patterns across 71K+ skills. |

### MCP Servers & Integrations

| Project | Stars | Description |
|---------|-------|-------------|
| **[cf-browser](https://github.com/claude-world/cf-browser)** | ![Stars](https://img.shields.io/github/stars/claude-world/cf-browser?style=flat-square) | Cloudflare Browser Rendering proxy — 10 MCP tools (screenshot, PDF, markdown, scrape, a11y, crawl). |
| **[mcp-director-mode-server](https://github.com/claude-world/mcp-director-mode-server)** | ![Stars](https://img.shields.io/github/stars/claude-world/mcp-director-mode-server?style=flat-square) | Teaching MCP Server for Director Mode — TDD, Auto-Cycle, SpecKit demos. |
| **[claude-101](https://github.com/claude-world/claude-101)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-101?style=flat-square) | 27 practical AI tools (MCP server + CLI) — real computation for writing, analysis, coding, and business. |

### Utilities

| Project | Stars | Description |
|---------|-------|-------------|
| **[skills-optimizer](https://github.com/claude-world/skills-optimizer)** | ![Stars](https://img.shields.io/github/stars/claude-world/skills-optimizer?style=flat-square) | Compress Claude Code agents & skills — 6:1 compression with semantic verification. |
| **[skill-universal](https://github.com/claude-world/skill-universal)** | ![Stars](https://img.shields.io/github/stars/claude-world/skill-universal?style=flat-square) | Write Skills once, run everywhere — Claude Code, Agent SDK, OpenClaw. |
| **[claude-code-rfcs](https://github.com/claude-world/claude-code-rfcs)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-code-rfcs?style=flat-square) | Community-driven RFCs for Claude Code architectural proposals. |

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

Made by [Claude World Taiwan](https://claude-world.com)

</div>
