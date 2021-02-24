# Rest API With CodeIgniter 4 Framework

## STEP 1
Download the complete project and import database file in phpmyadmin

## STEP 2
run this command in project root folder 

composer require firebase/php-jwt

This command will install JWT into application. It will install jwt package into vendor folder at project root.

## STEP 3
Start the server via 
php spark serve

## STEP 4
Now test apis

REGISTER API POST Method

URL – http://localhost:8080/api/register

Form Data -
name:bhoopnesh
email:bhoopnesh11@gmail.com
phone_no:9691271037
password:bhoopnesh@123

LOGIN API POST Method

URL – http://localhost:8080/api/login

Form Data -
email:bhoopnesh11@gmail.com
password:bhoopnesh@123

GET POST API GET Method

URL – http://localhost:8080/api/posts

SET Authorization header in with the help of login token data after that you get your posts.

