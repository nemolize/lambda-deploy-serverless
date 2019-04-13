# lambda-deploy-serverless

This is an example project of deploying lambda on CLI using [serverless](https://serverless.com/)

# Requirements
- `awscli` must be installed.
- You have authorized your account with `aws configure`.
- The following policies are granted to your service account
  - `iam:*`,
  - `apigateway:*`,
  - `s3:*`,
  - `logs:*`,
  - `lambda:*`,
  - `cloudformation:*`

# How to deploy
- `yarn deploy`
