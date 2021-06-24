Installation -

Requirements - xampp/php 7.3,composer,mySql

steps- 
1. clone the repo into local machine
2. given .env.example file create a .env file using that
3. create an empty database in mySql
4. add that database in .env file in DB_NAME with your mysql password in DB_password with root as user
5. open cmd in the installed folder then type the following commands 
6. php composer install
7. php artisan migrate
8. php artisan: db seed
9. php artisan serve
 
