# dz 1
1. Развернул в корп клауде на деве

2. postgres=# create database thai;
   CREATE DATABASE
   postgres=#
   \q
   postgres@xenos-pg-test:/tmp$ psql < /tmp/dl/thai.sql 

4. postgres=# \\c thai 

You are now connected to database "thai" as user "postgres".

thai=# select count(\*) from book.tickets;

  count   

\----------

 53997475

(1 row)
