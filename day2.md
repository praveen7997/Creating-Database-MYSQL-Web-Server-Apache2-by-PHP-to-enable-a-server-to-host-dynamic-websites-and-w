# Creating  Database MYSQL, Web Server Apache2 by PHP to enable a server to host dynamic websites and web apps.

Kali Linux installation step by step:

* First Download Kali linux.
Boot your pc with Kali Linux once booted, Select Graphical Install.
* Select your language and click continue. Select your Location and click continue.
* Configure your Keyboard and click continue.Type Your Desired Host name and click continue,again press continue button.
* Set your root password and click continue.Configure the Clock and click continue.
* Now Click on Guided – Use entire disk and click continue.Now click continue.
* Now Click on All Files in One Partition and click continue.Now click continue.
* Select option yes and click continue.Select option no and click continue.Select option yes and click continue.
* Now installation is finished and completed.
* So now you can use linux.
Log into Kali Linux with the username and password

# How to Install Apache on Ubuntu
* Open a terminal and type:
*     sudo apt-get update
*Step 1: Install Apache
* To install the Apache package on Ubuntu, use the command:
*     sudo apt-get install apache2
*Step 2: Verify Apache Installation
* To verify Apache was installed correctly, open a web browser and type in the address bar:
*     http://local.server.ip
*The web browser should open a page labeled “Apache2 Ubuntu Default Page,” as in the image below:




# How to install My Sql
* Open Terminal and run below command.
*     sudo apt-get install mysql-server

* Give the root password.
* Wait for the installation to finish.
* The installer itself start the MySql server. To check whether the MySql server is running or not, run below command.
*     sudo netstat -tap | grep mysql

* To make sure, your MySql installation works fine with Apache and PHP, run below command. It will install necessary modules to connect to a MySql database through PHP using Apache.
*     sudo apt-get install libapache2-mod-auth-mysql php5-mysql

* Installation is completed.
 
# Installation of Php
* In default we have php installed in Kali Linux, but check for the latest version and update it
*     sudo apt-install python3
* To check the version of
* php -v

# creating a Directory with sql,html,php files
 
 first go to the path which we want to create a folder/directory

 $ cd /var/www/html

 Now create a folder 
   
  $ sudo mkdir verzeo-webapp 

  $ sudo chmod 777 verzeo-webapp
 copy required files to create web login page of php,html and mysql from github

 git hub link

 # now create our own data base

 go to mysql

 $ sudo mysql -u root -p

 you will enter into mysql, there we need to check for databases we use syntax as 

 Mariadb()> show databases;

 ![image](SCREENSHOTS/SQL1.png)

 





       


