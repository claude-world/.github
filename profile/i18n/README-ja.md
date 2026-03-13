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

### 開発ツールキット

| プロジェクト | Stars | 説明 |
|------------|-------|------|
| **[director-mode-lite](https://github.com/claude-world/director-mode-lite)** | ![Stars](https://img.shields.io/github/stars/claude-world/director-mode-lite?style=flat-square) | コードを書くな — Claude に指示を出せ。25 commands、14 agents、29 skills + TDD Auto-Loop。 |
| **[claude-world-examples](https://github.com/claude-world/claude-world-examples)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-world-examples?style=flat-square) | Claude Code と Director Mode の実践例とベストプラクティス。 |

### セキュリティ

| プロジェクト | Stars | 説明 |
|------------|-------|------|
| **[claude-skill-antivirus](https://github.com/claude-world/claude-skill-antivirus)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-skill-antivirus?style=flat-square) | Claude Code Skills セキュリティスキャナー — 9 エンジンで 71K+ skills の悪意パターンを検出。 |

### MCP サーバー

| プロジェクト | Stars | 説明 |
|------------|-------|------|
| **[cf-browser](https://github.com/claude-world/cf-browser)** | ![Stars](https://img.shields.io/github/stars/claude-world/cf-browser?style=flat-square) | Cloudflare Browser Rendering プロキシ — 9 MCP ツール（スクリーンショット、PDF、Markdown、クロール）。 |
| **[trend-pulse](https://github.com/claude-world/trend-pulse)** | ![Stars](https://img.shields.io/github/stars/claude-world/trend-pulse?style=flat-square) | 無料トレンドアグリゲーター — 15 ソース、認証不要。CLI + Python + MCP Server。 |
| **[mcp-director-mode-server](https://github.com/claude-world/mcp-director-mode-server)** | ![Stars](https://img.shields.io/github/stars/claude-world/mcp-director-mode-server?style=flat-square) | Director Mode 学習用 MCP Server — TDD、Auto-Cycle、SpecKit デモ。 |

### ユーティリティ

| プロジェクト | Stars | 説明 |
|------------|-------|------|
| **[skills-optimizer](https://github.com/claude-world/skills-optimizer)** | ![Stars](https://img.shields.io/github/stars/claude-world/skills-optimizer?style=flat-square) | Claude Code agents & skills を圧縮 — 6:1 圧縮率、セマンティック検証。 |
| **[skill-universal](https://github.com/claude-world/skill-universal)** | ![Stars](https://img.shields.io/github/stars/claude-world/skill-universal?style=flat-square) | Skill を一度書いてどこでも実行 — Claude Code、Agent SDK、OpenClaw。 |
| **[claude-code-rfcs](https://github.com/claude-world/claude-code-rfcs)** | ![Stars](https://img.shields.io/github/stars/claude-world/claude-code-rfcs?style=flat-square) | コミュニティ主導の Claude Code アーキテクチャ提案。 |

---

## クイックスタート

```bash
# Director Mode Lite をインストール
curl -fsSL https://raw.githubusercontent.com/claude-world/director-mode-lite/main/install.sh | bash -s .

# skill のセキュリティスキャン
npx claude-skill-antivirus scan <skill-name>

# MCP でトレンドトピックを取得
npx trend-pulse trending --geo TW --count 10
```

---

## コミュニティ

<div align="center">

[**claude-world.com**](https://claude-world.com) &nbsp;•&nbsp;
[**Discord**](https://discord.com/invite/rBtHzSD288) &nbsp;•&nbsp;
[**GitHub Issues**](https://github.com/claude-world/director-mode-lite/issues)

[Claude World Taiwan](https://claude-world.com) 製 🇹🇼

</div>
