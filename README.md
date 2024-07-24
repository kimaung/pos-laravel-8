Cara menjalankan
```
composer update
```
atau
```
composer install
```
Copy file .env dari .env.example

```
cp .env.example .env
```
Konfigurasi file .env
```
cp .env.example .env
```
Edit File .env
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=example_app
DB_USERNAME=root
DB_PASSWORD=
```
generate Key
```
php artisan key:generate
```
Migrate database

```
php artisan migrate
```
Seeder table User, Pengaturan

```
php artisan db:seed
```
Running
```
php artisan serve
```
