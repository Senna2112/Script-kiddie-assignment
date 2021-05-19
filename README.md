# Script-kiddie-assignment

Prerequisites
Git, Composer, PHP, Node,

Commands:
Clones the repo into the designated directory.
1 git clone [repo-name]

Changes directory to the directory containing the Laravel 8 project.
2 cd kledingbank

Makes a copy of the .env.example file and calls it .env
3 copy .env.example .env

Necessary changes to the .env contents to make it compatible with your database.
4

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE= your_database
DB_USERNAME= your_username
DB_PASSWORD= your_password
Composer command to install all dependencies defined in the composer.json file.
5 composer install

Generates a application key, Laravel user sessions and other encrypted data will not be secure!
6 php artisan key:generate

Creates the tables in your MySQL database as defined by the migration files in your /databases/migrations directory.
7 php artisan migrate
