# HTTPでやりとりする仕組み

<!-- Markdown記法のヒント

コード記法（1行の中に埋めたい場合）

`code`

コードブロック記法（複数行）

```
print('a')
print('b')
```

-->

## 実習でやったこと (Y)

Gitから学習のためのノートを貰った
HTTPの仕組みを学び、神戸電子のHP(http://www.kobedenshi.ac.jp)  で確認した
ターミナルから神戸電子のHTMLをレスポンスとして貰い、それをkd.txtとしてVSCodeに開いた

## 自分で調べたこと

ポート番号についてよくわからなかったのでサーバの構造について少し調べた

## HTTPメッセージ (kd.txt) のうち、最も重要だと思う部分を貼り付けてください

```
GET /H  HTTP/1.0

HTTP/1.0 200 OK

Date: Fri, 07 Jun 2019 01:38:33 GMT

Server: Apache

X-Cached: Fri, 07 Jun 2019 01:38:34 GMT

X-Pingback: https:/xmlrpc.php

Last-Modified: Fri, 07 Jun 2019 01:38:34 GMT

X-Accel-Expires: 0

Cache-Control: max-age=300

Expires: Fri, 07 Jun 2019 01:43:33 GMT

Vary: Accept-Encoding

Connection: close

Content-Type: text/html; charset=UTF-8
```

## それはなぜですか？

何をするのかを簡潔に表している
Apache HTTPサーバー
キャッシュの設定？コンテンツの種類など

## わかったこと・気づいたこと

URLにも常に法則がある事
kd.txtは長すぎて目を通す気にならない
長い部分はHTML？->メッセージボディに当たる部分s
普通に文字化けもしている
