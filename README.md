# 👋 Hello, I'm Daiki Kaneda
モバイル・バックエンド開発を勉強中の学生エンジニアです。

## 🚀 Technical Interests & Stack

- **Mobile:** Flutter (Riverpod)
- **Backend:** TypeScript (Node.js), Spring Boot, Java
- **Infrastructure:** AWS (Serverless Architecture, AWS CDK, Fargate)
- **Frontend:** Next.js, React
- **Architecture & Practices:** Domain-Driven Design (DDD), CI/CD (GitHub Actions)

## 📚 Certifications & Goals

以下が取得した資格と取得目標の資格です：

- ✅ **Java SE 11 Gold** (Certified Professional)
- ✅ **Java SE 11 Silver**
- ✅ **AWS Solutions Architect - Associate (SAA)**
- ✅ **AWS Certified Developer – Associate (DVA)**
- ✅ **AWS Certified CloudOps Engineer - Associate**
- ✅ **AWS Certified Solutions Architect – Professional (SAP)**
- [] AWS Certified DevOps Engineer - Professional 

## 🎨 Portfolios
- **[WIP] [短~中編小説生成ワークフロー](https://github.com/daiki-kaneda/novel-generator)**
  StepFunctionsを用いた小説生成ワークフロー. 初めは長期コンテキストを維持するのが困難だったが、知識グラフ（TKG)などを取り入れることで解決。また、具体的なプロットを作成することによる不自然な展開を抑えるために、章作成ごとにプランや知識グラフを微調整するDOME方式や大まかなプロットと章作成の直前で作る詳細なプロットの二重アウトラインを導入することで自然な展開にできた。
  参考文献
  [Generating Long-form Story Using Dynamic Hierarchical Outlining with Memory-Enhancement](https://aclanthology.org/2025.naacl-long.63/) (Wang et al., NAACL 2025)

- **[WIP] [習慣化・ご褒美管理アプリ (Treat Management)](https://github.com/daiki-kaneda/treat-log)**
  Flutter × TypeScript × AWS CDK (Lambda, DynamoDB, Cognito) で構築中。楽観的UIやDDD（ドメイン駆動設計）を取り入れた堅牢な状態管理と、インフラのIaC化（コード化）に挑戦しています。EventBridge Scheduler+SNSでのプッシュ通知の実装やDynamoDBのGSIを工夫した匿名認証も導入しています。

- **[Dota2 Tier List Web App](https://github.com/daiki-kaneda/dota2-tier-list-app)**
  Flutter Web × Spring Boot × AWSサーバーレスで作った毎日更新するティアリスト。

## 🌱 More Projects & Learning History 
<details>
<summary>こちらをクリックしてください</summary>

### 🍃 Spring Boot (AIコーディング不使用)
- **[ギャンブル性のあるシンプルなゲームAPI](https://github.com/daiki-kaneda/fizz-buzz-combo)**: ユーザが初めに選ぶルールとランダムに生成される数字によって得点が決まるので、戦略性とギャンブル性があり、面白いと思い、作りました。
- **[数独API](https://github.com/daiki-kaneda/sudoku-app-api)**: ユーザ認証、データベースの正規化のいい練習になりました
- **[ゲームアイテムトレードAPI](https://github.com/daiki-kaneda/fantasy-trade-api)**: ユーザ認証、悲観ロックのいい練習になりました
- **[部屋予約システムAPI](https://github.com/daiki-kaneda/room-reservation-system-api)**: FirebaseAuthによる認証を組み込むいい練習になりました
- **[TacoCloud](https://github.com/daiki-kaneda/taco-cloud)**: Spring in Actionという本を読みながら最初に作ったSpringBootアプリです
- **[認証付きTODOアプリ](https://github.com/daiki-kaneda/todo-auth-demo)**: 反復練習用
- **[認証付きメモアプリ](https://github.com/daiki-kaneda/memoapp-auth-demo)**: 反復練習用
- **[チーム数独API](https://github.com/daiki-kaneda/team-sudoku-api)**: マルチプレイの数独API。Websocketを直接使わず、Supabase Realtimeを使用して、開発コストを下げています。
  

### 🧱 Terraform学習（AIコーディング不使用）
- **[Terraform基礎学習](https://github.com/daiki-kaneda/terraform-basic)**: Lauro Müller先生の[Udemyのコース](https://www.udemy.com/course/mastering-terraform-beginner-to-expert/)を進めて作ったものです。 
  - **[公開練習用のモジュール](https://registry.terraform.io/modules/daiki-kaneda/networking-tf-course/aws/latest)**

### 📱 Flutter Apps & Learning

- **[Flutter Learning Repository](https://github.com/daiki-kaneda/flutter-ui-study)**: FlutterのUIやパッケージの学習、実験的なUIの作成(experimentsディレクトリ配下)などを多く行いました。
- **[ディクテーションアプリ](https://github.com/daiki-kaneda/dict_app)** かなり時間をかけて作ったディクテーション学習用モバイルアプリ. (AIコーディング不使用)クラウドを本格的に学ぶ前だったので、ユーザーが音声ファイルを選択->STT(Speech to Text) APIで単語ごとの秒数なども分析した結果を取得->それを使ってディクテーション問題を作成という様にしています。UIにこだわったので、いつかAWSなどのクラウドを使って新しいリポジトリで作り直したいと思っています。
- **[プラットフォーマーゲームアプリ](https://github.com/daiki-kaneda/bit_math)**: FlameというDart,Flutterを使うゲームフレームワークを使用して作ったゲームです。小さなキャラクターを動かして、正解のブロックに頭をぶつける算数学習ゲームです。
- **[その他公開しているアプリなどはこちら](https://apps.apple.com/jp/developer/daiki-kaneda/id1675602625)**: これらのアプリはAWSなどのクラウドを使わずに作ったものなのであまり機能は多くありません😓 審査の間のやり取りなどは多くの学びがありました。 

### 🧪 Experimental Projects
以前から作成に興味があったプロジェクトを作っています。(AI Agent使用)
- **[論文要約音声作成アプリ](https://github.com/daiki-kaneda/fargate-worker)**: arxivなどの論文のpdfをBedrockのClaudeなどに直接渡して要約->再びBedrockでAmazon Pollyで高品質な音声を作成できるようにSSMLに変換->Pollyで音声化->メールで通知という様にしています。　開発中のコストを最適化するために、FargateはSQS内のメッセージ数が実行中のものも含めて0の時にキャパシティを0にする様にしています。
- **[Remotionによる動画生成アプリ](https://github.com/daiki-kaneda/video-generation)**: Remotion+Fargateを使用した動画生成アプリ. RemotionはReactベースで動画生成自体にAIを使用しないので、コストを最適化しつつ、様々な動画を作れる様に実験中。
- **[日本語数学解説動画作成プロジェクト](https://github.com/daiki-kaneda/manim_study/tree/main/project/curriculum_math_150)**: Pythonの動画生成フレームワークのManimを使って、日本語の数学解説動画を作るプロジェクト. 現在150本分のカリキュラムは作成済みで、初めの２０本分は実際に動画作成済み。

### 📝 Others
- **[Kerasでの猫画像品種分離モデル訓練](https://colab.research.google.com/drive/1yd_lexqWXJErQFGdv41Snt9l9fLOhyni?usp=sharing)**: 定番の教科書である[Deep Learning with Python](https://www.manning.com/books/deep-learning-with-python-third-edition)をハンズオンしながら読み終えた後,訓練したモデル。
- **[数独ソルバー](https://github.com/daiki-kaneda/sudoku_solver)** 自分が中学生の頃Haskellを学んだ時の[教科書](https://people.cs.nott.ac.uk/pszgmh/pih.html)の著者である[Graham HuttonのYoutubeチャンネル](https://www.youtube.com/@haskellhutt)でのHaskellの数独ソルバーをSwiftで書き直してみたもの。
</details>