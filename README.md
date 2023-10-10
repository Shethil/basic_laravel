#Upload a laravel project into git:

1. git init
2. git add .
3. git commit -m "comment"
4. git status
5. git remote add origin pository_link
6. git push


#Clone a laravel project from git:

1. git clone <project url>
For Specific Branch: git clone --single-branch --branch <branch name> <project url>
2. cd <project name>
3. composer install
4. cp .env.example .env
5. php artisan key:generate
6. Crate database in phpmyadmin 
7. php artisan migrate
8. php artisan serve

#CRUD
1. composer create-project laravel/laravel CRUD
2. create a database: http://localhost/phpmyadmin
3. edit .env file
4. php artisan make:controller StudentController -r
5. php artisan make:model Student -mfs --requests
6. edit migration file
7. php artisan migrate
8. call StudentController in web.php
9. create index, create, view, edit blade file
10. Complite StudentController functions.
