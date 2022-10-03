# web-message-board
このプロジェクトは、掲示板アプリのソースコードです。

## コンテナ起動

起動するときは以下のコマンドを入力します。
プロジェクトルートでコマンドを実行する必要があります。

```sh
# Start
$ docker compose start
```

## アクセス

コンテナ起動中は、以下の URL にアクセスできます。

<http://localhost:8080/>
<http://localhost:8081/>


## コンテナ終了

制作終了時は以下のコマンドでコンテナを終了します。
（※ `docker run` コマンドで --rm を使用している場合は Ctrl + C でプロセスを終了すると、自動的にコンテナも削除されます。）

```sh
$ docker compose stop
```

## 一通り作業が終了

```sh
$ docker compose down
```