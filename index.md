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
|プロフィール|横浜国立大学理工学部卒、東京大学理学系研究科修士課程修了。株式会社ZUUにてソフトウェアエンジニアとして自社プロダクトの保守運用・マイクロサービス開発をリード。その後、住友商事グループのDX専門会社である株式会社Insight Edgeに入社し、SRE/プラットフォームエンジニアとして全社横断の運用自動化基盤（データパイプライン構築、LLM活用等）の設計・実装を主導している。|

---

## 保有スキル

- **SRE / Platform Engineering**
  - 運用保守の属人化を排除する「Documentation as Code」の実践とパイプライン構築
  - dbt / BigQueryを用いたビジネス・運用KPIのデータモデリングと可視化
  - 障害対応、トイル撲滅
  - 非機能要件（セキュリティ、可用性）の全社標準フレームワーク策定
- **Webアプリケーション・インフラ開発**
  - Goを用いたバックエンド設計・実装、マイクロサービスアーキテクチャ設計
  - GCP (GKE, Cloud Run等) およびTerraformを用いたインフラのIaC化
  - 生成AI（Claude等）を活用した高度な開発・アーキテクチャ設計
- **プロジェクト推進・ベンダーコントロール**
  - 外部委託先を活用した運用保守体制の構築とエスカレーションフローの整備
  - ファシリテーションおよびステークホルダー（経営層、開発チーム、外部ベンダー）間の要件調整

## 技術スタック

### バックエンド

言語, 単体テスト
![Go Badge](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=fff&style=flat)

DB
![PostgreSQL Badge](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=fff&style=flat)
![MongoDB Badge](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=fff&style=flat)

インフラ・IaC
![Docker Badge](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=fff&style=flat)
![Google Cloud Badge](https://img.shields.io/badge/Google%20Cloud-4285F4?logo=googlecloud&logoColor=fff&style=flat)
![Kubernetes Badge](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=fff&style=flat)
![Helm Badge](https://img.shields.io/badge/Helm-0F1689?logo=helm&logoColor=fff&style=flat)
![Terraform Badge](https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=fff&style=flat)
Terraform Cloud

モニタリング
![Datadog](https://img.shields.io/badge/Datadog-632CA6?logo=datadog&logoColor=fff&style=flat)

CI/CD
![GitHub Actions Badge](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=fff&style=flat)
![CircleCI Badge](https://img.shields.io/badge/CircleCI-343434?logo=circleci&logoColor=fff&style=flat)
![ArgoCD](https://img.shields.io/badge/Argo%20CD-1e0b3e?style=for-the-badge&logo=argo&logoColor=#d16044)

### フロントエンド

![Nuxt.js Badge](https://img.shields.io/badge/Nuxt.js-00DC82?logo=nuxtdotjs&logoColor=fff&style=flat)

### データエンジニアリング / BI

![Google BigQuery Badge](https://img.shields.io/badge/Google%20BigQuery-669DF6?logo=googlebigquery&logoColor=fff&style=flat)
![dbt Badge](https://img.shields.io/badge/dbt-FF694B?logo=dbt&logoColor=fff&style=flat)
![Looker Badge](https://img.shields.io/badge/Looker-4285F4?logo=looker&logoColor=fff&style=flat)

### その他（AI支援・ツール）

- LLM (Claude, ChatGPT API等を用いたアーキテクチャ設計・自動化パイプライン構築)
![Git Badge](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=fff&style=flat)
![GitHub Badge](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=fff&style=flat)

---

## 職務経歴詳細

### 株式会社Insight Edge （2025年6月から現在）

住友商事グループのDXを推進する技術専門会社にて、SRE / プラットフォームエンジニアとして全社横断的なシステム運用保守の自動化・高度化を主導。

OAM（運用保守）チームの第1号社員として、「開発チームが運用保守から手離れできる仕組みづくり」をミッションとし、属人化の排除とデータドリブンな運用体制の構築をゼロから提案・実装している。

**主な経験・実績:**

- **Documentation as CodeとLLMを用いた運用自動化基盤の構築**
  - 属人化していた各システムの運用保守マニュアルとサービスポートフォリオをGitHub上で一元管理する仕組みを構築。
  - GitHub ActionsのCDパイプライン上でマニュアル情報をBigQueryへ連携し、契約情報やシステム情報が自動同期・更新される「陳腐化しないドキュメント基盤」を実現。
  - LLMを活用し、CI/CDパイプライン上で運用保守マニュアルの品質を自動評価・採点・改善提案する仕組みを実装し、全社的なドキュメント品質の底上げに貢献。
- **データドリブンなSRE体制の構築（KPI/KGIの策定とダッシュボード化）**
  - 経営層・開発チーム向けに、運用保守の負荷や委託状況を定量評価する7つのKGI/KPI（開発チームの運用保守関与率、問い合わせリードタイム等）を独自に定義。
  - 上記指標をdbtのデータモデルとして実装し、Looker Studioにて毎日自動更新されるダッシュボードを構築。「なんとなく忙しい」運用を数値化し、経営の意思決定に貢献（開発チームの関与率63%、工数比率24%等を可視化）。
- **非機能要件の全社標準化とアーキテクチャガバナンス**
  - 各案件でバラバラだった非機能要件（セキュリティ、可用性、保守性）のフレームワークを独自に策定。
  - Terraform Cloudの導入必須化や、即座に利用可能なセキュリティチェックのGitHub Actions Workflowテンプレートを作成し、全社的なセキュア開発体制を推進。
  - クラウドベンダー提供のAIモデル廃止リスクに備え、全案件のAIモデル一覧の自動同期化と更新方針の策定を主導。
- **問い合わせ対応のシステム化とベンダーコントロール**
  - formrunやSlack通知を活用した問い合わせ管理台帳・対応フローを整備し、対応漏れを防止。
  - 外部委託先を巻き込んだ定型/非定型作業のエスカレーションフローを構築し、6案件の運用保守移管を完遂。週次定例にて外部ベンダーのコントロールを主導。

概要の一部をテックブログに寄稿しております。
<https://techblog.insightedge.jp/entry/ops-basis>

### 株式会社ZUU （2022年4月から2025年6月）

自社プロダクトの保守運用、新規テナント構築、新機能開発、BI開発によるマーケティング支援に従事。

#### 1. 自社プロダクト（MP Cloud）の保守運用・SRE業務

対象: 約20テナント、最大月間100万PV規模のオウンドメディア向けCMS。4名チームのリーダー。
使用技術: Go, GCP (GKE, Cloud SQL, Cloud Run 等), Terraform, Postgres, Redis, Datadog 等。

- **障害対応と根本解決**
  - サービス停止、パフォーマンス低下等、10件以上の障害対応を主導。GKEのトラブルシューティング、DBインデックス・Redis Scanに起因する遅延の解消、外部攻撃(WAF)対応など広範に解決。
  - 事後振り返り（Post-mortem）を実施し、Goのコード改修（不要なエラーログの抑止等）やインフラ構成の見直しによる根本的な再発防止策を完遂。
- **SLOベースの監視体制構築とインフラIaC化**
  - Datadogを用いたCUJ（Critical User Journey）に基づくアラート重大度判定と監視体制を構築し、ノイズを削減。
  - Terraformによる新規テナントインフラ構築手順を標準化・自動化し、構築時間を16時間から8時間へ半減。

#### 2. 新規機能・マイクロサービス開発

- **編集履歴管理マイクロサービスのアーキテクチャ設計・開発**
  - 複雑化したモノリス（MP Cloud）から機能を切り離し、Cloud Run + API Gateway + MongoDBによる独立したマイクロサービスを設計・実装。
  - コスト効率（コールドスリープ活用）と参照・書き込み特性を考慮したNoSQLの技術選定を主導し、GKE上のStatefulSetへの移管まで担当。
- **3Dセキュア認証の導入（セキュリティ強化）**
  - Go（バックエンド）とVue（フロントエンド）を改修し、決済代行業者との折衝を含めた3Dセキュア導入を主導。
  - Design Docsの作成、100件以上のテストケース作成による退行テスト・結合テストを実施し、高レベルの品質保証を実現。

#### 3. BI開発によるデータ分析基盤構築

- コンバージョン増加を目的とし、マーケティング担当者と協業。BigQuery, dbt, Looker Studioを用いてデータウェアハウスとダッシュボードを構築し、データ駆動の意思決定を支援。

### 株式会社アクア (2020年4月から2022年3月)

2つの受託開発案件にて、要件定義・設計からバックエンド/フロントエンドの開発までフルスタックに従事。自社コーポレートサイトのリニューアルも主導。

---

## SWEとしての強み

- **「運用をコードとデータで解決する」プラットフォームエンジニアリング能力**
  - 属人化しやすい運用ドキュメントや問い合わせフローを、Git、CI/CD (GitHub Actions)、データウェアハウス (BigQuery) を連携させて自動更新・自動可視化する「陳腐化しないシステム」として構築できる。
  - SREの活動をdbt等を用いて定量的なビジネスKPIとしてモデリングし、経営層や他部門が投資対効果を判断できるデータ駆動型の運用体制をリードできる。
- **モダンクラウド(GCP)と生成AIを活用した高度なアーキテクチャ設計**
  - GCPエコシステム（GKE, Cloud Run, Cloud SQL等）とGoを深く理解し、システムの要件（レイテンシ、コスト、一貫性）に応じた適切なマイクロサービス設計や技術選定（MongoDB vs RDB等）が可能。
  - AI（LLM）を単なるコーディング補助としてではなく、「ドキュメントの品質監視パイプライン」や「大規模システムの設計支援」に組み込み、1人のエンジニアの生産性をチームレベルまで引き上げるオーケストレーション能力を持つ。
- **トラブルシューティング力**
  - 分散システムの障害（ネットワーク起因、GKEの内部挙動、DBロック等）に対して、メトリクスから論理的に根本原因を特定・解消できる。
  - 対症療法で終わらせず、コードレベルの修正（Go）やIaC（Terraform）への反映、非機能要件フレームワークの策定に昇華させ、将来の技術的負債を未然に防ぐ。
- **技術力で組織にレバレッジを効かせる「Right Hand（右腕）」としての影響力**
  - 大声で政治的に立ち回るのではなく、Terraform Cloudの必須化をはじめ、「システムとルール」によって開発組織全体の品質とセキュリティをコントロールできる。
  - 外部ベンダーのフロントに立ち、ビジネス上の課題（契約上限の形骸化など）を技術運用面から発見し、上層部やPMと協調して組織構造を改善に導くことができる。

## 取得資格

- 応用情報処理技術者（2021年12月取得）
