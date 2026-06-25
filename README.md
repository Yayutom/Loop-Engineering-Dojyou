# Loop Engineering 道場 🥋

手を動かして学ぶ **エージェントのループ設計（Loop Engineering）** の伴走型学習サイト（日本語・初心者向け・2026年6月版）。

> 2026年、AIの腕前は「プロンプトの言い回し」では決まらなくなりました。決め手は **ループ設計** —— エージェントが何をきっかけに動き、どう繰り返し、何を「合格」とし、いつ止まるか。

## 🌐 公開（GitHub Pages）

リポジトリの **Settings → Pages → Source: `Deploy from a branch` → Branch: `main` / `(root)`** を選ぶと、`index.html` がそのまま公開されます。

## 📚 学べること

| # | モジュール | 内容 |
|---|---|---|
| 1 | なぜ今ループ設計か | プロンプト1往復 → AIが自分で回すループへ |
| 2 | ループの解剖学 | きっかけ→計画→行動→観測→検証→停止（クリックで解説） |
| 3 | 4つの設計要素 | Trigger / Topology / Verifier / Stop |
| 4 | ハンズオン① | ループ実行シミュレータ（検証なしの偽完了を体感） |
| 5 | ハンズオン② | Verifier 道場（機械判定できる検証器を選ぶ） |
| 6 | 組み立て演習 | ドラッグでループの1周を並べ替え＆採点 |
| 7 | 擬似コード | 4要素入りの最小ループを書いてトレース実行 |
| 8 | 実務プレイブック | 失敗→処方の早見表・離陸前チェックリスト |
| ★ | 理解度クイズ | 全5問・即採点＆解説 |

進捗・チェック・クイズの記録はブラウザの `localStorage` に保存されます。

## 🗂 構成

- `index.html` — 単一ファイル完結（CSS/JSインライン、依存なし）

## 📖 出典

- [Agentic Loops: From ReAct to Loop Engineering (2026)](https://datasciencedojo.com/blog/agentic-loops-explained-from-react-to-loop-engineering-2026-guide/)
- [Loop Engineering — Requesty](https://www.requesty.ai/blog/loop-engineering-how-to-build-ai-agent-loops-that-run-themselves)
- [What Is Loop Engineering? — explainx.ai](https://explainx.ai/blog/what-is-loop-engineering-ai-agents-2026)
- [Context Engineering for Coding Agents — martinfowler.com](https://martinfowler.com/articles/exploring-gen-ai/context-engineering-coding-agents.html)

---

🤖 Generated with [Claude Code](https://claude.com/claude-code)
