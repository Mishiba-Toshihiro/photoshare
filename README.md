# 画像共有サービスの作成

本リポジトリは、Webサービスとして会員制の画像共有サービスをPythonのフレームワークであるFlaskを利用し作製したものである。

『仕様』
- 会員の者のみ（ユーザ、pw）ログインできる。（sns_user.pyで管理）
![動画共有写真 001](https://user-images.githubusercontent.com/62229682/90151112-5902be00-ddc1-11ea-93dd-ff25414d2ff2.jpeg)
- 各ユーザは、写真の投稿と写真のグループを作成可能。写真をグループに割り当てることができる。
![動画共有写真 004](https://user-images.githubusercontent.com/62229682/90151134-5d2edb80-ddc1-11ea-911c-261ff93b80d4.jpeg)
- 投稿画像は、画像ごとのfile-id, 作成グループのalbum-idが割り当てられ、dataディレクトリのDB(SQLite)に格納される
- 各ユーザごとの投稿画像を一覧画像で表示して閲覧可能
![動画共有写真 002](https://user-images.githubusercontent.com/62229682/90151150-61f38f80-ddc1-11ea-8808-be966bb91b83.jpeg)
- 投稿の画像データを時系列で表示可能。全てのユーザからの投稿画像を一覧で確認可能。
![動画共有写真 003](https://user-images.githubusercontent.com/62229682/90151323-8fd8d400-ddc1-11ea-9093-f81dd94e0f69.jpeg)
