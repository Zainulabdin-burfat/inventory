## Laravel Inventory

This Project Is By:
git clone https://github.com/sanz/laravel-inventory.git
cd laravel-inventory
composer install
cp .env.example .env
php artisan migrate
php artisan key:generate
php artisan storage:link
php artisan serve