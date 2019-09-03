# GETTING STARTED

## Today

1-Clone the repository:

<code> https://github.com/midorikocak/today.git </code>

2-Switch to the repo folder

    cd today

3-Install all the dependencies using composer

    composer install

4-Copy the example env file and make the required configuration changes in the .env file

    cp .env.example .env

5- Generate a new application key

    php artisan key:generate


6-Run the database migrations (**Set the database connection in .env before migrating**)

    php artisan migrate
    
 
7-**TL;DR command list**

    git clone git@github.com/midorikocak/today.git
    cd today
    composer install
    cp .env.example .env
    php artisan key:generate
    php artisan migrate

 8-Start the local development server

    php artisan serve

    You can now access the server at http://localhost:8000
    
9- **Make sure you set the correct database connection information before running the migrations Environment variables.**

    php artisan migrate
   
    php artisan serve

       
       
     
       
