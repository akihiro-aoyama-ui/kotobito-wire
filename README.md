# Kotobito サイトワイヤー (wire-v2)

新サイト構成のワイヤーフレーム一式。`index.html` がトップ。
グレースケールのワイヤー表現で、各ページはプレースホルダ中心。

## ページ構成
- index.html … TOP（KV / News / Approach / 事例 / 事業 / わたしたち / Contact）
- news.html / news-detail.html … News 一覧・リリース文
- works.html / case.html … プロデュース事例 全体像・個別事例
- output.html / interview.html … アウトプット・インタビュー
- business.html … 事業（プロデュース事業・自社事業＋全体像図）
- about.html … わたしたちについて（哲学・代表・メンバー・会社概要）
- member.html … メンバー詳細
- policy.html … プライバシーポリシー等
- style.css … 共通スタイル

## GitHub Pages で先方に共有する手順

1. GitHub で新規リポジトリを作成（例: `kotobito-wire`）。
2. このフォルダで以下を実行（リモートURLは作成したリポジトリのもの）:
   ```
   git remote add origin https://github.com/<アカウント>/kotobito-wire.git
   git push -u origin main
   ```
3. リポジトリの Settings → Pages → Build and deployment:
   - Source: `Deploy from a branch`
   - Branch: `main` / フォルダ `/(root)` を選択して Save
4. 数分後、`https://<アカウント>.github.io/kotobito-wire/` で公開されます。
   このURLを先方に共有してください。

※ プライベートに見せたい場合は、Private リポジトリ＋GitHub の限定共有や、
   Netlify/Vercel のプレビューURL（ドラッグ＆ドロップ）も利用できます。
