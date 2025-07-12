# 🏋️ Training Log

けんさんのパワーリフティング練習記録を管理するためのリポジトリです。

## 📁 ディレクトリ構成

```text
training-log/
├── logs/ ← トレーニング記録（JSONファイル）
│ ├── 2025-07-12.json
│ ├── 2025-07-17.json
│ └── ...
├── .github/
│ └── workflows/
│ └── update-from-issue.yml ← GitHub Actions（後で追加）
├── viewer/ ← GitHub Pages用ビューワ（後で追加）
└── README.md ← このファイル

```
## 📝 記録方法（iPhoneで完結）

1. ChatGPTに「今日の練習をJSONで出して」と言う
2. 出力されたJSONをGitHub公式アプリで Issue に貼り付け
3. Issueに `training-log` ラベルをつけて投稿
4. GitHub Actionsが自動で `logs/` フォルダにJSONを保存します

## 👀 表示方法

今後、GitHub Pages または外部Viewer（Vercel等）で記録を可視化できるようにします。

---

### 📌 備考
- このリポジトリは非公開（プライベート）で運用します
- 表示対象はけんさん本人と弟さんのみ
