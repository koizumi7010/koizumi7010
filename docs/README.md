# 職務経歴書

## 基本情報

| 項目 | 内容 |
|------|------|
| 氏名 | 小泉 直人 (Koizumi Naoto) |
| 生年月日 | 1997年12月19日 |
| 経験職種 | バックエンドエンジニア・SRE |
| 居住地 | 東京都 |
| 最終学歴 | 法政大学デザイン工学部システムデザイン学科 |

## 連絡先
- [GitHub](https://github.com/koizumi7010)
- [LinkedIn](https://www.linkedin.com/in/naoto-koizumi-161a05225/)
- [YOUTRUST](https://youtrust.jp/users/67c6e4e6fa0d1a66457a123842f23c3f)

## プロフィール
バックエンドエンジニア・SREとして約3年の経験を持つソフトウェアエンジニアです。
Goを主軸としたサーバーサイド開発から、AWS・Kubernetesを活用したクラウドインフラの設計・運用まで幅広く担当しています。
特にクラウドネイティブな環境での開発・運用に強みを持ち、コスト最適化や自動化による業務効率化を得意としています。
Platform Engineeringの分野にも知見があり、開発者体験の向上にも積極的に取り組んでいます。

## 技術スキル

### プログラミング言語
- **主要言語:**
  - Go・Python
- **経験のある言語:**
  - TypeScript・JavaScript

### フレームワーク・ライブラリ
- **Backend:** 
  - goa・chi・Django・Celery
- **Frontend:** 
  - React・Next.js

### 通信プロトコル
- REST・GraphQL 

### データベース
- **RDBMS:** 
  - MySQL・PostgreSQL
- **NoSQL:** 
  - Redis
- migration

### インフラ・DevOps
- **クラウド:** 
  - AWS
    - EKS・S3・ElastiCache(Redis)・Aurora MySQL・DynamoDB・OpenSearch・SNS・CloudFront・ELB・Kinesis Firehose・Lambda・SQS・Secrets Manager・CloudWatch・CloudTrail etc...
- **CI/CD:**
  - GitHub Actions, CircleCI
- **コンテナ:**
  - Kubernetes
    - Istio・Managed Node Group・AWS Load Balancer Controller・Cluster Autoscaler・External Secrets Operator・Descheduler・External DNS・CoreDNS・Vertical Pod Autoscaler
  - Docker
- **Platform Engineering**
  - Backstage
- **その他:**
  - Terraform
  - Helm・helmfile
  - Skaffold

### セキュリティ
- AWS(Security Hub・GuardDuty・Organizations)・Snyk・Trivy・Kubescape

### ツール・その他
- **監視・オンコール:**
  - Datadog・PagerDuty
- **開発環境:**
  - VSCode・Claude Code
- **バージョン管理:**
  - GitHub
- **プロジェクト管理:**
  - Jira

## 職務経歴

### 株式会社Gunosy | Backend Engineer, SRE | 2022/01-在籍中
#### **地域ニュース施策** 
- **役割:** バックエンドエンジニア（主担当）
- **技術スタック:** Go・MySQL・Redis・AWS・Kubernetes・Docker・Skaffold
- **主な成果:**
  ユーザーごとに地域ニュースを配信する施策のサーバーサイド対応をリードし、ネイティブアプリ向けのバックエンドAPIの要件定義〜開発実装を担当
    - 新機能のバックエンドAPI開発（Go）
    - データベースのスキーマ設計（MySQL）

#### **社内管理画面の新機能実装**
- **役割:** バックエンドエンジニア（主担当）
- **技術スタック:** Go・MySQL・TypeScript・GraphQL・Next.js・AWS・Kubernetes・Docker・Skaffold
- **主な成果:**
  社内ユーザーが管理画面から新施策向けに記事の登録や削除、並び替えなどを行う機能を実装
    - Go、GraphQLを用いた管理画面向けAPIの開発
    - TypeScript、Next.jsを用いた管理画面の実装
    - データベースのスキーマ設計

#### **雨雲プッシュ機能の実装**
- **役割:** バックエンドエンジニア（主担当）
- **技術スタック:** Go・Python・Cerely・FCM・MySQL・AWS・Kubernetes・Docker・Helm・Skaffold
- **主な成果:**
  ユーザーの地域データに基づき、雨雲が接近している各ユーザーにプッシュ通知を行う新機能の実装
    - Goを用いた各市区町村の雨雲データを取得するバッチ実装
    - Python, Cerelyを用いた雨雲プッシュ機能の実装
    - データベースのスキーマ設計

#### **Amazon Auroraのコスト最適化**
- **役割:** バックエンドエンジニア（主担当）
- **技術スタック:** AWS・Aurora MySQL/PostgreSQL・Terraform
- **主な成果:**
  Amazon Aurora I/O-Optimizedによるコスト最適化を実施
    - 具体的な実施内容は[こちらのブログ](https://tech.gunosy.io/entry/aurora_io_optimized)に記載しています。

#### **クラウドインフラにおける脆弱性およびメンテナンス情報等の管理・自動化**
- **役割:** SRE（主担当）
- **技術スタック:** AWS・Health Event・Datadog・Jira
- **主な成果:**
  AWSにおいて検出されたHealth Event(メンテナンス通知など)やセキュリティ項目(Security Hub,Snyk)の管理・自動化を組織横断的に導入しました
    - 具体的な実施内容は[こちらのブログ](https://tech.gunosy.io/entry/infrastructure-issue-jira)に記載しています。

### 富士通株式会社 | Network Engineer | 2020/04-2021/12
#### **病院向けモバイルネットワーク基盤の導入**
- **役割:** Network Engineer（副担当）
- **技術スタック:** sXGP(Private LTE)・RHEL・Cisco
- **主な成果:**
  sXGPを利用した病院向けのモバイルネットワーク基盤の提案・設計プロジェクトを担当しました
    - アクセスポイントの設計とハンドオーバーの検証
    - SDNを利用したsXGP基盤の設計・構築・検証 

## 技術記事・アウトプット
- [Zenn](https://zenn.dev/koizumi7010)
- 登壇
    - [Platform Engineering Meetup Online #1](https://www.youtube.com/watch?v=koMsUFOar88)
        - **タイトル:** 入門Backstage SystemModelの理解と活用方法

## 学歴
- 法政大学 デザイン工学部 システムデザイン学科 (2020年卒業)

## 資格・認定
- AWS Solution Architect Associate
- Cisco Certified Network Associate
- ITILv4 Foundation

## 言語
- **日本語:** ネイティブ
- **英語:** 読み書き

## その他
- **趣味・興味:** 音楽(US・UK)、映画、車
- **コミュニティ活動:** Platform Engineering Kaigiの運営メンバー
