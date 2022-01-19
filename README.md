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


## ER図
<img src="https://user-images.githubusercontent.com/24279672/150081334-25eebbf0-e670-4b9f-be9c-4b650173baad.jpg" width="500">
