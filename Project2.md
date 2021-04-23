## WEB STACK IMPLEMENTATION (LEMP STACK)

Major Steps taken
-       Created Ubuntu EC2 Instance on AWS
-       Installed nginx  via `sudo apt install nginx`.

![lemp1](https://user-images.githubusercontent.com/25107495/115910650-fe982200-a464-11eb-8527-860b20af78b6.PNG)

-       Install mySQL  via `sudo apt install mysql-server`
-       Then to lockdown access to the database i ran `sudo mysql_secure_installation`
-       Installed PHP using `sudo apt install php-fpm php-mysql` and configured nginx to use PHP processor as below

![lemp2](https://user-images.githubusercontent.com/25107495/115910929-5898e780-a465-11eb-820b-bc4f1d9a488e.PNG)
![lemp3](https://user-images.githubusercontent.com/25107495/115910939-5b93d800-a465-11eb-82bf-4274be4ea14c.PNG)

-       Verified nginx can hand a test file to the PHP processor as below, which shows webpage about server information.

![lemp4](https://user-images.githubusercontent.com/25107495/115910945-5d5d9b80-a465-11eb-8a50-eb16edd81af4.PNG)
![lemp5](https://user-images.githubusercontent.com/25107495/115910954-5fbff580-a465-11eb-80e5-78c83b2aa91c.PNG)

-       Created a Database named dipodb and table todo_list as below
CREATE DATABASE `dipodb`;  
CREATE USER 'dipo'@'%' IDENTIFIED WITH mysql_native_password BY '********';  

-       inserted into my todo_list table items as below
INSERT INTO dipoDB.todo_list (content) VALUES ("My first important item");  
INSERT INTO dipoDB.todo_list (content) VALUES ("My Second important item");  
INSERT INTO dipoDB.todo_list (content) VALUES ("My third important item");  

![lemp6](https://user-images.githubusercontent.com/25107495/115910961-6189b900-a465-11eb-9d90-c8ef93bb5994.PNG)

-       Final Result:

![lemp7](https://user-images.githubusercontent.com/25107495/115910962-62224f80-a465-11eb-90be-5b0c5fc6d6bb.PNG)



