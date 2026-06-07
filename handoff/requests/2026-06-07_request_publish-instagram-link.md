# Claude Code 実行依頼

作成日: 2026-06-07
ステータス: approved
実行レベル: commit-and-push-approved

## 目的

確認済みのInstagramリンクとコピーライト変更を公開する。

## 人間の承認

- 人間がMacBookでローカル表示を確認済み。
- Instagramリンクから正しいプロフィールへ移動できることを確認済み。
- スマホから今回の実行を承認済み。
- 今回に限り、指定範囲のcommitと`origin/main`へのpushを許可する。

## 今回やること

1. 必読ファイル、依頼書、`git status`、`git diff`を確認する。
2. 次を最終確認する。
   - Instagram URLが`https://www.instagram.com/tomarigi_lab/`
   - 共有用パラメータが含まれていない。
   - コピーライトが`© 2026 tomarigi_lab`
   - 作品、タイトル、文章が意図せず変更されていない。
3. 次のファイルだけをcommit対象にする。
   - `docs/index.html`
   - `docs/style.css`
   - `handoff/project-status.md`
   - `handoff/requests/2026-06-07_request_home-copyright-name.md`
   - `handoff/requests/2026-06-07_request_home-instagram-link.md`
   - `handoff/requests/2026-06-07_request_publish-instagram-link.md`
   - `handoff/results/2026-06-07_result_home-copyright-name.md`
   - `handoff/results/2026-06-07_result_home-instagram-link.md`
   - `handoff/results/2026-06-07_result_publish-first-artwork.md`
4. `docs/images/arigatou.png`はcommit対象に含めない。
5. commit後、`origin/main`へpushする。
6. push後、結果を`handoff/results/2026-06-07_result_publish-instagram-link.md`へ保存し、`handoff/project-status.md`を更新する。

## 今回やらないこと

- 作品、タイトル、文章の変更。
- `docs/images/arigatou.png`の削除・commit。
- GitHub Pages・DNS・Instagramなど外部サービス設定の変更。
- 指定外ファイルのcommit。
- 履歴書き換え、force push。

## 完了条件

- Instagramリンクとコピーライト変更がcommit・pushされている。
- 元PNGがcommitされていない。
- push後の結果と現在地が記録されている。
