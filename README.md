# RRYZ09.github.io

RRYZ09 の個人サイト(自己紹介・経歴)。GitHub Pages ユーザーサイト。

## 公開手順(ありさん操作)

1. GitHub で **RRYZ09** アカウントにログインし、新規リポジトリ `RRYZ09.github.io`(public)を作成
2. このローカルリポジトリから push:
   ```bash
   cd ~/work/rryz09_github_io
   git remote add origin git@github.com:RRYZ09/RRYZ09.github.io.git
   git push -u origin main
   ```
   (rryz鍵での認証。Claudeに頼んでもOK)
3. リポジトリの Settings → Pages → Source が `main` / root になっていることを確認
4. 数分後に https://rryz09.github.io/ で公開される

## 編集メモ

- `index.html` の Career セクションに `TODO: ありさん記入` コメントあり(学歴・職歴・登壇歴)
- 外部CDN・Webフォントは使っていない(素のHTML+CSSのみ)
- ダークモード対応(OS設定に追従)
