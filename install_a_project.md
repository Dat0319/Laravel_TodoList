### install composer or laragon, xampp
#### composer or [link](https://getcomposer.org/download/)
```
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
php -r "if (hash_file('sha384', 'composer-setup.php') === '48e3236262b34d30969dca3c37281b3b4bbe3221bda826ac6a9a62d6444cdb0dcd0615698a5cbe587c3f0fe57a54d8f5') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
php composer-setup.php
php -r "unlink('composer-setup.php');"
```
#### laragon
[install by link](https://forum.laragon.org/topic/755/laragon-3-2-released-php-7-2-0-vc15-apache-to-2-4-29-vc15-node-js-8-9-1-yarn-1-3-2-composer-1-5-3/2)

### install xampp
[link](https://www.apachefriends.org/index.html)

## and if you want to show your project you can use ngrox to deploy your project
[link](https://allaravel.com/blog/cai-dat-laravel-de-dang-voi-laragon)

### Create a project by composer manager package
```
composer create-project --prefer-dist laravel/laravel todo-app "5.8.*"
```

### run project 
```
php artisan serve
```
### create a controller

```
php artisan make:controller AboutController --resource
```

### create a model
```
php artisan make:model Todo
```

### create migration
```
php artisan make:migration create_todos_table
```
### run all migration
```
php artisan migrate
```

### nhập liệu với factory
```
php artisan make:factory TodoFactory
```

