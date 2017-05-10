Item Catalog Application

Describe:
An restaurant-menu item catalog application with flask 
Third party authentication via Google and Facebook account

Setup:
0. Install dependency libararies (Flask, sqlalchemy, requests and oauth2client
1. Navigate to this project directory inside the vagrant environment
2. Run database_setup.py to create the database
3. Run lotsofmenus.py to populate the database
4. Run finalproject.py and navigate to localhost:5000 in the browser

Feature:
Routing and Templating made with Flask
Uses SQLAlchemy to communicate with the back-end db
RESTful API endpoints that return json files
Uses Google Login to authenticate users
authenticated users can create and edit items

