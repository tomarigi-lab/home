# 作業結果: Instagramリンク追加

実施日: 2026-06-07
依頼書: `handoff/requests/2026-06-07_request_home-instagram-link.md`

## 実施内容

### 1. `docs/index.html`

フッター内にInstagramリンクを追加。コピーライト行の直上に配置。

```html
<nav class="footer-links">
  <a class="footer-link" href="https://www.instagram.com/tomarigi_lab/" target="_blank" rel="noopener noreferrer">Instagram</a>
</nav>
```

- URL: `https://www.instagram.com/tomarigi_lab/`（共有用パラメータなし）
- `target="_blank"` + `rel="noopener noreferrer"` を設定
- コピーライト `© 2026 tomarigi_lab` は変更なし

### 2. `docs/style.css`

`.footer-links` と `.footer-link` のスタイルを追加。サイトの既存トーンに合わせ、文字色・サイズ・letter-spacingを揃えた。

### 3. `handoff/project-status.md`

Instagramリンク追加の状態を反映し、未決事項・次の候補を更新。

## 完了確認

- [x] 正式URLへのInstagramリンクが追加されている
- [x] 共有用パラメータ（`igsh`、`utm_source`等）が含まれていない
- [x] コピーライトが `© 2026 tomarigi_lab` のまま
- [x] `rel="noopener noreferrer"` が設定されている
- [x] commit、push、公開を行っていない
