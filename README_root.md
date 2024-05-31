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

## Illustrations :arrow_double_down:

## Authors 🧞‍♀️🧞
Sarah Boutier
Tuyen Huynh
Haris Hammache
