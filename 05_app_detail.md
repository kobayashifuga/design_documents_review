＃全体
- トップページがない

- admin,userで分けていない

- デバイスに関するURL等の記載がない
  - [check]OKですが、"devise"と表記しましょう。端末などの意味を表すデバイスなのか、gemの"devise"なのか、混乱してしまいます。

- disc,song,artist,label,genreが存在しない

＃orders
- indexとnewのURLが同じ


＃User
- 退会が物理削除になっている

- 退会完了について詳細設計に書かれていない

[add]
## ワイヤーフレーム上にあるページのURLが存在しない
- お届け先住所変更ページ
- 支払い方法の確定画面
- ユーザーの退会確認

## ワイヤーフレーム上にないページのURLが記載されている
- カートの編集

## order_details
- order_detailsテーブルの情報は、ordersテーブルと同時にデータ作成を行うため、ordersコントローラーでまとめて記述可能

## admins
- show/editでURLが重複
