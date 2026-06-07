# Claude Code 実行依頼

作成日: 2026-06-07
ステータス: approved
実行レベル: local-only

## 目的

ホームページから`tomarigi_lab`のInstagramへ移動できる、小さく自然な導線を追加する。

## Instagram正式URL

```text
https://www.instagram.com/tomarigi_lab/
```

共有用URLに含まれる`igsh`や`utm_source`などのパラメータは使用しない。

## 今回やること

1. `docs/index.html`へInstagramリンクを追加する。
2. リンク文言は`Instagram`とする。
3. 現在の「一枚の絵と言葉を、ゆっくりと。」という静かな世界観を壊さない、小さく自然な配置にする。
4. 新しいタブで開く場合は、安全な`rel`属性を設定する。
5. `docs/style.css`へ必要最小限のリンクスタイルを追加する。
6. コピーライト`© 2026 tomarigi_lab`が維持されていることを確認する。
7. `handoff/project-status.md`を更新する。
8. 結果を`handoff/results/2026-06-07_result_home-instagram-link.md`へ保存する。

## 今回やらないこと

- Instagramプロフィールや投稿内容の変更。
- noteリンク、他のSNSリンク、問い合わせフォームの追加。
- サイト構成・作品・文章の大幅変更。
- commit、push、公開。
- 外部サービス・プロジェクト外へのアクセス。

## 編集可能な範囲

- `docs/index.html`
- `docs/style.css`
- `handoff/project-status.md`
- `handoff/results/2026-06-07_result_home-instagram-link.md`

## 完了条件

- 正式URLへのInstagramリンクが追加されている。
- 共有用パラメータが含まれていない。
- コピーライトが`© 2026 tomarigi_lab`のまま。
- commit、push、公開を行っていない。
