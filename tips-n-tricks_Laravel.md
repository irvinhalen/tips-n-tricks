# 🍆 Tips 'n' Tricks 🎃

> This one is for 📦 *Laravel*


## Getting Started

### New Project

- Create a new project with *example-project* being the name of your choice
```sh
composer create-project laravel/laravel example-project
```
- Change directory to the newly created project
```sh
cd example-project
```
- Run the project
```sh
php artisan serve --host=0.0.0.0 --port=3001
```


## Model

### Creating Models

1. Run command
```sh
php artisan make:model Post
```

## View

> Nothing here yet


## Controller

### Creating Controllers

1. Run command
```sh
php artisan make:controller UserController
```

## Route

### api.php

1. Run command
```sh
php artisan install:api
```

## Database

### Database Connection

1. Locate the .env file and open it
2. Find these variables and change them accordingly
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=database_name
DB_USERNAME=root
DB_PASSWORD=password
```

### Migrations

- Creating migrations
  1. run this command with *table_name* being the table name of your choice
```sh
php artisan make:migration create_table_name
```
- Running migrations
  1. run this command
```sh
php artisan migrate
```

### Seeding

- Creating seeders
  1. run this command with *NameSeeder* being the seeder name of your choice
```sh
php artisan make: seeder NameSeeder
```
