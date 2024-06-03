
## SQLITE

## Installing Laravel Breeze
 ```
composer require laravel/breeze --dev
 
php artisan breeze:install blade

npm run dev
 ```
## Models, migrations, and controllers
 ```
php artisan make:model -mrc Chirp
 ```

## Authorization Model Policy
 ```
php artisan make:policy ChirpPolicy --model=Chirp
 ```
