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

- Cree recursos API elocuentes
```php
php artisan make:resource Producto
```

- crear controlador para web
```php
php artisan make:controller CategoryController
```

- realizar la migracion 
```php
php artisan migrate
```

- otros de migracion 

: Drop all tables and re-run all migrations 
```php
php artisan migrate:fresh
```

:Create the migration repository
```php
php artisan migrate:install
```

:Reset and re-run all migrations
```php
php artisan migrate:refresh
```

:Rollback all database migrations
```php
php artisan migrate:reset
```

:Rollback the last database migration
```php
php artisan migrate:rollback
```

:Show the status of each migration.
```php
php artisan migrate:status
```      
        
- comprobar las rutas         
```php
php artisan route:list
``` 
https://httpstatuses.com/














              
         
