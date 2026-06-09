# Web公開用ファイル

このフォルダは静的ホスティングへアップロードできます。PDFを含めています。

## 確認

```powershell
python -m http.server 8080 -d public_site
```

ブラウザで次を開きます。

```text
http://127.0.0.1:8080/
```

## 公開方法

- Netlify Drop: `public_site.zip` をアップロード
- GitHub Pages: `public_site` の中身をリポジトリ直下へ置き、Pages の公開元を `main` / root に設定
- 一般的なレンタルサーバー: `public_site` の中身を公開ディレクトリへアップロード

## 注意

- 公開版ではローカルZoteroへの直接追加は使えません。`RIS保存` で取り込み用ファイルを保存できます。
- 元PDF、ページ画像、翻訳本文を一般公開する前に、論文ごとの著作権と配布条件を確認してください。
