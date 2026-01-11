<div align="center">

# Director Mode for Claude Code

**コードを書くな、Claude に指示を出せ。**

<a href="../README.md">English</a> • <a href="README-zh-tw.md">繁體中文</a> • 日本語

<br/>

[![ウェブサイト](https://img.shields.io/badge/ウェブサイト-claude--world.com-blue?style=flat-square)](https://claude-world.com)
[![Discord](https://img.shields.io/badge/Discord-参加-7289da?style=flat-square&logo=discord&logoColor=white)](https://discord.com/invite/rBtHzSD288)
[![ライセンス](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![Stars](https://img.shields.io/github/stars/claude-world/director-mode-lite?style=flat-square)](https://github.com/claude-world/director-mode-lite/stargazers)

</div>

---

## 紹介

**ディレクターモード**は、Claude Code との協業を変革します。コードを1行ずつ書くのではなく、ビジョンを定義して Claude に自律実行させます。

<table><tr><td width="50%">

**従来の AI コーディング**
```
あなた：関数を書いて
AI：関数です
あなた：エラー処理を追加
AI：更新されたコード
あなた：テストを書いて
AI：テストです
...数時間繰り返し
```

</td><td width="50%">

**ディレクターモード**
```
あなた：REST API を構築して、
   認証、テスト、文書も

AI：分析 → 計画 → 実装
    → テスト → 文書 → 完了

✓ 完成品、テスト完了、文書完備
```

</td></tr></table>

---

## 🚀 Director Mode Lite

Claude Code の無料オープンソースツールキット。**TDD ベースの自動ループ**により、すべての受け入れ基準が満たされるまで実行し続けます。

```bash
/auto-loop "Todo モジュールを作成。add、remove、toggle 機能と単体テストを含む"

# Claude が自動的に反復：
# RED   → 失敗するテストを書く
# GREEN → テストを通す
# REFACTOR → コードをクリーンアップ
# → すべての基準が満たされるまで繰り返す ✓
```

### 含まれるもの

| コンポーネント | 数量 | 説明 |
|--------------|------|------|
| **コマンド** | 13 | `/auto-loop`, `/workflow`, `/focus-problem` など |
| **Agents** | 3 | code-reviewer, debugger, doc-writer |
| **Skills** | 4 | 専門スキルモジュール |

---

## 📦 クイックインストール

```bash
/plugin marketplace add claude-world/director-mode-lite
```

または curl：

```bash
curl -fsSL https://raw.githubusercontent.com/claude-world/director-mode-lite/main/install.sh | bash -s .
```

---

## 🛠️ コマンド

| コマンド | 説明 |
|---------|------|
| `/auto-loop` | TDD 自動開発（完了まで実行）|
| `/workflow` | 5ステップ：フォーカス → 過剰開発防止 → テスト → 文書 → コミット |
| `/focus-problem` | コーディング前の深い分析 |
| `/test-first` | TDD サイクル（レッド-グリーン-リファクタリング）|
| `/smart-commit` | Conventional Commits を自動生成 |
| `/plan` | TodoWrite でタスク分解 |

[全 13 コマンドを見る](https://github.com/claude-world/director-mode-lite#commands)

---

## 📚 プロジェクト

<table><tr><td width="50%">

**[Director Mode Lite](https://github.com/claude-world/director-mode-lite)**

Claude Code 完全ツールキット
- 13 コマンド
- 3 Agents
- 4 Skills
- Auto-Loop

</td><td width="50%">

**[例](https://github.com/claude-world/director-mode-lite/tree/main/examples)**

実践チュートリアル
- 計算機（5分）
- REST API（15分）

</td></tr></table>

---

## 🌐 コミュニティ

<div align="center">

[**ウェブサイト**](https://claude-world.com) &nbsp;•&nbsp;
[**Discord**](https://discord.com/invite/rBtHzSD288) &nbsp;•&nbsp;
[**GitHub Issues**](https://github.com/claude-world/director-mode-lite/issues)

</div>

---

<div align="center">

By [Claude World Taiwan](https://claude-world.com) 🇹🇼

</div>
