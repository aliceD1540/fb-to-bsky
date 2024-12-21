## なにこれ

Facebookの最新投稿の画像を取得してBlueskyにポスト、 
要は某ゲーム機のスクショをBlueskyに投稿するための補助ツールです。

## 一連の想定操作

1. 某ゲーム機からスクショをFacebookに投稿（非公開でOK）
2. 本ツールで最新投稿を取得
3. コメントを加えてBlueskyに投稿

## 使い方

1. .env に各種設定値をセット
    - 要Facebook Developer登録
2. `python3 main.py` でサーバを起動

### Render上で動かす場合は以下の通り設定

- Language
    - Python 3
- Build Command
    - `pip install -r requirements.txt`
- Start Command
    - `flask run`
- Environment
    - .env の設定を転記
