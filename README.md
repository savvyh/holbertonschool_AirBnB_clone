# AirBnB clone

## General 🏨
For my first year of study in web development, I was able to create in several stages a website inspired by the famous AirBnB website.<br>
I worked on it with 2 peers due to the group project.

## Step 💻
1. The first step was to create a console in Python.
2. Then I had to create a database using MySQL.
3. I also used Flask to develop a web server.
4. Finally, it was of course necessary to create the user interface, focusing on the front-end.

## What part of the project is presented here? :dart:
Well, for each of the stages a new up-to-date (and complete 😅) code was provided to me by the school in order to start again on a good code base before starting a new stage.<br>
The aim of the project was to make the page more dynamic, by adding a filter option using the "search" button. <br>
This is the part that I worked on and that I would like to present through this project.

## Requirements 👍
0. Use JQuery : `<script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>`.
1. All JavaScript files must be in the folder `scripts`.
2. Clone this project to work on it and add dynamism on the website : https://github.com/jzamora5/AirBnB_clone_v3.
3. Directory to view : `web_dynamic`

## How to use 💯
- Start the Flask web server : `HBNB_MYSQL_USER=hbnb_dev HBNB_MYSQL_PWD=hbnb_dev_pwd HBNB_MYSQL_HOST=localhost HBNB_MYSQL_DB=hbnb_dev_db HBNB_TYPE_STORAGE=db HBNB_API_PORT=5001 python3 -m api.v1.app`
- In another terminal, open the web browser : `HBNB_MYSQL_USER=hbnb_dev HBNB_MYSQL_PWD=hbnb_dev_pwd HBNB_MYSQL_HOST=localhost HBNB_MYSQL_DB=hbnb_dev_db HBNB_TYPE_STORAGE=db HBNB_API_PORT=5001 python3 -m web_dynamic.4-hbnb`
- Open web browser and add the endpoint as : `http://localhost:5000/4-hbnb/`
- At the top right there is a sticker. This should be red if the API is properly connected, otherwise it remains gray. Make sure the tablet is red!
- Get the database : `curl -o 100-dump.sql "https://s3.eu-west-3.amazonaws.com/hbtn.intranet.project.files/holbertonschool-higher-level_programming+/290/100-hbnb.sql"`
- Read the database and execute it to the MySQL server : `cat 100-dump.sql | mysql -uroot -p`

## Handle error ❎
- If somthing wrong, you can clone from this repository : `https://github.com/savvyh/holbertonschool-AirBnB_clone_v4`<br>
-> This is the repository of my group.

## Illustrations :arrow_double_down:
##### 1. First page when web browser is open : <br>
![image](https://github.com/savvyh/holbertonschool_AirBnB_clone/assets/139894873/27776e6d-bc0a-4e63-9c24-45b650362aa3) <br>

##### 2. Adding checkbox to choose options : <br>
![image](https://github.com/savvyh/holbertonschool_AirBnB_clone/assets/139894873/e9fbc588-2aa7-41b5-859c-2d0a129850c7) <br>

##### 3. Click on the "search" button and filters places according to the selected options : <br>
![image](https://github.com/savvyh/holbertonschool_AirBnB_clone/assets/139894873/cf2b8370-8da0-4bec-b078-54001dfc0cf6) <br>

## Authors 🧞‍♀️🧞
* Sarah Boutier
* Tuyen Huynh
* Haris Hammache
