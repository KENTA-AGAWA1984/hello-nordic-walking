## アプリケーション名
 Hello, NordicWaliking

## アプリケーション概要
 エンジニアにノルディックウォーキングを習慣化させるアプリ
## URL
 ※現在アプリケーション作成中のため、完成次第追記致します。
## テスト用アカウント	
 ※現在アプリケーション作成中のため、完成次第追記致します。
## 利用方法

### ローカルにアクティビティのログをDL
 1. GarminデバイスのモバイルアプリGarmin Connectのログを使用
 2. DLしたい任意の期間を指定しフォームに入力
 3. トグルスイッチのレバーを右に → DL開始

### パフォーマンス統計の可視化
 1. ※ DLデータのグラフ化を実装予定

## アプリケーションを作成した背景
 作成の背景は二つあります。
1. ノルディックウォーキングの普及がシニア層に偏っており、本来このスポーツの恩恵を受けるべき層に普及が進んでおりません。ですが、発祥国であるフィンランドや日本国内では長野など、クロスカントリースキー（歩くスキー）が普及している地域ではサマーシーズンのトレーニングとして重宝されており、全身の骨格筋の90%を使用する有酸素運動として認知されています。この普及率の違いは「身体がスキーの経験を獲得しているか否かである」と考えました。そこでスキーの経験が不足している部分を、統計データを援用することで普及を促したいという目的があります。
2. 上記の問題設定でアプリ開発を進めた時、懸念されるのは「運動記録の統計データに関心を持つユーザーがどれだけいるのだろう？」という点です。そこで、日々データやアルドリズムに向き合っているエンジニアにTGTを設定しました。また、座位での業務時間が長いエンジニアにとって、関節の負荷を抑えながら全身運動が行えるノルディックウォーキングは最適なワークアウトになります。また自身の運動記録を統計データとして分析し、改善策を考えるプロセスは、本業のプロジェクトを進めるプロセスの洗い出しにも応用出来ます。以上の内容から企画、開発を進めることにしました。

## 洗い出した要件	
https://docs.google.com/spreadsheets/d/1PEFxZLvsJUrImqYwvxRdSfcNKipthk_80F1jaBarYDo/edit#gid=982722306

## 実装した機能についての画像やGIFおよびその説明


## 実装予定の機能	
 ※ DLデータのグラフ化を実装予定

## データベース設計
https://user-images.githubusercontent.com/102355885/183355008-0d4d9a1f-ffd2-4b0e-8b13-96bc5c77b449.png

## 画面遷移図


## 開発環境
1. java
2. PostgreSQL

## ローカルでの動作方法

## 工夫したポイント
1. DLをバックグラウンド処理で行うことで、PC作業と並行して実行出来る
2. 取り込んだデータのグラフ化は、必要な分析フェイズなので画面で視覚的に表現したい

