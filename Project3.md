## Simple To-Do Application on MERN Web Stack

Major Steps taken
-    Created Ubuntu EC2 Instance on AWS
-    Upgraded ubuntu and Installed node  via `sudo apt-get install -y nodejs` This is the backend of the Application
-    created a directory 'todo' via `mkdir todo` and 'cd' into the directory.
-    Install Expressjs with `npm install express` so the routes can be defined

![1 expressjs installed1](https://user-images.githubusercontent.com/25107495/115950494-7ac94e80-a4d3-11eb-9693-b0894a667ae3.PNG)
![2 expressjs installed2](https://user-images.githubusercontent.com/25107495/115950496-7bfa7b80-a4d3-11eb-8206-599957a81a7f.PNG)

-    Signedup and made use of MongoDB database by creating models via `npm install mongoose`

![3 Mondodb database connection succesful](https://user-images.githubusercontent.com/25107495/115950497-7c931200-a4d3-11eb-9792-f05605df3ab8.PNG)

-    As no frontend configured yet, used PostMan to generate request to the backend server to test functionality

![4 PostmanPostReqBody](https://user-images.githubusercontent.com/25107495/115950498-7d2ba880-a4d3-11eb-932a-bcd9f1917727.PNG)
![5 PostmanPostReqHeader](https://user-images.githubusercontent.com/25107495/115950499-7dc43f00-a4d3-11eb-8004-9e1f23a95d7b.PNG)
![6 browser ger request postman](https://user-images.githubusercontent.com/25107495/115950501-7dc43f00-a4d3-11eb-8136-03d7ea11dede.PNG)
![7 PostmanGetReq](https://user-images.githubusercontent.com/25107495/115950502-7e5cd580-a4d3-11eb-9474-df88f0c32957.PNG)
![8 PostmanDeleteReq](https://user-images.githubusercontent.com/25107495/115950503-7ef56c00-a4d3-11eb-8f0e-39e4c9c64f45.PNG)  
**Browser below showed the post request was deleted**
![9 browser delete request postman](https://user-images.githubusercontent.com/25107495/115950506-7ef56c00-a4d3-11eb-8b5a-b7d18b30553a.PNG)

-    Configured react as frontend for the todo Application

![10 runing react and configure proxy](https://user-images.githubusercontent.com/25107495/115950507-7f8e0280-a4d3-11eb-840b-54870e966d81.PNG)
![11 runing react and configure proxy browser](https://user-images.githubusercontent.com/25107495/115950508-80269900-a4d3-11eb-8a98-f12064d6d35e.PNG)

-    Final Result

![12 completed1](https://user-images.githubusercontent.com/25107495/115950509-80269900-a4d3-11eb-91c5-e49b024c5a52.PNG)
![12 completed2](https://user-images.githubusercontent.com/25107495/115950510-80bf2f80-a4d3-11eb-881e-8b64f0a5214c.PNG)
![13 completed Project 3 Browser](https://user-images.githubusercontent.com/25107495/115950511-8157c600-a4d3-11eb-83db-135f689da1b6.PNG)
