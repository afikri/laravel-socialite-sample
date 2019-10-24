## How to get the sample running
1. run ```composer install```
2. do `cp .\.env.example .env`
3. generate encryption key by `php artisan key:generate` 
4. change 
```
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=
```
to fit the database
