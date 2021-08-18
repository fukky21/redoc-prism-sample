# redoc-prism-sample

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
