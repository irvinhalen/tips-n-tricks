# 🍆 Tips & Tricks 🎃

> This one is for 📦 *Laravel*


## Getting Started

### New Laravel Project

- Create a new project with *example-project* being the name of your choice
```
composer create-project laravel/laravel example-project
```
- Change directory to the newly created project
```
cd example-project
```
- Run the project
```
php artisan serve --host=0.0.0.0 --port=3001
```


## Model

### Creating Models

1. Run command
```
php artisan make:model Post
```

## View

> Nothing here yet


## Controller

### Creating Controllers

1. Run command
```
php artisan make:controller UserController
```
2. TestTickles

## Route

### api.php

1. Run command
```
php artisan install:api
```

## Database

### Database Connection

1. locate the .env file and open it
2. find these variables and change them accordingly
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=database_name
DB_USERNAME=root
DB_PASSWORD=password
```

### Migrations

- create migration
  1. run this command with *table_name* being the table name of your choice
  ```
  php artisan make:migration create_table_name
  ```
- running migration
  1. run this command
  ```
  php artisan migrate
  ```

### Seeding

- creating seeders
  1. run this command with *NameSeeder* being the seeder name of your choice
  ```
  php artisan make: seeder NameSeeder
  ```
