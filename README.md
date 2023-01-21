larabel構築手順

①下記のcommandを実行しlarabelのソースを取得する
docker-compose run php composer create-project --prefer-dist laravel/laravel .

②下記のcommandを実行しdocker-composeからコンテナを構築する
docker-compose up

③dockerコンテナのworkspace_php_laravel_phpに入り、下記のcommandを実行
chmod -R 777 /var/www/html/storage