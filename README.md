[comment]: <> (This readme was created by Nodinq Readme Generator)
![alt text](https://img.shields.io/badge/License-MIT-brightgreen)
![alt text](https://img.shields.io/badge/ver.-1.0.0-blue)

# MVC-CMS Blog App


## Description

Blog CMS portal that allows user registration and login using session method under Express server.
The user can create, edit and delete posts from the database. Under the hood controllers manage the routes and SQL queries through Sequelize and MySQL2.
The front-end is despatched by Handlebars. And it use Restful paradigm to communicate with the back-end.

## Screenshot

![alt screenshot](https://github.com/brberis/mvccms-blog-app/raw/main/assets/images/web.png)

## Features

- Rich Text Editor
- Session expiration (Set to 1 hour)
- Support posts with HTML
- User password encryption
- User sessions (Express Session)

## Dependencies and Technology

- bCrypt
- Connect Session Sequelize
- Dotenv
- ExpressJs
- Express Handlebars
- Express Session
- Mysql2
- Sequelize
- Trix

## Live Demo

Live demo site [here](https://mvccms-blog-app.herokuapp.com).

## How to Install

To install this Blog App, please follow these steps:

1. Clone the repository by running the command git clone: 
[https://github.com/brberis/mvccms-blog-app.git](https://github.com/brberis/mvccms-blog-app.git)
2. Navigate to the root of the project directory using the command `cd repo-name`.
3. Run `npm install` to install all the necessary dependencies.
4. Set up the required environment variables by creating a .env file in the root of the project directory and adding the necessary environment variable key-value pairs.
5. Start the development server by running the command `npm rstart`
7. In the browser navigate to `http://localhost:3000` to access the app

### Note:
- Make sure that you have the latest version of Node.js and npm installed on your machine
- Make sure you have MySQL installed and running before start the development server. 


## Questions

Please send your questions [here](mailto:cristobal@barberis.com?subject=[GitHub]%20MVC-CMS%20Blog%20App) or visit [github/brberis](https://github.com/brberis).

## Credits

* Cristobal A Barberis%    
