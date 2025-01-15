# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？

- リモートリポジトリ
    - サーバー上にあり、複数の開発者へ共有できる。
- ローカルリポジトリ
    - 各個人の開発環境で、ローカルでの作業を行うため。

## プッシュとマージの違いは何でしょうか？
- プッシュ
    - ローカルリポジトリの変更をリモートリポジトリに反映させること。
- マージ
    - 分岐した変更履歴を統合すること。

## コミットとプッシュの違い
- コミット
    - 新規作成したファイルや編集したファイルを保存すること。
- プッシュ
    - コミットした内容をリモートリポジトリに反映させる。

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？

- 簡潔かつ具体的に、誰が読んでも内容が理解できること。

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？

- ローカルでマージ
    - レビューがないため、コードの品質を担保担保できない。
- プルリクエストでマージ
    - レビューを経てマージすることで、コードの品質を担保する。

## コンフリクトを起こしてしまった場合、どう対処すべきですか？

- 先にマージされた変更箇所を、後のコードに取り込んでから再度マージする
