# Laravel_TodoList
## Create database todos_app
```
php artisan migrate
php artisan db:seed
```

## run laravel project

```
npm i
composer install
php artisan key:generate
php artisan serve
```

create a controller:

```
php artisan make:controller TodosController --resource
```

create a modal

```
php artisan make:model Todo
```

create table from migration:

```
php artisan make:migration create_todos_table
```

run all migrate to create database:

```
php artisan migrate
```
