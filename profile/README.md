<div align="center">

# Director Mode for Claude Code

**Don't write code. Direct Claude to write code for you.**

<a href="i18n/README-zh-tw.md">繁體中文</a> • <a href="i18n/README-ja.md">日本語</a>

<br/>

[![Website](https://img.shields.io/badge/Website-claude--world.com-blue?style=flat-square)](https://claude-world.com)
[![Discord](https://img.shields.io/badge/Discord-Join%20Community-7289da?style=flat-square&logo=discord&logoColor=white)](https://discord.com/invite/rBtHzSD288)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![Stars](https://img.shields.io/github/stars/claude-world/director-mode-lite?style=flat-square)](https://github.com/claude-world/director-mode-lite/stargazers)

</div>

---

## Introduction

**Director Mode** transforms how you work with Claude Code. Instead of writing code line by line, you define the vision and Claude executes autonomously.

<table><tr><td width="50%">

**Traditional AI Coding**
```
You: "Help me write a function"
AI: "Here's a function"
You: "Now add error handling"
AI: "Here's updated code"
You: "Now write tests"
AI: "Here are tests"
...repeats for hours
```

</td><td width="50%">

**Director Mode**
```
You: "Build a REST API with auth,
       tests, and docs"

AI: Analyzes → Plans → Implements
    → Tests → Documents → Done

✓ Complete, tested, documented
```

</td></tr></table>

---

## 🚀 Director Mode Lite

Free, open-source toolkit for Claude Code with **TDD-based Auto-Loop** that runs until all acceptance criteria are met.

```bash
/auto-loop "Create a Todo module with add, remove, toggle functions and unit tests"

# Claude automatically iterates:
# RED   → Write failing tests
# GREEN → Make tests pass
# REFACTOR → Clean up code
# → Repeats until all criteria met ✓
```

### What's Included

| Component | Count | Description |
|-----------|-------|-------------|
| **Commands** | 13 | `/auto-loop`, `/workflow`, `/focus-problem`, etc. |
| **Agents** | 3 | code-reviewer, debugger, doc-writer |
| **Skills** | 4 | Specialized expertise modules |

---

## 📦 Quick Install

```bash
/plugin marketplace add claude-world/director-mode-lite
```

Or with curl:

```bash
curl -fsSL https://raw.githubusercontent.com/claude-world/director-mode-lite/main/install.sh | bash -s .
```

---

## 🛠️ Commands

| Command | Description |
|---------|-------------|
| `/auto-loop` | TDD autonomous development (runs until done) |
| `/workflow` | 5-step flow: Focus → Prevent → Test → Doc → Commit |
| `/focus-problem` | Deep analysis before coding |
| `/test-first` | TDD cycle (Red-Green-Refactor) |
| `/smart-commit` | Auto-generate conventional commits |
| `/plan` | Break down tasks with TodoWrite |

[View all 13 commands](https://github.com/claude-world/director-mode-lite#commands)

---

## 📚 Projects

<table><tr><td width="50%">

**[Director Mode Lite](https://github.com/claude-world/director-mode-lite)**

Complete toolkit for Claude Code
- 13 commands
- 3 agents
- 4 skills
- Auto-Loop

</td><td width="50%">

**[Examples](https://github.com/claude-world/director-mode-lite/tree/main/examples)**

Hands-on tutorials
- Calculator (5 min)
- REST API (15 min)

</td></tr></table>

---

## 🌐 Community

<div align="center">

[**Website**](https://claude-world.com) &nbsp;•&nbsp;
[**Discord**](https://discord.com/invite/rBtHzSD288) &nbsp;•&nbsp;
[**GitHub Issues**](https://github.com/claude-world/director-mode-lite/issues)

</div>

---

<div align="center">

Made with direction by [Claude World Taiwan](https://claude-world.com) 🇹🇼

</div>
