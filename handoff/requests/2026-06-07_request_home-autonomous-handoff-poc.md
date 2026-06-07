# Claude Code 実行依頼

作成日: 2026-06-07
ステータス: approved
実行レベル: local-only

## 目的

CodexからClaude Codeを直接起動し、人間の手動連携なしで、依頼読解・確認・結果記録・現在地更新まで完走できるか検証する。

## 今回やること

1. `CLAUDE.md`、`project/project-guidelines.md`、`handoff/project-status.md`、この依頼書を読む。
2. `git status`と`git diff`で、現在の未コミット変更を確認する。
3. 現在の変更が、直前の運用状態整合PoCと開始・終了チェック追加の内容として妥当かレビューする。
4. 意図しない変更、秘密情報、公開前に問題となる内容がないか確認する。
5. `handoff/project-status.md`へ、次の状態を反映する。
   - 独自ドメインのDNSレコードとネームサーバー設定が完了し、HTTPS証明書の準備待ちであること。
   - CodexからClaude Codeを直接起動する自動連携PoCを実施したこと。
6. 結果を`handoff/results/2026-06-07_result_home-autonomous-handoff-poc.md`へ保存する。

## 今回やらないこと

- Webサイト本文・デザイン変更。
- Git fetch、pull、commit、push。
- GitHub Pages・DNS・外部サービスの設定変更。
- ファイル削除、履歴書き換え。
- プロジェクト外へのアクセス。

## 編集可能な範囲

- `handoff/project-status.md`
- `handoff/results/2026-06-07_result_home-autonomous-handoff-poc.md`

## 完了条件

- 現在の変更内容がレビューされている。
- 問題・注意点・commit可能性が結果へ記録されている。
- `handoff/project-status.md`が現在の状態へ更新されている。
- commit、push、外部変更を行っていない。

## 人間が判断すること

- CodexからClaude Codeを直接起動する連携を、今後の標準運用候補にするか。
- 現在の変更をcommit・pushするか。
