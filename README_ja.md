# <p align="center"> 👗 AIバーチャル試着 🚀✨</p>

<p align="center">AIバーチャル試着では、ローカルでのアップロードまたはAI生成のモデル画像と衣装画像を使用して、自由にモデルと衣装を選択し、AIによる試着画像を生成することができます。</p>

<p align="center"><a href="https://302.ai/ja/tools/tryon/" target="blank"><img src="https://file.302.ai/gpt/imgs/github/20250102/72a57c4263944b73bf521830878ae39a.png" /></a></p >

<p align="center"><a href="README_zh.md">中文</a> | <a href="README.md">English</a> | <a href="README_ja.md">日本語</a></p>


![](docs/302_AI_Virtual_Try_On_jp.png)

[302.AI](https://302.ai/ja/)の[AIバーチャル試着](https://302.ai/ja/tools/tryon/)のオープンソース版です。
302.AIに直接ログインすることで、コード不要、設定不要のオンライン体験が可能です。
あるいは、このプロジェクトをニーズに合わせてカスタマイズし、302.AIのAPI KEYを統合して、自身でデプロイすることもできます。

## インターフェースプレビュー
モデルの説明とパラメータ設定に基づいて、AIでモデル画像を生成するか、ローカルからモデル画像をアップロードします。モデル画像は右側に表示されます。
![](docs/302_AI_Virtual_Try_On_jp_screenshot_01.png)       

衣装の説明とパラメータ設定に基づいて、AIで衣装画像を生成するか、ローカルから衣装画像をアップロードします。衣装画像は右側に表示されます。
![](docs/302_AI_Virtual_Try_On_jp_screenshot_02.png)        

試着に使用するモデルを選択し、AIバーチャル試着を開始します。
![](docs/302_AI_Virtual_Try_On_jp_screenshot_03.png)      

HD画質機能で、画像をより鮮明にします。
![](docs/302_AI_Virtual_Try_On_screenshot_04.jpg)        

背景除去機能で、ワンクリックで画像の背景を削除できます。
![](docs/302_AI_Virtual_Try_On_screenshot_05.jpg)    

二次ライティング機能では、ライティングの説明を入力するか背景画像をアップロードし、光源の方向を選択することで、画像に二次ライティングを適用できます。
![](docs/302_AI_Virtual_Try_On_screenshot_06.png)     

二次ライティング適用後の試着画像。
![](docs/302_AI_Virtual_Try_On_screenshot_07.jpg) 


## プロジェクトの特徴
### 👚 モデル画像
モデルの説明とパラメータ設定に基づいて、AIでモデル画像を生成するか、ローカルからアップロードすることができます。
### 🙎‍♂️ 衣装画像
衣装の説明とパラメータ設定に基づいて、AIで衣装画像を生成するか、ローカルからアップロードすることができます。
### 🧚 AIバーチャル試着
使用したいモデルを選択するだけで、AIバーチャル試着を開始できます。
### 🖼️ HD画質
試着画像生成後、AIを使用して画像をより鮮明で高品質にします。
### ✂️ 背景除去
試着画像生成後、AIを使用して背景を除去します。
### 🔦 二次ライティング
試着画像生成後、AIを使用して二次ライティングを適用します。
### 📜 履歴記録
作成履歴を保存し、記録を失うことなく、いつでもどこでもダウンロードできます。
### 🌓 ダークモード
ダークモードをサポートしており、あなたの目を保護します。
### 🌍 多言語サポート
- 中国語インターフェース
- 英語インターフェース
- 日本語インターフェース


## 🚩 将来のアップデート計画
- [ ] トップスとボトムスを同時に選択し、全身コーディネートを実現する機能


## 🛠️ 技術スタック

- **フレームワーク**: Next.js 14
- **言語**: TypeScript
- **スタイリング**: TailwindCSS
- **UIコンポーネント**: Radix UI
- **状態管理**: Jotai
- **フォーム処理**: React Hook Form
- **HTTPクライアント**: ky
- **国際化**: next-intl
- **テーマ**: next-themes
- **コード規約**: ESLint, Prettier
- **コミット規約**: Husky, Commitlint

## 開発&デプロイ
1. プロジェクトのクローン
```bash
git clone https://github.com/302ai/302_virtual_try_on
cd 302_virtual_try_on
```

2. 依存関係のインストール
```bash
pnpm install
```

3. 環境設定
```bash
cp .env.example .env.local
```
必要に応じて`.env.local`の環境変数を修正してください。

4. 開発サーバーの起動
```bash
pnpm dev
```

5. プロダクションビルド
```bash
pnpm build
pnpm start
```


## ✨ 302.AIについて ✨
[302.AI](https://302.ai/ja/)は企業向けのAIアプリケーションプラットフォームであり、必要に応じて支払い、すぐに使用できるオープンソースのエコシステムです。✨
1. 🧠 包括的なAI機能：主要AIブランドの最新の言語、画像、音声、ビデオモデルを統合。
2. 🚀 高度なアプリケーション開発：単なるシンプルなチャットボットではなく、本格的なAI製品を構築。
3. 💰 月額料金なし：すべての機能が従量制で、完全にアクセス可能。低い参入障壁と高い可能性を確保。
4. 🛠 強力な管理ダッシュボード：チームやSME向けに設計 - 一人で管理し、多くの人が使用可能。
5. 🔗 すべてのAI機能へのAPIアクセス：すべてのツールはオープンソースでカスタマイズ可能（進行中）。
6. 💪 強力な開発チーム：大規模で高度なスキルを持つ開発者集団。毎週2-3の新しいアプリケーションをリリースし、毎日製品更新を行っています。才能ある開発者の参加を歓迎します。