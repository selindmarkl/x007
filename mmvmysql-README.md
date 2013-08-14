x007
====

Scripts and settings for x007
#READ ME FOR MMV MySQL SCRIPT
===========

MySQL is not installed by default on OS X 10.7 or newer.  This script will fix that bug.

#WHAT THIS SCRIPT DOES
+ Downloads MySQL from Oracle
+ Installs MySQL and the bits required to make it start by default
+ Sets some paths 
+ Sets a default root password

#INSTALLATION
+ Open Terminal and run the following command

        bash <(curl -Ls http://git.io/eUx7rg)

+ Enter in your system password when prompted
+ The script will install MySQL, generate a root password and display it along with writing a file to the dekstop including the password.
+ Click to install the MySQL preference pane when prompted.
+ Close your terminal and open a new terminal to access MySQL via command line
+ Install [Sequel Pro](http://www.sequelpro.com/) or phpmyadmin to manage MySQL
