# Introduction

This guide walks you through on how to run PHP and MySQL in your linux terminal

# Requirements

Make sure you have the following in your system:
- Linux terminal
- Mysql
- PHP
- Nginx (environment to run PHP)

# Walkthrough

Open you linux terminal 

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