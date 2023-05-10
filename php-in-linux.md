# Introduction

This guide walks you through on how to run PHP and MySQL in your linux terminal

# Requirements

Make sure you have the following in your system:
- Linux terminal
- Nginx (environment to run PHP)
- Mysql
- PHP

# Installation

Installing nginx
```
sudo apt-get update
sudo apt-get upgrade
sudo add-apt-repository ppa:nginx/stable
sudo apt-get update
sudo apt-get install -y nginx
```

Installing php and mysql
```
sudo add-apt-repository ppa:ondrej/php  # Add Repo
sudo apt-cache show php                 # Check the latest PHP version available to install
sudo apt-get install php7.4-cli php7.4-fpm php7.4-curl php7.
```


# Walkthrough

Open you linux terminal

Start the Nginx service
```
sudo service nginx start
```

Run the following command to start your MySQL service in you system:
```
sudo service mysql start
```

To start PHP, run the following command in the same folder that contains your root in ```index.php```
```
php -S localhost
```
With this you should be able to visit http://localhost/ on your browser

If you want to run a custom port in your localhost, simply add the port number in above command seprated by a colon:
```
php -S localhost:8080
```
[<- Back to Guides List](/Readme.md)