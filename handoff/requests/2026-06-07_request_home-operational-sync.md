# Claude Code 実行依頼

作成日: 2026-06-07
ステータス: pending
実行レベル: approved-local-sync

## 目的

`home`プロジェクトの実態と、Claudeが次回読む現在地を一致させる。
あわせて、Claude Codeが作業開始・実行・結果記録・現在地更新まで一周できるか確認する。

## 背景

- 最小ページの作成、commit、push、GitHub Pages公開まで完了した。
- 独自ドメイン`tomarigi-lab.com`を取得し、GitHub Pagesへ設定した。
- GitHubが`docs/CNAME`をリモートへ作成した可能性がある。
- `handoff/project-status.md`と既存結果ログは、現在の実態に追いついていない。

## 作業開始時に必ず行うこと

1. `CLAUDE.md`を読む。
2. `project/project-guidelines.md`を読む。
3. `handoff/project-status.md`を読む。
4. この依頼書を読む。
5. `git status`、`git log`、リモートとの差分を確認する。

## 今回やること

1. GitHubの`main`とローカル`main`の差分を確認する。
2. ローカルに未変更がなく、fast-forward可能な場合だけ、リモートの変更をローカルへ同期する。
3. `docs/CNAME`と現在の公開構成を確認する。
4. `handoff/project-status.md`を、現在の実態へ更新する。
5. 今回の実施結果を`handoff/results/2026-06-07_result_home-operational-sync.md`へ保存する。
6. 今後の作業で状態更新漏れを防ぐため、開始時・終了時に確認すべき項目を結果へ提案する。

## 今回やらないこと

- Webサイト本文・デザインの変更。
- 新しい機能の実装。
- commit、push、GitHub Pages設定変更。
- DNS設定変更。
- ファイル削除、履歴書き換え。

## 編集可能な範囲

- `handoff/project-status.md`
- `handoff/results/2026-06-07_result_home-operational-sync.md`

リモート同期によって取得される既存ファイルは、この編集範囲の制限対象外とする。

## 同期の安全条件

- `git pull --ff-only`相当のfast-forward同期だけ許可する。
- ローカル変更、競合、分岐がある場合は同期せず、結果へ状況を記録する。
- commit、pushは行わない。

## 完了条件

- 実態と`handoff/project-status.md`が一致している。
- GitHub Pages公開済み、独自ドメイン設定済み、DNS反映待ちであることが記録されている。
- ローカルとリモートの同期結果が記録されている。
- 次回のClaudeが短い現在地から再開できる。
- 結果ファイルに、実施内容、確認結果、未決事項、次の判断が残っている。

## 人間が判断すること

- Claudeの開始時・終了時チェックを、正式なプロジェクトガイドラインへ追加するか。
- 今後、状態同期をルーティンとして扱うか。
