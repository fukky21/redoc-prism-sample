# redoc-prism-sample
Docker × ReDoc × PrismでAPI開発環境を構築するサンプルコードです。

解説記事は[こちら](https://qiita.com/fukky21/items/299126f6fa3d343eed22)

## Setup
```bash
$ docker-compose up
```

## Usage
### API仕様を確認する
http://0.0.0.0:8080/ にアクセス

### Mockを使用する
```bash
# 例: ユーザー一覧を取得する
$ curl -X GET -H "Content-Type: application/json" 'http://0.0.0.0:4010/v1/users'
```
