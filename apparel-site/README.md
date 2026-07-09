# apparel-site

アパレルショップの紹介サイト（静的サイト・HTML/CSS）。

## ファイル構成
- `index.html` … ページ本体（ヒーロー・商品一覧・About・Contact）
- `styles.css` … 見た目（色・レイアウト・スマホ対応）

## 編集の仕方
1. `index.html` の `BRAND NAME` を自分のブランド名に置換
2. 商品は `<article class="card">…</article>` が1商品。増やす時はこのかたまりをコピペ
3. 商品画像は `card-img` の `background` を、画像を使うなら `<img src="画像ファイル">` に差し替え
4. Instagram / メールのリンクを自分のものに変更

## ローカルで確認
`index.html` をブラウザにドラッグ＆ドロップするだけで表示できる。

## 公開（GitHub Pages・無料）
1. このリポジトリを **Public** にする
2. GitHub の Settings → Pages → Branch を `main` / `/root` に設定
3. 数分後、`https://<ユーザー名>.github.io/apparel-site/` で公開される
