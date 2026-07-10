# AI練習メニュー（Phase 1）/ AI Practice Menu

中学英語の授業向けに、**制約付きのAI練習プロンプト**を配る単一ファイルのWebツールです。
「手放しラダー」= ①知識 → ②思考 → ③議論 → ④探求 → ⑤フリーパス の5モードに沿って、
各段階のプロンプトを生成し、AI（Google AIモード等）に貼り付けて練習します。

A single-file web tool that hands students **constrained AI-practice prompts** for
English class, along a five-mode "relinquishment ladder"
(① Knowledge → ② Thinking → ③ Discussion → ④ Inquiry → ⑤ Free-pass).

**公開URL / Live:** https://kenjiintasmania.github.io/ai-practice-menu/

## 使い方 / How to use
1. ページを開く。
2. いまのレベルの目安を選ぶ（学習記録が無ければ「手動でレベルを選ぶ」でOK）。
3. モードの「📋コピーしてAIを開く」でプロンプトを貼り付けて練習する。
4. AIに「まとめ」と言うと記録用の項目が出る → 貼り付けて「送信」。

## ファイル / Files
- `index.html` — ツール本体（バニラJS・単一ファイル・外部依存なし）。
- `log_gas.gs` — 送信を受ける Google Apps Script の**参照コード**（正規表現なし）。
  デプロイして得た `/exec` URL を `index.html` の `LOG_GAS_URL` に貼る。

## プライバシー / Privacy
- 収集は学習方略の記録が目的。氏名欄は**任意**。
- 収集先スプレッドシートのIDや個人データは**本リポジトリに含みません**。
- 教育現場で運用する際は、各校の同意・個人情報の方針に従ってください。

## ステータス / Status
Phase 1（プロトタイプ / R&D）。仕様は変わることがあります。
