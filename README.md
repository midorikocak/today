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

6-Generate a new JWT authentication secret key

    php artisan jwt:generate
    
 
7-Run the database migrations (**Set the database connection in .env before migrating**)

    php artisan migrate
    
 
8-**TL;DR command list**

    git clone git@github.com/midorikocak/today.git
    cd today
    composer install
    cp .env.example .env
    php artisan key:generate
    php artisan jwt:generate
    
 10-You can use XAMPP for the local server and you should create a virtual server.
     After you install XAMPP for your linux,then;
      
      **cd /opt/lampp/etc/httpd.conf
      
      #Virtual hosts
      #Include etc/extra/httpd-vhosts.conf
       
       change it like this;
       #Virtual hosts
      Include etc/extra/httpd-vhosts.conf
      
 11- Finally,
       
       cd /opt/lampp/etc/extra/
       nano httpd-vhosts.conf
       **
       <VirtualHost my_app.laravel:80>
    ServerAdmin webmaster@my_app.laravel
    DocumentRoot "/opt/lampp/htdocs/today/public/"
    ServerName my_app.laravel
    ErrorLog "logs/my_app.laravel-error_log"
    CustomLog "logs/my_app.laravel-access_log" common
     </VirtualHost> **
     
     and then ;
     
     sudo /opt/lampp/lampp/restart
     
     You can use my_app.laravel on your web.
       
       
     
       
