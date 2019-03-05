# **2019/03/01 Railsメモ**

## link_to, form_forにremote: true
    リクエストがhtml型ではなく,js型
    レスポンスは、アクション名.html.erbではなく、アクション名.js.erbを参照する
---

## ControllerにModelの処理を書かない
    困ったら、moduleに書く、Controllerを分割する
---

## target="_blank"
    別ウィンドウを開く属性
---

## selectタグ　いっぱいある
    select
    f.select
    collection_select
    select_tag ←紐付けオブジェクトがないときはこれ使う
