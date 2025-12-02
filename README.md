### Hi there 👋
<p align="left">
  <a href="http://qiita.com/UserKazun">
    <img height="20" src="https://qiita-badge.apiapi.app/s/UserKazun/posts.svg" />
  </a>
  <//qiita.com/UserKazun">
    <img height="20" src="https://qiita-badge.apiapi.app/s/UserKazun/contributions.svg" />
  </a>
</p>

X: https://twitter.com/developer_kazu<br>
zenn: https://zenn.dev/userkazun 


<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://golang.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="go" width="40" height="40"/> </a> <a href="https://laravel.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/laravel/laravel-plain-wordmark.svg" alt="laravel" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.nginx.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" alt="nginx" width="40" height="40"/> </a> <a href="https://www.php.net" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/> </a> <a href="https://developer.apple.com/swift/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/swift/swift-original.svg" alt="swift" width="40" height="40"/> </a> </p>



# 職務経歴書

## 株式会社 PR TIMES（2020年4月 ～ 現在）

---

### 概要
Webクリッピング関連プロダクトの開発と運用をリード。フロントエンドからインフラ、テスト自動化、DB移行に至るまで幅広く対応し、プロジェクト推進とチーム連携にも注力。

---

### 主な実績

#### 🔧 管理画面の実装（2020年4月 ～ 2021年4月）
- **技術**: PHP, Docker, GitHub
- **アーキテクチャ**: レイヤード＋クリーンアーキテクチャの社内パターンを理解・適用
- **成果**:
  - [社内ボイラープレートを用いた開発](https://developers.prtimes.jp/2021/05/10/boilerplate_dev/)
  - [DDDとクリーンアーキテクチャをちょっとだけ理解した](https://qiita.com/UserKazun/items/e1ab9a7ed33898dd9005)
  - [なぜドメインモデルを採用するのか?](https://qiita.com/UserKazun/items/32889f680aab41e84a15)

#### 🚀 Webクリッピングβ版リリース（2021年11月 ～ 2022年4月）
- **技術**: PHP, Docker, Amazon ECS
- **内容**:
  - 既存UIを刷新し、β版として新規公開
  - [提供開始リリース](https://prtimes.jp/main/html/rd/p/000001209.000000112.html)
  - [開発に必要な気付き記事](https://prtimes.jp/story/detail/MxzRjfL2QxE)

#### 👥 チームリーダーとして開発推進（2021年8月 ～ 2023年2月）
[サービス紹介](https://prtimes.jp/webclipping/service/)
- デイリーミーティング改善やタスク管理の導入
- メンバーのタスクマネジメント
- 他チームや部署との連携やスケジュール調整など

#### 🔄 ステージング・インフラ整備（2022年）
- **ステージング環境復旧**（6月）：Amazon EC2 の根本原因調査・修正
- **マルチステージング導入**（10月）：Terraform＋ECSで他チーム環境を参考に構築

#### ✅ テスト環境構築とCI自動化（2022年11月）
- **技術**: PHP, PHPUnit, GitHub Actions
- テストが存在しなかったレガシー環境に対してCI/CDパイプラインを整備

#### 💼 正式版リリースと完全移行（2022年11月 ～ 2023年7月）
- **技術**: PHP, Docker, Amazon ECS
- β版を有料版としてリリースし、追加機能を実装して完全移行を達成

#### 🛠 MySQL メジャーバージョンアップ（2023年9月）
- **技術**: PHP, Amazon RDS for MySQL
- アップグレード対応および互換性・文字コードの検証と対応

#### 🔁 MongoDB → DocumentDB 移行（2024年1月）
- **技術**: PHP, MongoDB, Amazon DocumentDB
- 移行理由：高運用コストのMongoDBからAWS管理のDocumentDBへ
- データ移行スクリプト作成（MongoDB → CSV → DocumentDB）
- [詳細ブログ記事](https://developers.prtimes.jp/2024/03/07/migrate-mongodb-ec2-to-documentdb/)

#### ✨ クリッププレビュー機能実装（2024年6月 ～ 2024年8月）
- **フロント**: React, TypeScript, Playwright, vitest, Storybook, OpenAPI
- **バックエンド**: PHP
- 一貫して仕様策定・実装・QA対応まで実施
- [学びの共有記事](https://developers.prtimes.jp/2024/09/06/frontend-challenge-learnings/)

#### OpenAI を使用した機能開発(2024年11月〜2025年3月)
- **フロントエンド**：React / TypeScript / Playwright / Vitest / Storybook / OpenAPI
- **バックエンド**：PHP / MySQL
- **開発機能概要**：
数千記事の記事データを OpenAI に読み込ませ、頻出かつユニークなキーワードの抽出を実施。
抽出したキーワードが記事内でどのような文脈で利用されているかを解析し、可視化したデータとしてユーザーに提供する機能を開発。

- **担当業務・技術的取り組み**：
  - 数千記事のデータを OpenAI に分析するためのリクエスト形式やそれのレスポンスを確認する PoC
  - OpenAI API Batch API を使用するジョブキュー基盤の設計・実装（PHP によるバッチ処理、MySQL によるキュー管理テーブルの設計）
    - 今回の機能要件に応じて OpenAI Batch API を採用し、Batch API 実行後の結果を取り込み DB へ保存するバッチ処理を実装
  - Batch API リクエストで使用する JSONL ファイル生成バッチの開発
  - 解析結果をユーザーに提供するためのバックエンド API を設計・実装
  - 当該 API を用いてデータを可視化するフロントエンドの実装全般を担当

---

## 業務外活動

### ✅ OSS 活動
- [TaskManager_Sample](https://github.com/UserKazun/TaskManager_Sample)
- [SwiftUIT](https://github.com/UserKazun/SwiftUIT)
- [Laravel へのコントリビュート](https://github.com/laravel/framework/pull/46802)

### 🎤 技術イベント登壇
- [PHPerkaigi 2022 登壇内容](https://fortee.jp/phperkaigi-2022/proposal/c5e23ffc-4645-47d2-b6b8-5df1ac75d613)
- [発表資料（SpeakerDeck）](https://speakerdeck.com/userkazun/phperkaigi2022-mongo-niliu-matutayue-1-dot-6yi-jian-falseji-shi-detawo-bigquery-he-dot-dot-dot)

### 🛠 個人開発
- SQL → QueryDSL 変換CLI：[qc](https://github.com/UserKazun/qc)（Go）
- [画像投稿サービス](https://github.com/UserKazun/valorant-fm)（PHP/Nginx）

### 📺 SwiftUI学習共有
- [YouTubeチャンネル](https://youtube.com/channel/UCJU4PjuyIEL43CTlPSFjW5Q)

