# README

## About

この構成ファイルは自宅サバでマイクラサーバー(Spigot鯖)を実行するための構成ファイルです。

## Usage

### First Run

`docker compose up -d`

docker-compose.ymlの構成を変更したあとはこのコマンドを実行してください。そのときにコンテナが存在するとエラーが出る可能性があるのでその時は、`docker rm spigot`で過去のコンテナを削除してください。
ワールドデータなどは永続化されているため削除しても問題ありません。

### サーバーの起動

`docker compose start`

一度起動したあとは、このコマンドでサーバーを起動することができます。

### サーバーの停止

`docker compose stop`

サーバーを停止します。

### サーバーの再起動

`docker compose restart`

サーバーを再起動します。
