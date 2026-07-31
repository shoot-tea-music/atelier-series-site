# ATELIER SERIES Website v1.0

静的HTML/CSS/JavaScriptで作成した、GitHub + Vercel向けのブランドサイトです。

## ローカル確認

`index.html` をブラウザで開くか、簡易サーバーを起動します。

```bash
python -m http.server 8000
```

その後 `http://localhost:8000` を開きます。

## Vercel公開

1. このフォルダの中身を新しいGitHubリポジトリへアップロード
2. Vercelで `Add New > Project`
3. GitHubリポジトリを選択
4. Framework Preset は `Other`
5. Build Command / Output Directory は空欄のままDeploy

## 公開前に変更する箇所

- `index.html` の `COMING SOON` を販売ページURLへ変更
- `mailto:` の連絡先を正式な問い合わせ先へ変更
- FAQの利用規約を確定内容に合わせて調整
- BASEの商品価格・販売URLを設定後、CTAへ反映

## 使用画像

`assets/post-01.png` から `post-06.png` はClassic Edition完成版です。
