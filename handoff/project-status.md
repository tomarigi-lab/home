# Project Status

最終更新: 2026-06-07

## 目的

とまり木の正式ホームページを、小さく作りながら育てる。

## 現在地

- `docs/index.html` と `docs/style.css` を、一枚の作品と短い言葉が主役のページへ試作済み（ローカルのみ・未公開）。
- 最初の作品「ありがとう」（`docs/images/arigatou.png`）・タイトル・文章をHTMLに反映済み（ローカルのみ・未コミット）。
- 仮表示（プレースホルダー・「準備中」テキスト）はすべて削除済み。
- 画像は縦横比を保ったまま切り抜かずに全体表示（`height: auto`）するよう CSS 調整済み。
- 表示名は「とまり木」、補足表記は `tomarigi_lab`。
- GitHub Pages 公開済み（`main` ブランチの `/docs` フォルダ）。公開中のリモートはまだ旧来の準備中ページ。
- 独自ドメイン `tomarigi-lab.com` を取得・設定済み。
- `docs/CNAME` に `tomarigi-lab.com` が記載されており、GitHub がリモートへ作成した。
- ローカルとリモートは `bb206c9`（Create CNAME）で同期済み（今回の作業はまだ未コミット）。
- DNS レコード（A/CNAME）とネームサーバー設定は完了済み。HTTPS 証明書は GitHub Pages 側で準備中（反映待ち）。
- CodexからClaude Codeを直接起動する自律連携PoC（依頼読解〜結果記録まで）を 2026-06-07 に実施済み。
- `project/project-guidelines.md` へ、作業開始時・終了時チェックリストを追加済み。
- 作品「ありがとう」に添える文章を公開可能な内容へ差し替え済み（ローカルのみ・未コミット）。

## docs/ 構成

```
docs/
├─ index.html      一枚サイト本体
├─ style.css       スタイル
├─ CNAME           tomarigi-lab.com
└─ images/
   └─ arigatou.png 作品「ありがとう」
```

## 次の候補

- ブラウザで `docs/index.html` をローカルで開き、作品「ありがとう」の表示を確認する。
- タイトル「ありがとう」と添え文章を採用するか判断する（人間）。
- 表示に問題なければ commit → push → 公開（人間が判断）。
- ブラウザで `https://tomarigi-lab.com` へアクセスし、HTTPS 証明書の有効化と DNS 反映を確認する。
- Instagramリンクを追加する（リンクが用意でき次第）。
- CodexからClaude Codeを直接起動する連携を標準運用候補とするか判断する。

## 未決事項

- タイトル「ありがとう」を採用するか（人間がブラウザで確認して判断）。
- 差し替えた添え文章を採用するか（人間が判断）。
- ローカル確認後に commit → push → 公開するか（人間が判断）。
- HTTPS 証明書の有効化確認（人間がブラウザで `https://tomarigi-lab.com` へアクセスして確認）。
- Instagramリンクを掲載する時期。
- Codex → Claude Code 自律連携を標準運用候補にするか（今回の PoC 結果を踏まえて人間が判断）。

## 安全上の注意

- Git push、公開、削除、履歴書き換え、外部送信は、人間の明示的な許可なしに実行しない。
