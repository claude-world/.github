<div align="center">

# Claude World

**Claude Code をマスターするためのオープンソースツール**

<a href="../README.md">English</a> • <a href="README-zh-tw.md">繁體中文</a> • 日本語

[![Website](https://img.shields.io/badge/ウェブサイト-claude--world.com-blue?style=flat-square)](https://claude-world.com)
[![Discord](https://img.shields.io/badge/Discord-参加-7289da?style=flat-square&logo=discord&logoColor=white)](https://discord.com/invite/rBtHzSD288)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)

</div>

---

## プロジェクト

[ClaudeWorld Public Works](https://claude-world.com/ja/open-source/) が
lifecycle を含む正式な一覧です。13 active originals、3 archived
experiments、1 labeled upstream fork を分け、archive を維持中の製品として
扱いません。

### 開発ツールキット

| プロジェクト | Stars | 説明 |
|------------|-------|------|
| **[director-mode-lite](https://github.com/claude-world/director-mode-lite)** | ![Stars](https://img.shields.io/github/stars/claude-world/director-mode-lite?style=flat-square) | Claude Code、Codex CLI、Grok Build native adapters。35 shared skills、14 agent adapters、default zero hooks、portable session relay。 |
| **[agent-deck](https://github.com/claude-world/agent-deck)** | ![Stars](https://img.shields.io/github/stars/claude-world/agent-deck?style=flat-square) | タスク分解、DAG 実行、agent live stream、git finalization の browser console。 |
| **[agentOS](https://github.com/claude-world/agentOS)** | ![Stars](https://img.shields.io/github/stars/claude-world/agentOS?style=flat-square) | tools、agents、channels、複数 model providers を備えた open-source iPhone-native agent host。 |
| **[claude-agent](https://github.com/claude-world/claude-agent)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-agent?style=flat-square) | memory、skills、MCP servers、content workflow を統合する persistent assistant experiment。 |
| **[claude-world-examples](https://github.com/claude-world/claude-world-examples)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-world-examples?style=flat-square) | Claude Code と Director Mode の実践例とベストプラクティス。 |
| **[discord-engagement-bot](https://github.com/claude-world/discord-engagement-bot)** | ![Stars](https://img.shields.io/github/stars/claude-world/discord-engagement-bot?style=flat-square) | community prompts、discussions、roundups を予約する Electron menubar experiment。 |

### セキュリティ

| プロジェクト | Stars | 説明 |
|------------|-------|------|
| **[claude-skill-antivirus](https://github.com/claude-world/claude-skill-antivirus)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-skill-antivirus?style=flat-square) | Claude Code Skills セキュリティスキャナー — 9 エンジンで 71K+ skills の悪意パターンを検出。 |

### MCP サーバー & 連携

| プロジェクト | Stars | 説明 |
|------------|-------|------|
| **[cf-browser](https://github.com/claude-world/cf-browser)** | ![Stars](https://img.shields.io/github/stars/claude-world/cf-browser?style=flat-square) | Cloudflare Browser Rendering プロキシ — 10 MCP ツール（スクリーンショット、PDF、Markdown、クロール、a11y）。 |
| **[trend-pulse](https://github.com/claude-world/trend-pulse)** | ![Stars](https://img.shields.io/github/stars/claude-world/trend-pulse?style=flat-square) | 無料トレンドアグリゲーター — 20 ソース、認証不要。CLI + Python + MCP Server。 |
| **[notebooklm-skill](https://github.com/claude-world/notebooklm-skill)** | ![Stars](https://img.shields.io/github/stars/claude-world/notebooklm-skill?style=flat-square) | NotebookLM でリサーチ、Claude でコンテンツ作成。13 MCP ツール搭載のパイプライン。 |
| **[claude-world-studio](https://github.com/claude-world/claude-world-studio)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-world-studio?style=flat-square) | Agent SDK と MCP で trend discovery、research、synthesis、social publishing を接続。 |

### ユーティリティ

| プロジェクト | Stars | 説明 |
|------------|-------|------|
| **[skills-optimizer](https://github.com/claude-world/skills-optimizer)** | ![Stars](https://img.shields.io/github/stars/claude-world/skills-optimizer?style=flat-square) | Claude Code agents & skills を圧縮 — 6:1 圧縮率、セマンティック検証。 |
| **[claude-101](https://github.com/claude-world/claude-101)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-101?style=flat-square) | writing、analysis、coding、business 向け 27 deterministic tools。CLI + MCP。 |

### Archive & Lineage

| プロジェクト | 状態 | 説明 |
|------------|------|------|
| [mcp-director-mode-server](https://github.com/claude-world/mcp-director-mode-server) | **Archived** | 教育用 MCP server。実装履歴として保持。 |
| [skill-universal](https://github.com/claude-world/skill-universal) | **Archived** | cross-runtime skill format experiment。lineage として保持。 |
| [claude-code-rfcs](https://github.com/claude-world/claude-code-rfcs) | **Archived** | community RFC space。履歴として保持。 |
| [sdd-mcp-fork-member](https://github.com/claude-world/sdd-mcp-fork-member) | **Upstream fork** | specification-driven MCP lineage。ClaudeWorld original として扱いません。 |

---

## クイックスタート

```bash
# Director Mode Lite をインストール
curl -fsSL https://raw.githubusercontent.com/claude-world/director-mode-lite/main/install.sh | bash -s .

# skill のセキュリティスキャン
npx claude-skill-antivirus scan <skill-name>

# MCP でトレンドトピックを取得
pip install "trend-pulse[mcp]"
trend-pulse trending --geo TW --count 10
```

---

## コミュニティ

<div align="center">

[**claude-world.com**](https://claude-world.com) &nbsp;•&nbsp;
[**Discord**](https://discord.com/invite/rBtHzSD288) &nbsp;•&nbsp;
[**GitHub Issues**](https://github.com/claude-world/director-mode-lite/issues)

[Claude World Taiwan](https://claude-world.com) 製 🇹🇼

</div>
