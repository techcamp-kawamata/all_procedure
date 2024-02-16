# README

## Usersテーブル

|Column             |Type   |Options                   |
|-------------------|-------|--------------------------|
|last_name          |string |null: false               |
|first_name         |string |null: false               |
|last_name_kana     |string |null: false               |
|first_name_kana    |string |null: false               |
|email              |string |null: false, unique: true |
|encrypted_password |string |null: false               |
|birthday           |date   |                          |
|address            |string |                          |
|occupation         |string |                          |
|department         |string |                          |
|post               |string |                          |

※imageはActiveStrageで実装するため含まない
### Association

## pagesテーブル
