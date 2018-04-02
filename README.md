# 環境構築

1. src/ の下にLaravelアプリを配置します。
1. nginx/default.conf の root を変更します。
1. php/Dockerfile の WORKDIR を変更します。
1. ターミナルで以下のコマンド打つべし！

```bash
$ docker-compose build
$ docker-compose up -d
```

http://localhost:8080 にアクセス！