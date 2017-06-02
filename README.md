# Restaurant Menu Catalog

## Describe:
1. An restaurant-menu item catalog application with flask
2. Third party authentication via Google and Facebook account
3. Taking a baseline Ubuntu Linux virtual machine that is hosted on Amazon Lightsail and preparing it to host the applicationg
4. Includes installing updates, securing the server from a number of attack vectors, and installing/configuring web and database servers

## Application Setup:
0. Install dependency libararies (Flask, sqlalchemy, requests and oauth2client
1. Navigate to this project directory inside the vagrant environment
2. Run database_setup.py to create the database
3. Run lotsofmenus.py to populate the database
4. Run finalproject.py and navigate to localhost:5000 in the browser


## Server Configuration:
1. Public IP Address: 34.224.137.73
2. SSH port: 2200
3. URL of hosted web application: http://34.224.137.73
4. If not work, restart Apache and reload command: sudo apache2ctl restart
5. SSH connection command: ssh -i ~/.ssh/grader grader@34.224.137.73 -p2200


## Server Operation:
1. SSH connection command: ssh -i ~/.ssh/grader grader@34.224.137.73 -p2200
2. If URL http://34.224.137.73 does not work, restart Apache and reload: sudo apache2ctl restart
3. App/Packages used in this app is summarized in requirements.txt

## Application Feature:
1. Routing and Templating made with Flask
2. Uses SQLAlchemy to communicate with the back-end db
3. RESTful API endpoints that return json files
4. Uses Google Login to authenticate users
5. Authenticated users can create and edit items
