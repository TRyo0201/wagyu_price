
# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？

リモートリポジトリ:ネットワークでアクセスするサーバー上のリポジトリ

ローカルリポジトリ：ローカルコンピュータ上のリポジトリ。個別の開発作業を行う場所。

## プッシュとマージの違いは何でしょうか？

プッシュは、ローカルリポジトリの変更をリモートリポジトリに送信する操作です
マージは、異なるブランチの変更を統合する操作です。

## コミットとプッシュの違い
コミットは、ローカルリポジトリに変更を保存する操作
プッシュは、ローカルリポジトリでコミットした変更をリモートリポジトリに送信する操作


## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
一目で変更内容がわかるよう

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？

ローカルでマージするフローは簡単で早いが自己基準での判断になりやすい。プルリクエストでマージするフローはレビューなどが必要なので、品質が高くなりやすい

## コンフリクトを起こしてしまった場合、どう対処すべきですか？
先にマージされた変更内容を取り込む
後にマージしようとしている変更内容を取り込む
どちらの変更内容も取り込む