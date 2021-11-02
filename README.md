# ecommerce-backend

## how to access and use this project
This project is free and open source! To use this project, clone the project to your machine and follow the instructions in this walkthrough video below. 

## description / purpose
This functional Express.js API allows a user to connect to a database using Sequelize after adding the database name, MySQL username and password to an environment variable file. 
After running 'node server.js', the server is started and the Sequelize models are synced to the MySQL database. 
When a user opens API GET routes in Insomnia Core (or Postman) for categories, products, or tags, the data for each of these routes is displayed in a formatted JSON.
When users test API POST, PUT, and DELETE routes in Insomnia Core (or Postman), they are able to successfully create, update, and delete data in their ecommerce database.

## languages, skills, packages, frameworks used
This project utilizes Javascript, express.js, MySQL, Sequelize, and dotenv.

## purpose
This project demonstrates usage of an ORM backend for an e-commerce website. It uses the MySQL2 and Sequelize packages to connect an Express.js API to a MySQL database. It additionally utilizes the dotenv package to use environment variables to store sensitive data.

## mockup
The mockup below demonstrates the functionality of this backend using Insomina core: 
![alt text](https://github.com/aliciachen10/ecommerce-backend/blob/main/assets/demo-01.gif "Demo 1")
![alt text](https://github.com/aliciachen10/ecommerce-backend/blob/main/assets/demo-02.gif "Demo 2")
![alt text](https://github.com/aliciachen10/ecommerce-backend/blob/main/assets/demo-03.gif "Demo 3")
