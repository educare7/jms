# job Matching System(JMS)
PHP自作

## 概要
マッチングアプリの形式で仕事探しに応用できそうなアプリを作成いたしました。
マルチログイン機能により、管理者ユーザー・一般ユーザー・企業ユーザーに分けてのユーザー登録およびログインが可能です。

## 使い方
・管理ユーザー
新規登録
退会(ユーザー情報が削除されます。復元不可。)
登録情報の変更(ユーザー種別は変更不可)
ユーザーとのマッチング(すでにスワイプしたユーザーと自分と同一のユーザー種別のユーザーは非表示)
マッチしたユーザーとのリアルタイムチャット
パスワードリセット
ログアウト
ユーザー一覧の取得とユーザー削除
お問い合わせ一覧の表示と詳細確認
【テストアカウント】
    メールアドレス:admin@example.com
    パスワード:12345678
    
・一般ユーザー
新規登録
退会(ユーザー情報が削除されます。復元不可。)
登録情報の変更(ユーザー種別は変更不可)
ユーザーとのマッチング(すでにスワイプしたユーザーと自分と同一のユーザー種別のユーザーは非表示)
マッチしたユーザーとのリアルタイムチャット
パスワードリセット
ログアウト
お問い合わせの投稿
【テストアカウント】
    メールアドレス:user1@example.com ~ user5@example.com
    パスワード:12345678
    
・企業ユーザー
新規登録
退会(ユーザー情報が削除されます。復元不可。)
登録情報の変更(ユーザー種別は変更不可)
ユーザーとのマッチング(すでにスワイプしたユーザーと自分と同一のユーザー種別のユーザーは非表示)
マッチしたユーザーとのリアルタイムチャット
パスワードリセット
ログアウト
お問い合わせの投稿
【テストアカウント】
テストアカウント
    メールアドレス:company1@example.com ~ company5@example.com
    パスワード:12345678
    
## 環境
XMAMP/MySQL/PHP
## データベース
データベース名：educare7

テーブル

お使いのphpMyAdminに上のデータベースを作り、上に入っているeducare7.sqlをインポートしていただければお使いいただけるようになると思います。
