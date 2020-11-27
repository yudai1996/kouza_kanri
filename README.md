アプリケーション名:kouza_kanri

アプリケーション概要
管理側：講座申込時の申込者の確認
ユーザー側：開講中の講座の確認、講座への申し込み、マイページでの受講関連情報の確認・編集

URL：未デプロイ

テスト用アカウント：機能実装後設定

利用方法

1: アカウントの作成

2: トップページでの開講中講座一覧の閲覧

3: 講座一覧より各講座の詳細ページへの遷移（講座日程、必要資格、料金などの情報閲覧）

4: ヘッダーよりマイページへの遷移、アカウント登録時の商法確認（所持資格、生年月日、受講履歴の確認ができる）

5: アカウント情報の編集機能、資格取得による情報の更新が行える

6: 受講票作成フォーム、受講決定時に自身で受講票を作成。印刷できる

目指した課題解決

講座申し込み側、受付側ともに紙やFAXなどの(受講票の作成や郵送も含め)手間のかかる業務を効率的に管理、作成を行いたい、という課題を解決する為に作成

洗い出した要件(詳細URL:https://docs.google.com/spreadsheets/d/1pLe3_Oehxu4ioeWA2bS440pqpFfpuHdTu1dd5LoC-C8/edit#gid=282075926)

```
| 機能                   　   | 
| -------------------------- | 
| ユーザー管理機能      　       | 
| 申し込みフォーム            　　|  
| 受付中の講座一覧の表示      　 | 
| 講座の詳細ページ            　| 
| 受講票作成フォーム            | 
| マイページの編集機能       　　| 

```
実装した機能についてのGIFと説明:実装後記述

実装予定の機能	通知機能(受付完了等)の実装

データベース設計	ER図作成後添付

ローカルでの動作方法	git cloneしてから、ローカルで動作をさせるまでに必要なコマンドを記述しましょう。この時、アプリケーション開発に使用した環境を併記することを忘れないでください（パッケージやRubyのバージョンなど）。
