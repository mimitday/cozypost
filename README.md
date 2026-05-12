# CozyPost LP / PWA

## ファイル
- `index.html`：LP
- `app.html`：PWA本体
- `manifest.webmanifest`：PWA設定
- `sw.js`：オフライン用 Service Worker
- `assets/icon-192.png` / `assets/icon-512.png`：仮アイコン

## ロゴ差し替え
LP左上は現在テキストで `CozyPost` と入れています。
画像ロゴにする場合は、`index.html` の以下を差し替えてください。

```html
<div class="brand">CozyPost</div>
```

例：
```html
<div class="brand"><img src="assets/logo.png" alt="CozyPost"></div>
```

その場合は `assets/logo.png` を追加してください。

## GitHub Pages
このフォルダの中身をリポジトリ直下に置いて、GitHub Pages を有効化すれば公開できます。
