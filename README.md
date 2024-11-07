# Laravel Command Line Guide

### Install Laravel
```bash
composer create-project --prefer-dist laravel/laravel project-name
cd project-name
```

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

### Create a Seeder
```bash
php artisan make:seeder NameSeeder
```

### Run Specific Seeder
```bash
php artisan db:seed --class=NameSeeder
```

### Create a Factory
```bash
php artisan make:factory NameFactory --model=ModelName
```

### Generate Auth Scaffolding (Laravel Breeze or Jetstream)
#### Laravel Breeze
```bash
composer require laravel/breeze --dev
php artisan breeze:install
npm install && npm run dev
php artisan migrate
```

#### Laravel Jetstream
```bash
composer require laravel/jetstream
php artisan jetstream:install [livewire|inertia]
npm install && npm run dev
php artisan migrate
```

### Clear Application Cache
```bash
php artisan cache:clear
```

### Clear Configuration Cache
```bash
php artisan config:clear
```

### Clear Route Cache
```bash
php artisan route:clear
```

### Clear View Cache
```bash
php artisan view:clear
```

### List All Available Artisan Commands
```bash
php artisan list
```

### Create a Job
```bash
php artisan make:job NameJob
```

### Create a Listener
```bash
php artisan make:listener NameListener --event=EventName
```

### Create an Event
```bash
php artisan make:event NameEvent
```

### Create a Notification
```bash
php artisan make:notification NameNotification
```

### Create a Mail
```bash
php artisan make:mail NameMail
```

### Create a Console Command
```bash
php artisan make:command NameCommand
```

### Queue Work Command
```bash
php artisan queue:work
```

### Queue Listen Command
```bash
php artisan queue:listen
```

### Create a Custom Validation Rule
```bash
php artisan make:rule NameRule
```
