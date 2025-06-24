<!--
<<< 著者注: ステップ 2 >>>
前のステップを理解した上で、このステップを開始してください。
用語を定義し、docs.github.com へのリンクを貼ってください。
-->

## ステップ 2: マージコンフリクトの解決

_順調なスタートです！次は、マージコンフリクトについて詳しく見ていきましょう！ :mag:_

少し難しそうに感じるかもしれませんが、ご安心ください。Git はマージに関して賢く機能します！Git に必要なのは、人間が [競合の解決方法](https://docs.github.com/ja/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-using-the-command-line) を決定することだけです。場合によっては、マージコンフリクトを解決する最善の方法は、両方のブランチからコンテンツを追加すること、あるいはどちらのブランチにも存在しないコンテンツを追加することです。そのため、Git では人間がコードを確認し、適切な修正を行う必要があります。

![Merge conflict](https://github.com/kuboctopus/resolve-merge-conflicts/blob/main/images/merge_conflict.jpg)
![Resolve merge conflict](https://github.com/kuboctopus/resolve-merge-conflicts/blob/main/images/resolve_merge_conflict.jpg)

### :keyboard: アクティビティ: マージコンフリクトの解決

1. 先ほど作成したプルリクエストを開きます。競合は自動的に作成されています。ご安心ください！
1. ページの下部にある「このブランチには解決すべき競合があります」の下にある「**競合を解決**」ボタンをクリックします。
1. `<<<<<<< my-resume` で始まり、`>>>>>>> main` で終わるハイライト表示されたセクションを探します。これらのマーカーは、競合しているコンテンツを示すために Git によって追加されます。
1. `=======` より下と `>>>>>>> main` より上のすべてのコンテンツを削除して、メインブランチに加えられた変更を削除します。
1. 次に、以下の行を削除してマージコンフリクトマーカーを削除します。
```
<<<<<<< my-resume
=======
>>>>>>> main
```
1. マージコンフリクトマーカーを削除したら、「**解決済みとしてマーク**」をクリックします。
1. 最後に、「**マージをコミット**」をクリックします。
1. 約20秒待ってから、このページ（手順を実行しているページ）を更新します。[GitHub Actions](https://docs.github.com/en/actions) が自動的に次のステップに更新されます。
