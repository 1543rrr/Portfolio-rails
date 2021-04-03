# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

### 必要な情報の洗い出し
## - サインアップ/サインイン機能
# - 投稿機能
# - いいね機能
# - コメント機能

# テーブル設計
# users table
|id|
|name|
|email|
|password|
|password_confirmation|

# comments table
|id|
|comment|
|post_id|
|user_id|

# posts table
|id|
|caption|
|user_id|

# likes table
|id|
|post_id|
|user_id|

# photos table
|id|
|image|
|post_id|
