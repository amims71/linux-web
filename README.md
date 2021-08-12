# linux-web


```
sudo apt-get install mysql-server mysql-client
sudo apt-get install apache2
sudo apt-get install php php-cgi libapache2-mod-php php-common php-pear php-mbstring
sudo a2enconf php7.4-cgi
systemctl reload apache2

sudo apt-get install phpmyadmin


sudo mysql_secure_installation utility

or

sudo mysql

SHOW VARIABLES LIKE 'validate_password%';
SET GLOBAL validate_password.length = 1;
....

ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY '1';

flush priviliges;
exit

```
