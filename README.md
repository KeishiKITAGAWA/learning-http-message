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
Request URL: https://www.kobedenshi.ac.jp/
Request Method: GET
```

## それはなぜですか？

何をするのかを簡潔に表しているため

## わかったこと・気づいたこと

URLにも常に法則がある事
kd.txtは長すぎて目を通す気にならない
長い部分はHTML？->メッセージボディに当たる部分s
普通に文字化けもしている
