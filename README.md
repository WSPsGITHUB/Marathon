"# Marathon"

git clone https://github.com/WSPsGITHUB/Marathon.git<br/>
cd Marathon<br/>
composer install<br/>

shell : cp .env.example .env<br/>
or<br/>
ms-windows : copy .env.example .env<br/>

"# phpmyadmin create database, only doing once"<br/>
DB name:marathon<br/>
select:utf8mb4_unicode_ci<br/>

php artisan key:generate<br/>

--無資料庫時才輸入下兩行--<br/>
php artisan migrate<br/>
php artisan db:seed<br/>

php artisan serve<br/>
