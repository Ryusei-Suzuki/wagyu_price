# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
- リポジトリとは<br>
  ファイルやディレクトリの状態を記録する場所<br>
  そのソースコードの置き場のようなもの

- リモートリポジトリ<br>
  プログラムをネット上に配置し、保存や他の人と共有するためのリポジトリ

- ローカルリポジトリ<br>
  制作したプログラムを自分のPC上に保存しておくためのリポジトリ 

## プッシュとマージの違いは何でしょうか？
- プッシュ<br>
  ローカルの内容をリモートへ反映させる

- マージ<br>
  別ブランチで作成した変更内容をmasterブランチへ反映させる

## コミットとプッシュの違い
コミットはプログラムの変更内容を保存するコマンド<br>
プッシュはローカルの内容をリモートへ反映させるコマンド

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
コミットを行った際のプログラム変更内容がわかるようなメッセージにする

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
- ローカルでのマージ<br>
  ローカルリポジトリで作成した別ブランチの変更内容をmasterブランチへ反映させる

- プルリクエストでマージ<br>
  ローカルリポジトリで作成した別ブランチの変更内容を、リモートリポジトリの同じブランチへプッシュし、マージの許可をもらえた場合、リモートリポジトリのmasterブランチへマージする事ができる

## コンフリクトを起こしてしまった場合、どう対処すべきですか？
重複している内容を確認し、どの変更内容を反映するかを決める