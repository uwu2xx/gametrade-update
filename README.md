# gametrade-update
ゲームトレードの自動更新ツール

初期設定

[config.ini]
uptime 更新速度 (分)
key APIKEYを入力してください
→ https://2captcha.com/ でアカウントを作成するとAPIKEYが発行されます
##残高がないと動きません


[tokens.txt]
更新したいアカウントのremember_tokenを入力する
[url.txt]
更新したい商品のURLを入力する


////remember_tokenの確認方法
////1.ゲームトレード内でF12を押す（デベロッパーツールを開く）
////2.applicationタブを押す
////3.cookies → gametrade.jpを押す
////4.remember tokenを探す
////5.値をtokens.txtに入力

もともと書いてあるデフォルトテキストは削除してください


複数アカウント/複数商品出品
トークン、URLを改行して２行目以降も同じように入力する
例
[url.txt]
https://gametrade.jp/aaaaa #Aのアカウントの商品URL
https://gametrade.jp/aaaab #Bのアカウントの商品URL

[token]
a2ba434cfga2ba434cfga2ba434cfga2ba434cfg #Aのトークン
4f3312abd4f3312abd4f3312abd4f3312abd4f33 #Bのトークン
