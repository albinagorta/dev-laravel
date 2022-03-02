### MANUAL DE LARAVEL ###

- Instalacion de laravel
```php
composer global require laravel/installer
``` 

- creacion de app en laravel
```php
laravel new example-app
```

- crear controlador modelo migracion factory etc todos
```php
php artisan make:model  Category -all
```

- Crear modelo y migracion
```php
php artisan make:model Category -m
```

- crear controlador para api
```php
php artisan make:controller apiV1/CategoryController --api
```

- crear controlador para web
```php
php artisan make:controller CategoryController
```


