<div align="center">

# Director Mode for Claude Code

**Don't write code. Direct Claude to write code for you.**

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

<details><summary><b>🇹🇼 繁體中文</b></summary>

# Director Mode for Claude Code

**不要寫程式碼，指揮 Claude 幫你寫。**

## 總監模式

一種改變你與 Claude Code 協作方式的方法論。

```
傳統方式：你一行行寫程式 → AI 輔助片段 → 來回修正好幾小時
總監模式：你定義願景 → AI 自主執行 → 完整、測試、文件完備
```

## Director Mode Lite

免費開源工具包：Auto-Loop、13 個指令、3 個 Agents、4 個 Skills

```bash
/plugin marketplace add claude-world/director-mode-lite
```

**社群**：[Discord](https://discord.com/invite/rBtHzSD288) • [網站](https://claude-world.com)

</details>

<details><summary><b>🇯🇵 日本語</b></summary>

# Director Mode for Claude Code

**コードを書くな、Claude に指示を出せ。**

## ディレクターモード

Claude Code との協業を変革するメソドロジー。

```
従来の方法: コードを1行ずつ書く → AIが支援 → 数時間やり取り
ディレクターモード: ビジョンを定義 → AIが自律実行 → 完成品
```

## Director Mode Lite

無料オープンソースツールキット

```bash
/plugin marketplace add claude-world/director-mode-lite
```

**コミュニティ**：[Discord](https://discord.com/invite/rBtHzSD288) • [ウェブサイト](https://claude-world.com)

</details>

---

<div align="center">

Made with direction by [Claude World Taiwan](https://claude-world.com) 🇹🇼

</div>
