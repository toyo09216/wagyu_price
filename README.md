# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
### リモートリポジトリ
- ネット上に配置するソースコードの置き場。

### ローカルリポジトリ
- PCに配置するソースコードの置き場。


## プッシュとマージの違いは何でしょうか？
### プッシュ
- ローカルリポジトリの内容をリモートリポジトリにアップロードするためのもの。
### マージ
- 分岐したブランチを統合するためのもの。


## コミットとプッシュの違い
### コミット
- 変更内容をメッセージとして残すためのもの。
### プッシュ
- ローカルリポジトリの内容をリモートリポジトリにアップロードするためのもの。


## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
- 何をどう変更したのか、編集内容をより正確に書いてあげる。


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
### ローカルでマージするフロー
- コードレビューをする前にmasterに反映されるため、コードにバグがあっても気づかない可能性がでてくる。
### プルリクエストでマージするフロー
- masterにマージする前に、レビューを受けることができるため、バグを事前に発見できる。


## コンフリクトを起こしてしまった場合、どう対処すべきですか？
- 先にマージされた変更内容を取り込む
- 後にマージしようとしている変更内容を取り込む
- どちらの変更内容も取り込む  
のいずれかを選択し、取り込み作業が終わったらコンフリクト解決で行った作業内容をコミットする。