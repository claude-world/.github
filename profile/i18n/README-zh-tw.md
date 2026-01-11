<div align="center">

# Director Mode for Claude Code

**不要寫程式碼，指揮 Claude 幫你寫。**

<a href="../README.md">English</a> • 繁體中文 • <a href="README-ja.md">日本語</a>

<br/>

[![網站](https://img.shields.io/badge/網站-claude--world.com-blue?style=flat-square)](https://claude-world.com)
[![Discord](https://img.shields.io/badge/Discord-加入社群-7289da?style=flat-square&logo=discord&logoColor=white)](https://discord.com/invite/rBtHzSD288)
[![授權](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![Stars](https://img.shields.io/github/stars/claude-world/director-mode-lite?style=flat-square)](https://github.com/claude-world/director-mode-lite/stargazers)

</div>

---

## 簡介

**總監模式**改變你與 Claude Code 的協作方式。不再一行行寫程式，而是定義願景，讓 Claude 自主執行。

<table><tr><td width="50%">

**傳統 AI 寫作**
```
你：幫我寫一個函數
AI：這是函數
你：加上錯誤處理
AI：這是更新後的程式
你：寫測試
AI：這是測試
...重複好幾小時
```

</td><td width="50%">

**總監模式**
```
你：建立一個 REST API，
   包含認證、測試、文件

AI：分析 → 規劃 → 實作
    → 測試 → 文件 → 完成

✓ 完整、測試、文件完備
```

</td></tr></table>

---

## 🚀 Director Mode Lite

Claude Code 的免費開源工具包，具備 **TDD 自動循環**，持續執行直到所有驗收標準達成。

```bash
/auto-loop "建立 Todo 模組，包含 add、remove、toggle 功能和單元測試"

# Claude 自動迭代：
# RED   → 寫失敗測試
# GREEN → 讓測試通過
# REFACTOR → 重構程式碼
# → 重複直到所有條件達成 ✓
```

### 包含內容

| 組件 | 數量 | 說明 |
|-----|-----|-----|
| **指令** | 13 | `/auto-loop`, `/workflow`, `/focus-problem` 等 |
| **Agents** | 3 | code-reviewer, debugger, doc-writer |
| **Skills** | 4 | 專業技能模組 |

---

## 📦 快速安裝

```bash
/plugin marketplace add claude-world/director-mode-lite
```

或使用 curl：

```bash
curl -fsSL https://raw.githubusercontent.com/claude-world/director-mode-lite/main/install.sh | bash -s .
```

---

## 🛠️ 指令列表

| 指令 | 說明 |
|-----|------|
| `/auto-loop` | TDD 自動開發（持續執行直到完成）|
| `/workflow` | 5 步驟流程：聚焦 → 防止過度開發 → 測試 → 文件 → 提交 |
| `/focus-problem` | 寫作前深入分析 |
| `/test-first` | TDD 循環（紅-綠-重構）|
| `/smart-commit` | 自動產生 conventional commits |
| `/plan` | 用 TodoWrite 分解任務 |

[查看全部 13 個指令](https://github.com/claude-world/director-mode-lite#commands)

---

## 📚 專案

<table><tr><td width="50%">

**[Director Mode Lite](https://github.com/claude-world/director-mode-lite)**

Claude Code 完整工具包
- 13 個指令
- 3 個 Agents
- 4 個 Skills
- Auto-Loop

</td><td width="50%">

**[範例](https://github.com/claude-world/director-mode-lite/tree/main/examples)**

實作教學
- 計算機（5 分鐘）
- REST API（15 分鐘）

</td></tr></table>

---

## 🌐 社群

<div align="center">

[**網站**](https://claude-world.com) &nbsp;•&nbsp;
[**Discord**](https://discord.com/invite/rBtHzSD288) &nbsp;•&nbsp;
[**GitHub Issues**](https://github.com/claude-world/director-mode-lite/issues)

</div>

---

<div align="center">

由 [Claude World Taiwan](https://claude-world.com) 構建 🇹🇼

</div>
