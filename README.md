# dotnet-webapp-sample

サーバーサイド、フロントエンド全てC#で作成したアプリケーションのサンプル

## Get started

Required

- Docker
- Docker Compose

```sh
docker-compose build
docker-compose up -d

# Access to
http://localhost:8080
```

## 構築手順

- 前提：.NET Core SDK 3.1以上 or .NET Core SDK 3.1以上が入ったコンテナ

```sh
dotnet new blazorwasm --hosted
```

Blazorだけ(Serverなし)で構築したい場合は `--hosted` を取る

以上！！！
