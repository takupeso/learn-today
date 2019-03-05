
# **2019/03/04 Railsメモ**

## accepts_nested_attributes_for
    親モデルから子モデルを更新するためのメソッド
    https://olive-blog.com/post-252/
    
---
## migrationファイルreference型
    外部キーを設定するための型
    メリット2つ
        - 勝手にid指定してくれる(t.reference :userでuser_idを
          カラムに入れてくれる)
        - indexを指定してくれる    
---

## content_for
    共有レイアウトに、固定のレイアウトを打ち込むときに使う
    http://railsdoc.com/references/content_for

---

## javascript_pack_tag
    viewに入れこむJSを指定

---

## eager_load
    テーブルの外部結合を行うメソッド
    
    例：
    User.eager_load(:posts)
    => SELECT "users"."id" AS t0_r0, "users"."name" AS t0_r1, ...
    FROM "users" LEFT OUTER JOIN "posts" ON "posts"."user_id" =
    "users"."id"
---
