# 社長の画角 LP — Vercel デプロイ

静的サイト。ビルド不要。

## 構成
```
index.html      ← LP本体（Metaピクセル埋め込み済み）
support.js
image-slot.js
videos/
  template-1.mp4
  template-2.mp4
  template-3.mp4
vercel.json
```

## 注意
index.html はリポジトリの**一番上の階層**に置くこと。
フォルダの中に入れると Vercel が 404 を返します。
