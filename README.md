# TUT App Portal

学生ポータルのお知らせを自動で通知するソフトウェア

↓↓ヘルプや改善案についてはこちらのDiscordサーバーから

https://discord.gg/hqC3PUrT


追記: C#やその他何か知識, 技術等を提供していただける方を募集しています → https://discord.gg/hqC3PUrT

# プレビュー

ソフトのメイン画面

![](https://i.gyazo.com/530f60a08d2fb25690ab8710c486fea7.png)



# 機能

* お知らせの通知
* Discord Webhookでお知らせの内容を送信可能
* PC起動時に自動でソフトが起動
* バックグラウンド処理にも対応
* さらに（今後のアップデートで追加）

# 必須要件

* Windows 10 or 11
* Microsoft Edge

# ダウンロードと使用方法

Releases から TUTAppPortal_X.X_Release.zip をダウンロードし、解凍してください。
解凍後は「TUT App Portal.exe」をダブルクリックし、実行します。

```bash
1, ダウンロード: TUTAppPortal_X.X_Release.zip
2, 解凍/展開: TUTAppPortal_X.X_Release.zip
3, 起動する: TUT App Portal.exe（アプリケーション）
```

# ソースコードについて
容量の制限によりGoogleドライブにて公開しています。

https://drive.google.com/drive/folders/1BnOLcJccbGKxe1o8n8DLV_4QKyIyfB8d?usp=sharing

# 必ず読んでください
（TUT App Portal は名前が長いため、ここでは TUTAP と置き換える）

### 1. 情報
* 1.1 ユーザー情報について
TUTAP はユーザーがログインするアカウント情報（ユーザー名、学籍番号、メールアドレス、パスワードなど）を一切、収集致しません。

### 2. セキュリティ
* TUTAP はオープンソースとなっています。この公式Github以外でダウンロードした TUTAP は危険な可能性があります。自己責任でお願い致します。

### 3. 注意事項
* TUTAP に関連するトラブルや破損等は一切の責任を負わないものとします。
* オープンソースにおいて危険なことは、TUTAP が悪意あるソフトウェアに作り替えることも可能であることです。これにより悪意のある開発者やそのような悪意あるものを配布する人たちが出てきてしまう可能性があります。そのため改めて記述いたしますが、この公式Githubページ以外の場所でのダウンロードは推奨いたしません。

### 3. 変更
* TUTAP開発者 は必要に応じて「必ず読んでください」の内容を変更する権利を保有します。変更がある場合は、Readmeの一番上に書き込みます。

### 4. お問い合わせ先
* TUTAP の「必ず読んでください」に関するご質問やお問い合わせがある場合は、以下の連絡先までお願いいたします。

https://discord.gg/hqC3PUrT

# メモ

Windowsのみの対応です。
要望があれば、、別バージョン作ります(白目)

また、C#やその他何か知識, 技術等を提供していただける方を募集しています。上記のお問い合わせ先からお待ちしております。


# 使用しているライブラリ
* Microsoft.Playwright
* FontAwesome.Sharp
