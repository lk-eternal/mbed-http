# mbed-http:

## 機能
http/https機能(S3ダウンロードとアップロード)

## ベースソースコード
https://developer.mbed.org/teams/sandbox/code/mbed-http/#6daf67a96a91

## 変更内容
- 受信途中で接続が切れるのを防止するために、タイムアウトを設定する
- Transfer-Encoding：chunkedなしでファイルを少しずつアップロードする機能追加

## 差分ファイル
- \source\https_request.h.html
- \source\http_request_base.h.html
- \source\http_request_builder.h.html