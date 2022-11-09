This is a README for project 0x04. MySQL.

This project focuses on creating and configuring primary and replica
MySQL databases on our two web servers, web-01(primary) and web-02(replica).

The tasks are as follows:

Task 0 - Install MySQL
 - Install MySQL distribution 5.7.x on both web-01 and web-02 web servers

Task 1 - Create a user and password for both MySQL databases:
    user name = holberton_user
    password = projectcorrection280hbtn

Task 2 - Create a table to replicate in web-01
 - Create a database named tyrell_corp
 - Within db tyrell_corp, create a table named nexus6 with at least one entry

Task 3 - Create a user for the replica server in web-01
 - User name is replica_user with host name set to %
 - Password id user choice
 - replica_user must have the appropriate permissions to replicate the primary
   MySQL server
 - holberton_user will need SELECT priviliges on the mysql.user table in order
   to check that replica_user was created with the correct permissions.

Task 4 - Setup a Primary-Replica infrastructure using MySQL
 - MySQL primary is hosted on web-01
 - MySQL replica is hosted on web-02
 - MySQL primary configuration is to be provided as an answer file

Task 5 - MySQL backup
 - Write a BASH script that generates a MySQL dump and creates a compressed
   archive out of it.
 - The dump must contain all MySQL databases
 - The dump must be named backup.sql
 - The dump has to be compressed to a tar.gz archive
 - Archive must have the below name format:
        day-month-year.tar.gz
 - The user to connect to the MySQL database must be root
 - The BASH script accepts one argument that is the password used to connect
   to the MySQL database
