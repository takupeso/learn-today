
# **2019/03/02 Railsメモ**

## respond_to
    レスポンスのフォーマットをしてするメソッド
    
---
## collection_select
    DBの値を元に選択肢を作成してくれるヘルパー
    
    例：
    <%= collection_select(:page, :name, @categories, :id, :name) %>
---

## eager_load
    テーブルの外部結合を行うメソッド
    
    例：
    User.eager_load(:posts)
    => SELECT "users"."id" AS t0_r0, "users"."name" AS t0_r1, ...
    FROM "users" LEFT OUTER JOIN "posts" ON "posts"."user_id" =
    "users"."id"
---

## map
    要素の数だけブロックを実行し、ブロックの戻り値を要素にした配列を返すメソッドs
    array.map {|item| block }
    
    例：
    numbers = ["68", "65", "6C", "6C", "6F"]
    p numbers.map {|item| item.to_i(16) }

---

## eager_load
    テーブルの外部結合を行うメソッド
    
    例：
    User.eager_load(:posts)
    => SELECT "users"."id" AS t0_r0, "users"."name" AS t0_r1, ...
    FROM "users" LEFT OUTER JOIN "posts" ON "posts"."user_id" =
    "users"."id"
---
