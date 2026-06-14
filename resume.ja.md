# 職務経歴書

2026年6月現在

![ikuwow](ikuwow.webp)

Ikuo Degawa (@ikuwow)

SRE / Platform Engineer

1990年生まれ 神奈川県在住

* X https://x.com/ikuwow
* GitHub https://github.com/ikuwow
* Blog https://queryok.ikuwow.com
* Email ikuwow(at)gmail.com

この職務経歴書の最新版はGitHubにあります: https://github.com/ikuwow/resume

## 概要

Web系企業で SRE・プラットフォームエンジニアとして、サービスの信頼性とデリバリー基盤づくりに長く携わってきました。
AWS を基盤とした SLO/SLI 運用、GitOps・プログレッシブデリバリー、Kubernetes・Istio によるマイクロサービス基盤の設計・構築・運用を得意としています。
職種や技術領域をまたいで、技術・組織・コストのトレードオフを踏まえた全体最適な問題解決に取り組み、常にプロジェクトやサービスの目的とユーザーへの価値を見据えて行動します。

## スキル

### コア（信頼性・デリバリー基盤）

* SRE / DevOps の実践（CI/CD 環境の構築・運用、障害対応のリーダーシップ、ポストモーテムや50%ルール等のプラクティス、Enabling SRE）
* SLO/SLI・エラーバジェットポリシーの整備と運用
* 可観測性のための仕組みの設計・構築（Datadog 等）
* GitOps・プログレッシブデリバリーの設計・運用（PipeCD, Flagger, Flux 等）
* Kubernetes・Istio によるマイクロサービスアーキテクチャの設計・構築・運用
* AWS を中心としたクラウドインフラの構築・運用
* Golang によるバックエンドアプリケーションの開発・運用
* 手を動かした技術検証・PoC
* AIコーディングエージェントの活用、およびAIエージェントを前提とした開発プロセスの設計・導入

### 実務経験

* 言語・フレームワーク: PHP, Ruby on Rails, Java/Spring, JavaScript, Golang, CakePHP
* クラウド・基盤: AWS, GCP, Terraform, Ansible, Chef, Docker, Kubernetes, ECS
* データストア・分析基盤: PostgreSQL, MySQL, Elasticsearch, Redshift, BigQuery, Tableau
* フロントエンド: HTML/CSS/JavaScript, Sass, Webpack, RUM による観測・パフォーマンス改善
* その他: ネットワーク・インフラの基礎知識、オフィスネットワーク構築、英語の読み書き・リスニング

### バックグラウンド・周辺

* MATLAB・C 言語による画像処理・音声処理プログラミング
* Swift による iOS アプリの開発
* WordPress 等 CMS のカスタマイズ

<div class="page-break"></div>

## 職務経歴

### 株式会社tacoms

業務委託として2024年6月〜2025年7月、正社員として2025年8月から現在まで勤務

SRE のテックリードとして、飲食店向け注文管理 SaaS「Camel」の信頼性・デリバリー・コストを横断的に推進

#### SREメンバー/テックリード

* ECS Fargate, Aurora, SQS/SNS, Lambdaを利用したAWSサービス基盤の運用
* Aurora MySQLのパフォーマンス最適化
* BigQuery等を用いたデータ集計基盤の設計/構築
* 新規サービスインフラ構築・運用
* CIOps（GitHub Actions → ECR → ECS）からGitOps (PipeCD) への移行設計・実装
* Datadogを用いた可観測性を担う仕組みの構築、推進
* TiDB移行調査/検討
* PipeCDを用いたcanary release / progressive deliveryの導入
* 外部サービスとの連携エラー検知基盤の設計、構築 (Lambda, EventBridge, Datadog)
* 顧客のキャンペーンに伴う負荷対策
* AI活用のための基盤構築
* 各種障害対応、オンコール

#### 飲食店向け注文管理 SaaS「Camel」の開発/運用

* SLO/SLIの設計、計測基盤の構築、運用 (Datadog, AWS)
* Golangバックエンドアプリケーションの開発、運用
* 外部連携の可用性等の計測の仕組みの構築
* インフラコスト最適化
* 他製品からのリプレイスの推進
* 大手企業導入に伴う機能改修

#### 共通

* GitHub, Datadog等の社内基盤システムの管理者

### 株式会社ZOZO

正社員として2021年12月〜2024年4月の間フルリモートで勤務

大規模ECのプラットフォームSRE、および基幹システムリプレイスのリードSREを担当

#### プラットフォームサービスSREブロック, Front SREブロック

* Kubernetes基盤の設計・構築・運用
* Istioを用いたサービスメッシュ上でのマイクロサービスアプリケーションの運用
* MySQL、SQL Serverの運用
* Java、NodeJSアプリケーションの運用
* Terraformを用いたSentry, Datadog, PagerDuty等SaaSの管理
* SLOに基づいたサービス信頼性の担保
* GitHub Actions等を用いたMono repoの並行パイプラインを実現するワークフローの構築
* Flagger、Flux等の利用拡大
* GitHub Projectsの採用
* オンコール担当、障害対応
* 新入社員のメンター担当

#### 基幹システムリプレイスのリードSRE

* ドメイン知識のキャッチアップと要件への落とし込み
* Kafka (Amazon MSK等)を用いたデータ連携方式のPoC、設計、構築
* タスク/スケジュールの管理
* RDBの論理設計
* リリースフローの構築と開発チームへのレクチャー
* セキュリティ等各種ガイドラインの遵守
* SREや開発チームへのリプレイス後技術のレクチャー
* リリース前負荷試験の実施

#### フロントエンドリプレイスプロジェクト

* マイクロサービス基盤上でのNodeJSアプリケーションの設計、構築、運用
* AkamaiでのWAFやルーティングの設計
* リリースフローの構築と開発チームへのレクチャー
* セキュリティ等各種ガイドラインの遵守
* SREや開発チームへのリプレイス後の技術のレクチャー
* リリース前負荷試験の実施

### 株式会社エス・エム・エス

正社員として2017年10月〜2021年11月の間勤務
（2020年よりフルリモート勤務）

介護経営支援 SaaS「カイポケ」をはじめとする複数サービスの SRE を担当

#### 社内向けLPホスティングサービスの開発、サポートほか

2020年8月〜2021年11月

* Ruby on Railsアプリケーションの機能改善
* Serverlessアプリケーションの環境再構築、メンテナンス
* CIやワークフローの整備による開発体制改善
* AWS環境の作り直しによるコスト削減、管理の改善
* コードレビューとリリース管理
* 利用者（マーケター、デザイナーほか）のコンサルティング
* サービスの位置づけの定義、今後の方向性の決定

#### 介護経営支援サービス（SaaS）カイポケのSRE

2017年10月〜2020年7月

* 複数のSpring, SAStrutsアプリケーションをまたぐシステム全体のパフォーマンス改善
* アプリケーション/DBのパフォーマンスチューニング
* 協力会社とのAWS環境のメンテナンス
* AWS, Terraformによる開発環境の構築とメンテナンス
* 依存フレームワークやパッケージのEoLの対応
* バッチのメンテナンス
* SLIの策定とAWSを使った実装、可視化、SLOの決定
* インフラ全体のコスト最適化
* リリーススケジュールの調整等、各開発チームのサポート
* 社内からのシステムへの要求のトリアージ、問題解決のサポート

### チームアップ株式会社

業務委託として2018年4月〜2021年6月の間フルリモートで従事

#### 1 on 1ツールTeamUpのインフラ整備、開発体制の仕組み化支援

2018年4月〜2021年6月

* Terraform/Ansibleを用いたAWS環境のIaC化
* ドキュメント管理ツール esa.io、GitHubを使った開発体制の仕組み作り
* CircleCI等を用いた開発フローの整備
* サービスが稼働するAWS環境のリプレイス、メンテナンス
* AWSサービスを使ったセキュリティの要件の決定と実装
* Ruby on Railsアプリケーションのパフォーマンス改善サポート
* Ruby on Railsアプリケーションの管理面の機能開発

<div class="page-break"></div>

### レバレジーズ株式会社

正社員として2015年4月〜2017年9月の間勤務

#### エンジニア向けQ&Aサービス「teratail」の開発ほか

2015年4月〜2017年9月

* CakePHPアプリケーションの機能開発、メンテナンス
* 公開REST APIの設計、構築
* キャンペーンページのフロントエンド全体の開発
* CI環境の整備
* 事業目標達成のための施策検討
* Elasticsearch, Redshift, BigQuery等を使った分析基盤の構築
* VPCからGKE(Kubernetes)環境への移行
* アプリケーション全体のパフォーマンス改善
* メールマガジンのシステム（Mailchimp）の導入とアプリとの接続
* 純広告のシステム（Google Adwords）の導入と管理
* その他
  * 社内ネットワークの設計、構築、管理
  * 記事コンテンツの執筆
  * メールマガジン等のコンテンツの構築・ディレクション
  * 採用活動への参加
  * 2015年度Excellent Hacker賞受賞

### スローガン株式会社

インターンとして2013年9月〜2015年3月の間勤務

#### 「Goodfind」関連メディアのメンテナンス、社内ネットワーク整備ほか

* ユーザー向けCakePHPアプリケーションの機能開発
* 管理者向けCakePHPアプリケーションの機能開発
* Chef等を用いたVPC環境のリプレイス
* オフィス内/オフィス間ネットワーク構築、メンテナンス
* iOSアプリの新規開発
* 学生エンジニア向けセミナー講師

## 執筆

* [tacoms テックブログ](https://tacoms-inc.hatenablog.com/archive/author/ikuwow) テックブログ執筆 2024年〜
* [旧tacoms テックブログ](https://zenn.dev/p/tacoms) テックブログ執筆
* O'Reilly [進化的アーキテクチャ](https://www.oreilly.co.jp/books/9784873118567/) 翻訳レビュー 2019年
* SoftwareDesign連載 アプリエンジニアのための［インフラ］入門 全6回 2016年
* gihyo.jp [あとはコードを書くだけ，はじめに作る開発環境構築ベストプラクティス](https://gihyo.jp/dev/serial/01/howto-env-conf) 2016年
* gihyo.jp [聞いたら一生の宝，プログラミングの基礎の基礎](https://gihyo.jp/dev/serial/01/js-foundation)（第3,5,7回）2015年

## 資格

* [LPIC-3 305 (Virtualization and Containerization)](https://people.lpi.org/m/LPI000286814) 2024年
* 日商簿記 2級 2016年
* 情報処理技術者試験 ネットワークスペシャリスト 2015年
* TOEIC Score 860 2013年

## 学歴

* 2015年3月 慶應義塾大学大学院理工学研究科 総合デザイン工学専攻 卒業
* 2013年3月 慶應義塾大学理工学部 電子工学科 卒業
