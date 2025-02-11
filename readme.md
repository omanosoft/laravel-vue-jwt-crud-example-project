## Laravel Vue Jwt Example Project
This project is an example for this tutorial:
https://medium.com/aratta-studios/easy-jwt-authentication-crud-using-laravel-vue-js-mysql-cdee952f8c87?source=---------2------------------


# Setup

```
composer install
npm install
```

make a .env file and set your db 
```
mv .env.example .env
```

then
```
php artisan key:generate
php artisan jwt:secret
```

reset cache
```
php artisan config:clear
php artisan config:cache
```

create tables in database
```
php artisan migrate
```

# Usage

Run the backend
```
php artisan serve
```

Run the front-end
```
npm run watch
```

Browse the website using
http://localhost:8000
