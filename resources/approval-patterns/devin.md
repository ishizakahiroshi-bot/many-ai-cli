# Devin Approval Patterns

> many-ai-cli の Hub UI が Devin CLI の承認 / permission UI を検出するためのトリガー文言。
> 1 行 1 パターン。バッククオートで囲んだ部分のみをパースする。
> Devin CLI の `--permission-mode`（auto / accept-edits / smart / dangerous）に合わせ、暫定で Claude Code 系 + 汎用の文言を採用している。実機 TUI の承認プロンプトで確定する。

- `do you want to`
- `esc to cancel`
- `press enter to confirm`
- `allow this command`
- `permission required`
- `approve?`
- `proceed?`
