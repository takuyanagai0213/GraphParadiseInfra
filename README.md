# GraphParadise (Infra)
Goで構築するマイクロサービスアプリケーションのインフラをTerraformでコード化(AWS)

## 概要
GraphParadiseはグラフの表示ができるアプリケーションです。
開発環境にDockerを使用し、AWS ECSを使用して本番環境へのデプロイをコンテナ基盤で行なっています。

## 何ができるのか？（機能）
GraphParadise は、以下のことができます。

- グラフの表示

## どのように作られているか？（技術）

- Golang
- JavaScript
- docker（開発環境・本番環境に導入）
- AWS (IAM, VPC, ECR, Fargate, ECS, EKS, ALB, Route53, ACM)
- jQuery
- Github Actions(CI/CD)
- Terraform(インフラのコード化)

