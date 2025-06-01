
# 職務経歴書

## 基本情報

|項目名|項目内容|
|---|---|
|氏名|肥塚遼|
|生年月日|1994年11月26日|
|居住地|東京都|
|最終学歴|東京大学大学院理学研究科（物理学専攻）修了|
|メールアドレス|<supermarine@outlook.jp>|
|取得資格等|応用情報処理技術者|
|プロフィール|横浜国立大学理工学部卒、東京大学理学系研究科修士課程修了。株式会社ZUUにてソフトウェアエンジニアとして自社プロダクト開発の保守運用業務をリードし、株式会社Insight Edgeに入社。|

---

## 保有スキル

- Webアプリケーションの保守運用
  - 障害対応
  - ログやメトリクス監視
  - 開発案件の受付、管理
  - 保守運用チーム管理
- Webブアプリケーション開発
  - バックエンドを中心としたフルスタック開発
  - Goによる実装や、DB設計, インフラ構築
  - マイクロサービスの開発も経験
- ファシリテーション
  - 限られた時間内で行うミーティングで、確実に目的を達成できるよう支援。
- 投資
  - 金融業の企業に勤めている影響から個別株投資に挑戦中。

## 技術スタック

### バックエンド

言語, 単体テスト

![Go Badge](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=fff&style=flat)

DB

![PostgreSQL Badge](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=fff&style=flat)
![MongoDB Badge](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=fff&style=flat)

インフラ

![Docker Badge](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=fff&style=flat)
![Google Cloud Badge](https://img.shields.io/badge/Google%20Cloud-4285F4?logo=googlecloud&logoColor=fff&style=flat)
![Kubernetes Badge](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=fff&style=flat)
![Helm Badge](https://img.shields.io/badge/Helm-0F1689?logo=helm&logoColor=fff&style=flat)
![Terraform Badge](https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=fff&style=flat)

モニタリング

![Datadog](https://img.shields.io/badge/Datadog-632CA6?logo=datadog&logoColor=fff&style=flat)

CI

![GitHub Actions Badge](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=fff&style=flat)
![CircleCI Badge](https://img.shields.io/badge/CircleCI-343434?logo=circleci&logoColor=fff&style=flat)

デプロイ

![ArgoCD](https://img.shields.io/badge/Argo%20CD-1e0b3e?style=for-the-badge&logo=argo&logoColor=#d16044)
![Spinnaker](https://img.shields.io/badge/Spinnaker-139BB4?logo=spinnaker&logoColor=fff&style=flat)

### フロントエンド

![Nuxt.js Badge](https://img.shields.io/badge/Nuxt.js-00DC82?logo=nuxtdotjs&logoColor=fff&style=flat)

### BI

![Google BigQuery Badge](https://img.shields.io/badge/Google%20BigQuery-669DF6?logo=googlebigquery&logoColor=fff&style=flat)
![dbt Badge](https://img.shields.io/badge/dbt-FF694B?logo=dbt&logoColor=fff&style=flat)
![Looker Badge](https://img.shields.io/badge/Looker-4285F4?logo=looker&logoColor=fff&style=flat)

### その他

![Git Badge](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=fff&style=flat)
![GitHub Badge](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=fff&style=flat)
![WordPress Badge](https://img.shields.io/badge/WordPress-21759B?logo=wordpress&logoColor=fff&style=flat)

---

## 職務経歴詳細

### 株式会社Insight Edge （2022年6月から）

### 株式会社ZUU （2022年4月から2025年6月）

自社プロダクトの保守運用、新規テナント構築、新機能開発、BI開発によるマーケティング支援を行なっている。

#### 自社プロダクトのMP Cloudの保守運用

対象プロダクト: 自社WebアプリケーションのMP Cloud（オウンドメディア向けのCMS）保守運用業務に、チームリーダーとして従事（4名チーム）。約20テナント、最大月間100万PV規模のプロダクトを担当。

技術スタック: Go, GCP (GKE, Compute Engine, Cloud SQL、Cloud Armorm、Cloud Build, Cointainer Registry, Memorystore, Cloud Monitoring, Cloud Storage, Cloud Function, Cloud CDN, Cloud Load Balancer, Pub/Sub), Terraform, Postgres, Redis, Datadog, ElasticSearch, Backlog, Slack 等を使用。

担当領域: インフラ管理、保守運用案件管理、Goによるバックエンド開発、GCPでのインフラ構築、ログ監視、品質管理、運用フロー改善。

主な経験・実績:

- 障害対応
  - サービス停止、パフォーマンス低下、データ不整合等、10件以上の障害対応を主導。
  - ログ・メトリクス分析、本番再現、原因特定、コード修正、再デプロイまでの一連のプロセスを遂行し、プロダクトの安定稼働に貢献。
  - GKEアプリケーションのトラブルシューティング、DBインデックス・API計算量・Redis Scan問題に起因するパフォーマンス低下の解消、外部攻撃のWAFブロック対応、VPC内部におけるネットワーク起因の障害対応など、非常に幅広い障害対応を主導。
  - 障害発生時のインシデントチェックリストを用いた複数人での対応フローを実践し、関係部門への迅速な連絡と情報共有を徹底。
  - 事後には必ず振り返りを実施し、監視設定、退行テスト、インフラ構成等の見直しによる再発防止策を講じた。
- 監視・予防保守
  - Datadogを用いたSLOベースの監視体制を構築・運用。サイト応答時間やレスポンスステータス等の主要メトリクスを監視し、異常検知時はCUJ（Critical User Journey）に基づき重大度を判断して対応。
  - アプリケーションエラーログを継続的に確認し、不必要なログの発生原因を特定してGoコード改修を行うことで、監視効率の向上と真に必要なアラートへの集中に貢献。
  - CPでのテナント新規構築、定期的なインフラ管理を実施。
- 開発経験
  - Goを用いてバックエンドのバグ修正やAPI改善開発を実施。保守運用で発見した課題（例：不必要なエラーログ発生）に対するコードレベルでの根本解決を推進。
- インフラ構築
  - 新規テナントのインフラ構築を3件以上経験。Terraformによるリソース作成、GKEリソースデプロイを主導。
  - インフラ構築をするための社内アプリケーション実装やインフラ構築手順書整備などにより、16時間程度かかっていたインフラ構築時間を8時間程度まで圧縮。
- チームリーダー・管理経験
  - 3名チームのリーダーとして、保守運用案件の優先順位付け、チームメンバーへのタスク割り振り、進捗管理を実施。
  - 障害対応フローの改善や、関係部門との連携強化を通じて、チーム全体の対応力と運用効率向上に貢献。

#### 自社プロダクトの追加開発

開発案件の受付、開発、テスト、デプロイも担当。規模の大きかった案件を挙げる。

- MP Cloudのコンテンツの編集履歴を管理するマイクロサービス開発
  - 使用技術: Go, API Gateway, Cloud Run, GKE, MongoDB, ArgoCD
  - MP Cloudのコンテンツ（記事など）を誰が・どのように・いつコンテンツを変更したのか管理画面で参照する機能の開発。コンテンツの管理コストの削減、エンジニアへの問い合わせ工数の削減、CMSとしての価値向上を目的とする。
  - MP Cloudのコードベースが複雑であり変更コストが高かったため、MP Cloudとはコードベースやインフラが独立したマイクロサービスとして構築。MP Cloudのbackendからマイクロサービスを呼び出して編集履歴を管理する形式。
  - MP Cloudの管理画面上でコンテンツの作成・管理するとき（月に1万回以下と見積もった）にマイクロサービスがactiveであればよかったため、コスト削減のためにもコールドスリープ機能を有するCloud Runを選定。
  - 将来的に似たようなマイクロサービスが多数構築されることが想定されたため、MP CloudとCloud Runの間にAPI Gatewayを挟み、マイクロサービスの管理が容易になるようにした。
  - コンテンツの作成・編集は頻繁に発生するためマイクロサービスが管理するデータベースのデータ書き込みも頻繁に発生するが、編集履歴は滅多に参照しないことが想定されたため、データの書き込みパフォーマンスに優れたNoSQLの中でも手軽にJSON形式のデータを保存できるMongoDBを選定。
  - 当初は手軽に利用できたMongo Atlasを使用していたが、よりデータを管理しやすくするのと、Mongo Atlasは高度なサービスレベルをもつがマイクロサービスのサービスレベルと比較して過剰であったため、MongoDBをGKE管理のStatefulSetに移管。そのため、Cloud RunからStatefulSetにアクセスできるようにするためのInternal LoadBalancerのServiceを使用。
- 自社メディアへの3Dセキュア認証の導入
  - 使用技術: Go, Vue, ArgoCD
  - 自社メディアにユーザーがクレジットカードを登録する時の3Dセキュア認証の導入を主導。不正利用の防止を目的とし、自社メディアのセキュリティ向上に貢献。
  - 開発に至るまでの動機、現状のMP Cloudにおけるクレジットカード登録処理の仕様、3Dセキュア認証を導入するための技術要件、詳細な設計をDesign Docsとして整理。
  - MP CloudのbackendのGoアプリケーションとfrontendのVueアプリケーションを修正し、クレカ登録時に3Dセキュア認証を挟むように変更。
  - 仕様変更やリファクタリングを数多く行ったため、変更後の仕様を確認しやすくするために単体テストを充実。CIで単体テストを実行して問題がないことを確認。
  - 品質保証のため、退行テストや結合テストを充実させた。スプレッドシートに複数シナリオの100個以上のテストケースを記載し、テストを実施した。実際に問題のあるバグが見つかり、品質向上に役立った。
  - 決済代行業者とのやりとりも担当。技術要件の確認や、テストの方法などを問い合わせ、アプリケーションの品質向上に貢献。

#### BI開発によるマーケティング支援

自社と顧客が協業して運営するメディアにおけるコンバージョン増のため、ビジネスインテリジェンス（BI）の設計、開発、保守をおこなっている。マーケティング担当者や管理職に対する聞き取り、ビジネス上の課題の設定、課題解決の方針をチームで共同して実施し、ビジネス上のKPIの進捗を確認するためのダッシュボードを作成し、担当者に提供、継続的に保守している。

- ビジネス上の課題設定
  - FigJam, Google Documents
- データウェアハウス構築
  - Big Query, dbt
- ダッシュボード設計
  - FigJam
- ダッシュボード構築
  - Looker Studio

### 株式会社アクア (2020年4月から2022年3月)

2つの受託開発案件にて、自らの作成した要件定義と設計をもとに、バックエンドとフロントエンドの開発をしていた。

自社のコーポレートサイトのリニューアルも担当し、バックエンドとフロントエンドの開発もおこなった。

## SWEとしての強み

- モダンなクラウドインフラ (GCP) と多様な技術スタックを駆使した横断的な対応力
  - GCP（GKE, Cloud Run, Cloud SQL, Cloud Armmor, Terraformなど多数）を深く理解し、インフラ構築から運用・保守まで幅広く対応。
  - Goによるバックエンド開発、Postgres/MongoDB/Redis/ElasticSearchといった多様なデータストアの扱い、Vueによるフロントエンド連携、BIツール（BigQuery, dbt, Looker Studio）活用など、アプリケーション層からデータ活用までカバーする技術的な幅広さ。
  - これらの技術を組み合わせ、プロダクトのインフラ、アプリケーション、データ基盤といった異なるレイヤーの課題に対して、複合的な視点から解決策を提供可能。
- プロダクトの安定稼働と信頼性向上に貢献する卓越した問題解決能力
  - サービス停止、パフォーマンス低下、データ不整合、ネットワーク障害など、幅広い種類の障害に対して、10件以上を主導して対応した豊富な経験。
  - ログ・メトリクス分析、本番再現、原因特定、コード修正、デプロイ、事後振り返りといった一貫したプロセスを迅速かつ正確に遂行し、プロダクトの早期復旧と再発防止に貢献。
  - 技術的な課題（DBインデックス、計算量、Redis Scan、GKEトラブルシューティング、ネットワーク問題）を深く掘り下げ、根本原因を特定・解消する能力。
- 積極的な監視・予防保守によるリスク低減と運用効率化
  - Datadogを用いたSLOベースの監視体制の構築・運用や、CUJに基づいた重大度判断により、潜在的な問題を早期に検知し、ビジネス影響を最小限に抑える取り組み。
  - アプリケーションエラーログの分析からコード改修に至る実践を通じて、監視のノイズを減らし、運用チームが重要なアラートに集中できる環境を整備。
  - Terraformを用いた新規テナント構築の効率化（構築時間半減）や、手順書整備など、インフラ運用の標準化・自動化を推進した実績。
- ビジネス課題解決に繋がる開発力とアーキテクチャ設計スキル
  - Goを用いたバックエンド開発において、単なる機能実装に留まらず、保守運用上の課題（不必要なエラーログ）を解決するためのコード改修を主導。
  - 複雑なシステム（MP Cloud）に対し、マイクロサービス化というアーキテクチャ設計を行い、技術選定（Cloud Run, MongoDB, API Gateway）を根拠をもって実行。開発コスト削減と将来的な拡張性を考慮した設計力。
  - キュリティ向上（3Dセキュア導入）やCMS価値向上といった明確なビジネス目的を持って開発に取り組み、技術要件定義から設計、実装、テスト、外部連携まで一貫して推進。Design Docs作成による設計の明確化も実践。
- 品質保証への強い意識と実践的なテスト経験
  - 大規模な改修（3Dセキュア導入）において、単体テスト、退行テスト、結合テスト（100件以上のテストケース作成・実行）を徹底し、プロダクトの品質確保に貢献。
  - 決済代行業者といった外部関係者との連携を通じて、技術仕様の確認やテストの整合性を図るなど、システムの品質向上に必要な多角的な取り組み。
- チームリーダーとしてのマネジメントと組織貢献
  - 3名チームのリーダーとして、保守運用案件や開発タスクの管理、優先順位付け、チームメンバーへの適切なタスク割り振り、進捗管理を実行。
  - 障害対応フローの改善や、関係部門（ビジネス部門、上司、外部ベンダー）との密な連携を通じて、チーム全体のパフォーマンス向上と円滑なプロジェクト進行に貢献

## 取得資格

応用情報処理技術者　2021年12月取得
