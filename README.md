# README

## テーブル構成

### usersテーブル

| column | data type |
| --- | --- |
| name | string |
| email | text |
| password_digest | text |

### picturesテーブル

| column | data type |
| --- | --- |
| image | text |
| user_id | integer |

### favoritesテーブル

| column | data type |
| --- | --- |
| user_id | integer |
| picture_id | integer |
