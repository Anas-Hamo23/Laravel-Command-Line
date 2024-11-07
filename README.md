# Laravel Command Line Guide

### Start the Development Server
```bash
php artisan serve
```

### Create a Controller Class
```bash
php artisan make:controller NameController
```

### Create a Resource Controller Class
Creates a controller with default functions: index, create, store, show, edit, update, destroy.
```bash
php artisan make:controller PhotoController --resource
```

### Create an API Controller Class via Command Line
```bash
php artisan make:controller PhotoController --api
```

### Create a Model Class via Command Line
```bash
php artisan make:model NameModel
```

### Create a Migration Class via Command Line
```bash
php artisan make:migration NameMigrate
```

### Create a Model, Migration Classes via Command Line
```bash
php artisan make:model NameModel -m
```

### Create a Model, Migration, and Controller Classes via Command Line
```bash
php artisan make:model NameModel -mc
```

### Show All Routes
```bash
php artisan route:list
```

### Create a Middleware
```bash
php artisan make:middleware NameMiddleware
```

### Create a Middleware
```bash
php artisan make:middleware NameMiddleware
```

### Create a Request
```bash
php artisan make:request NameRequest
```

### Create a Policy
```bash
php artisan make:policy NamePolicy --model=ModelName
```

### Run Migrations
```bash
php artisan migrate
```

###  Rollback Migrations
```bash
php artisan migrate:rollback
```

### Seed the Database
```bash
php artisan db:seed
```
