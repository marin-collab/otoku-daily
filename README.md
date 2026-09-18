# otoku-daily

「お得情報リサーチAI」の毎朝自動更新データ置き場。

- `data/deals.json` … 表示ページが読む最新データ（クラウドルーティンが毎朝上書き）
- `data/history/` … 日別の履歴
- `public/index.html` … 表示ページ（Cloudflare Workersに配置。GitHubのdeals.jsonを読んで描画）
- `ROUTINE_PROMPT.md` … クラウドルーティンに設定しているプロンプトの原本
