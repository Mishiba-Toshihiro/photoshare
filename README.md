# 画像共有サービスの作成

本リポジトリは、Webサービスとして会員制の画像共有サービスをPythonのフレームワークであるFlaskを利用し作製したものである。

『仕様』
- 会員の者のみ（ユーザ、pw）ログインできる。（sns_user.pyで管理）

- 各ユーザは、写真の投稿と写真のグループを作成可能。写真をグループに割り当てることができる。

- 投稿画像は、画像ごとのfile-id, 作成グループのalbum-idが割り当てられ、dataディレクトリのDB(SQLite)に格納される
- 各ユーザごとの投稿画像を一覧画像で表示して閲覧可能

- 投稿の画像データを時系列で表示可能。全てのユーザからの投稿画像を一覧で確認可能。