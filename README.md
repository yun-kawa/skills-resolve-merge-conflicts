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
<<< 作成者メモ: コース開始 >>>
開始ボタン、Actions の所要時間に関するメモ、そして受講者にこのコースを受講するべき理由を伝えてください。
-->

## ようこそ

GitHub 上で 2人が同じファイルに変更を加えたときにマージコンフリクトが発生します。これは、他の人と共同作業しているときによくあることです。相違点の解決には多少の議論が必要になるかもしれませんが、マージコンフリクトを恐れる必要はありません。このコースでは、マージコンフリクトの最適な解決策を見つけるための手順を解説し、チームが開発を継続できるようにします。

- **対象者**: 新規開発者、GitHub 初心者、Git 初心者、学生、マネージャー、チーム。
- **学習内容**: マージコンフリクトとは何か、マージコンフリクトの解決方法、マージコンフリクトの軽減方法。
- **構築内容**: このコースでは、短い Markdown レジュメファイルを使用します。
- **前提条件**: このコースを受講する前に、[GitHub 入門](https://github.com/kuboctopus/introduction-to-github) を受講することをお勧めします。
- **所要時間**: このコースの所要時間は 30 分未満です。

このコースでは、以下の内容を学習します。

1. プルリクエストを作成する
2. マージコンフリクトを解決する
3. マージコンフリクトを作成する
4. プルリクエストをマージする

### このコースの開始方法

<!-- コースを開始するには、JavaScript で次のコマンドを実行します。
'https://github.com/new?' + new URLSearchParams({
template_owner: 'kuboctopus',
template_name: 'resolve-merge-conflicts',
owner: '@me',
name: 'skills-resolve-merge-conflicts',
description: 'My clone repository',
visibility: 'public',
}).toString()
-->

[![start-course](https://user-images.githubusercontent.com/1221423/235727646-4a590299-ffe5-480d-8cd5-8194ea184546.svg)](https://github.com/new?template_owner=kuboctopus&template_name=resolve-merge-conflicts&owner=%40me&name=skills-resolve-merge-conflicts&description=My+clone+repository&visibility=public)

1. **Start course** を右クリックし、リンクを新しいタブで開きます。
2. 新しいタブでは、ほとんどのプロンプトが自動的に入力されます。
- オーナーとして、個人アカウントまたはリポジトリをホストする組織を選択します。
- プライベートリポジトリは[Actionsの分単位の課金](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions)が発生するため、パブリックリポジトリを作成することをお勧めします。
- 下にスクロールし、フォームの下部にある**Create repository**ボタンをクリックします。
3. 新しいリポジトリが作成されたら、約20秒待ってからページを更新します。新しいリポジトリのREADMEに記載されている手順に従ってください。

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
