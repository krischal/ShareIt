# ShareIt - Technical Assessment (Laravel & Vue Js) from DuskMobile

The activity consists in developing a simple Laravel + VueJS web app on which one can do posts like on Facebook. The requirements are: 

    Simple but beautiful interface with an input where you can type any text and submit it by clicking “Share”. 
    It should store data in MySQL. 
    The previously posted items should display in chronological order. 
    If you have two windows opened and you post a comment on one of them, the other one should be updated with this post (Real-time updates)


Technology specifications: 

    Laravel 8 (only backend) 
    Php 7.4 
    MySQL Server v8.* (MariaDB v10.*) 
    Laravel Echo Server 
    VueJS (frontend) 

INstallation Guide:

    Clone the project inside (xampp/htdocs).
    Run the xamppp apache and sql server.
    cd to the project and run composer install on the terminal to install php dependencies
    Migrate your migrations: php artisan migrate
    Generate application encryption key: php artisan key:generate.
    Run npm install && npm run dev to install node.js dependencies.
    
