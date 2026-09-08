# dotfiles-agents-public

[takxlz/dotfiles-agents](https://github.com/takxlz/dotfiles-agents)（private）の配布用リポジトリ。
ファイルは置かず、release の asset だけを使う。

- `dotfiles-agents.zip` — リポジトリ全体。展開すると `dotfiles-agents/` ができる
- `update.bat` — Windows 用の取得スクリプト。最新 release の zip を取り、展開先を入れ替える

最新の release は `https://github.com/takxlz/dotfiles-agents-public/releases/latest/download/<asset>` から取れる。
release は main への push ごとに元のリポジトリの GitHub Actions が作る。
