if u want this progect first of all you have to do git clone
git clone: git clone https://github.com/Khadiza18103316/pizza.git or git clone git@github.com:Khadiza18103316/pizza.git in your project directory.
then run "composer update" this commant
then run "cp .env.example .env"
then run "php artisan key:generate"
then create a new database in your mysql and also write database name in .env file.
then run "php artisan migrate"
then run "php artisan db:seed"
then run "php artisan link:storage"
then run "php artisan serve"
and see the project


