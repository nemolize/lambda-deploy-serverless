# lambda-deploy-serverless

[serverless](https://serverless.com/)を利用してCLIからlambdaデプロイを行うサンプルプロジェクト

# 必要なもの
- `awscli` がインストールされていること
- `aws configure` でデプロイアカウントの認証が行われていること
- 下記のポリシーがデプロイアカウントに付与されていること
  - `iam:*`,
  - `apigateway:*`,
  - `s3:*`,
  - `logs:*`,
  - `lambda:*`,
  - `cloudformation:*`

# セットアップ
```console
yarn
```

# デプロイ
```console
yarn deploy
```
