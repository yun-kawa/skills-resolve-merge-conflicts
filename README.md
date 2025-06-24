<header>

<!--
<<< 作成者メモ: コースヘッダー >>>
1280×640 の画像、文頭大文字で書かれたコースタイトル、そして強調された簡潔な説明を含めてください。
リポジトリ設定で、テンプレートリポジトリを有効にし、1280×640 のソーシャル画像を追加し、ヘッドブランチを自動削除してください。
オープンソースライセンスを追加してください。GitHub は MIT ライセンスを使用しています。
-->

# マージコンフリクトの解決

_競合が発生する理由と解決方法を学びましょう。_

</header>

<!--
<<< 著者注: ステップ 3 >>>
前のステップを承認することから、このステップを開始します。
用語を定義し、docs.github.com へのリンクを作成します。
-->

## ステップ 3: 独自の競合を作成する

_お疲れ様です！マージコンフリクトを解決できました！ :tada:_

競合を解決しても、GitHub でプルリクエストが自動的にマージされるわけではありません。代わりに、競合の解決結果がマージコミットに保存され、あなたとチームは作業を継続できます。競合を解決するために、GitHub は _リバースマージ_ と呼ばれる処理を実行します。これは、`main` ブランチの変更が `my-resume` ブランチにマージされることを意味します。リバースマージでは、`my-resume` ブランチのみが更新されます。これにより、`main` にマージする前に、解決済みの変更を自分のブランチでテストできます。

さあ、少し大胆なことをしてみましょう。 (教育目的です！)

### :keyboard: アクティビティ: 独自の競合を作成

`references.md` という新しいファイルを追加し、その変更を `main` にプッシュしましたが、`my-resume` ブランチは更新しませんでした。

1. `my-resume` ブランチを参照します。
2. `Add file` ドロップダウンメニューをクリックし、`Create new file` をクリックします。
3. `references.md` というファイルを作成します。
4. `main` ブランチの `references.md` に追加した内容と競合するテキストを入力します。
5. ページの一番下までスクロールし、変更のコミットメッセージを入力します。
6. **Commit new file** ボタンをクリックし、「`my-resume` ブランチに直接コミット」オプションが選択されていることを確認します。
7. 約 20 秒待ってから、このページ (手順を実行しているページ) を更新します。 [GitHub Actions](https://docs.github.com/en/actions) は次のステップに自動的に更新されます。

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
