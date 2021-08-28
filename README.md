# rails newする
## APIモードの時
 `docker-compose run web rails new . --force --database=mysql --skip-bundle --api`
## デフォルトの時
 `docker-compose run web rails new . --force --database=mysql --skip-bundle`

# `docker-compose build`

# database.yml を編集
https://qiita.com/Yusuke_Hoirta/items/3a50d066af3bafbb8641#databaseyml-%E3%82%92%E7%B7%A8%E9%9B%86

# `docker-compose up -d`

# `docker-compose exec web rails db:create`


## 参考: https://qiita.com/Yusuke_Hoirta/items/3a50d066af3bafbb8641