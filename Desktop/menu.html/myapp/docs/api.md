# 学食メニューアプリ API仕様書

## GET /api/menus

登録されている学食メニューを一覧取得する。

### レスポンス例

[
{
"id": 1,
"menu_name": "唐揚げ定食",
"price": 890,
"comment": "うますぎわろた",
"created_at": "2026-06-24T10:00:00.000Z"
}
]

---

## POST /api/menus

新しい学食メニューを登録する。

### リクエスト例

{
"menu_name": "焼肉定食",
"price": 990,
"comment": "こいてやべえ"
}

### レスポンス例

{
"id": 2,
"menu_name": "焼肉定食",
"price": 990,
"comment": "こいてやべえ",
"created_at": "2026-06-24T10:05:00.000Z"
}
