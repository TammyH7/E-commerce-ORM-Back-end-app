## Challenge: Object-Relational Mapping(ORM): E-Commerce Back End

## Description

The task of this project is to build the back end for an e-commerce website and configure a working Express.js API to Sequelize to interact with a MySQL database.  This application would use MYSQL2 and Sequelize packages to connect Express API to a MySQL Database and a dotenv package to use environment variables to store sensitive data.

This application would show the creation of database using MySQL with models and the API routes to perform RESTful CRUD Operations.  

The URL of the GitHub repository is https://github.com/TammyH7/E-commerce-ORM-Back-end-app

The URL of the Walkthrough video is: https://app.screencastify.com/v3/watch/8uBDUMcv52o3XewI1ECQ

## Mock-Up

The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia:


![In Insomnia, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.](/assets/13-orm-homework-demo-01.gif)

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia:

![In Insomnia, the user tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”](/assets/13-orm-homework-demo-02.gif)

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia:

![In Insomnia, the user tests “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”](/assets/13-orm-homework-demo-03.gif)

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [Programs Used](#programs-used)
* [License](#license)

## Installation

* This application will need the installation of node.js from the website, https://www.node.org.

* Node Package Manager (npm) is a software manager and installer which puts the modules in place so that the node project can utilize it, and also, it manages dependency 
  conflicts intelligently and initialized using <strong>npm init</strong>.  The package.json will be generated and will contains all the details of the application in which the user have inputted during the npm initialization.

* This application also need the installation of MySQL which is a developer-friendly open source relational databse system.  The application uses MySQL packjage and 
  sequelize package to connect Express.js to MySQL database and also the dotenv package to use environment variables to store sensitive data. Dotenv is a zero-dependency module that loads environment variables from a .env file into process.env.

* Nodemon is installed as development dependency meaning that if our application ever goes in production, this package will not be included. The purpose of this package is to watch for any changes in our files and restart the server instead of us having to do that manually ourselves.

* For testing in Insomnia, the following project folder, E-Commerce Back-End and sub folders were set up as in the Mock-up.

## Usage

After the creation of the models and routes, run <strong>npm run seed</strong> to seed the data to the database so the routes can be tested using insomnia.

At command prompt, type in <strong>npm watch nodemon</strong> and the app will be listening on port 3001. Once the port is listening you can then go to Insomnia and begin testing with Products, Categories and Tags.

## Built With

- JSON
- JavaScript
- Dotenv
- Node.js
- Express.js
- MySql2
- Sequelize
- Insomnia
- Nodemon
- Visual Studio Code

## License

This project is licensed under the terms of the MIT license.