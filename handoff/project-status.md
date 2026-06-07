# Project Status

最終更新: 2026-06-07

## 目的

とまり木の正式ホームページを、小さく作りながら育てる。

## 現在地

- 作品「ありがとう」を掲載した一枚作品ページを commit・push 済み（commit: 5163f25）。
- GitHub Pages で公開中（`main` ブランチの `/docs` フォルダ、独自ドメイン `tomarigi-lab.com`）。
- 画像は軽量 JPEG（`arigatou.jpg`、197KB）を参照。元 PNG（6MB）はローカルのみに残存・未コミット。
- 表示名は「とまり木」、補足表記は `tomarigi_lab`。
- コピーライト表記を `© 2026 tomarigi_lab` へ変更済み・commit・push 済み。
- フッターに Instagram リンク（`https://www.instagram.com/tomarigi_lab/`）を追加済み・commit・push 済み。
- DNS レコード（A/CNAME）とネームサーバー設定は完了済み。HTTPS 証明書は GitHub Pages 側で準備中（反映待ち）。
- CodexからClaude Codeを直接起動する自律連携PoC（依頼読解〜結果記録まで）を 2026-06-07 に実施済み。
- `project/project-guidelines.md` へ、作業開始時・終了時チェックリストを追加済み。

## docs/ 構成

```
docs/
├─ index.html      一枚作品ページ（「ありがとう」掲載済み）
├─ style.css       スタイル
├─ CNAME           tomarigi-lab.com
└─ images/
   └─ arigatou.jpg 作品「ありがとう」（軽量JPEG・公開中）
```

ローカルのみ:
- `docs/images/arigatou.png`（元 PNG・未コミット）

## 次の候補

- ブラウザで `https://tomarigi-lab.com` へアクセスし、Instagramリンク・コピーライト変更・HTTPS証明書の有効化を確認する（人間）。
- CodexからClaude Codeを直接起動する連携を標準運用候補とするか判断する（人間）。

## 未決事項

- HTTPS 証明書の有効化確認（人間がブラウザで `https://tomarigi-lab.com` へアクセスして確認）。
- Codex → Claude Code 自律連携を標準運用候補にするか（今回の PoC 結果を踏まえて人間が判断）。

## 安全上の注意

- Git push、公開、削除、履歴書き換え、外部送信は、人間の明示的な許可なしに実行しない。
