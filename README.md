# takxlz-dist

配布物の置き場。ファイルは置かず、release の asset だけを使う。
元のリポジトリは private で、ここにはログインなしで取れる形で置く。

release は元リポジトリごとに固定のタグを持ち、更新のたびに作り直す。
取得は `https://github.com/takxlz/takxlz-dist/releases/download/<タグ>/<asset>` の固定 URL から。
版は release の題名と notes（元のコミット）で分かる。

| タグ              | 元リポジトリ                                                        | asset                                               |
| ----------------- | ------------------------------------------------------------------- | --------------------------------------------------- |
| `dotfiles-agents` | [takxlz/dotfiles-agents](https://github.com/takxlz/dotfiles-agents) | `dotfiles-agents.zip`、`update-dotfiles-agents.bat` |

release は各元リポジトリでコミットしたあと、手元から publish-release スキルで作る（自動では作らない）。
