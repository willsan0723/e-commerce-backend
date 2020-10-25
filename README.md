# E-commerce Back End
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

This is a simple application to demonstrate understanding of the backend of an e-commerce database. I have taken the liberty of creating a walkthrough that shows the functionality of this application once it has been installed:
https://drive.google.com/file/d/19f0D6PrNWNABnyAtP9OXrUKrRUOOO4vC/view

## Installation
First go to the directory containing the server.js file for this appplication.

npm init -y, npm install -y, npm install sequelize, npm install --save mysql2, and npm install dotenv need to all be run before starting this application.

## Usage
Log into your mysql account by typing: mysql -u root -p then enter your password.

In the mysql prompt type source db/schema.sql followed by source db/seeds.sql to create and prepopulate the table.

Create a .env file to store your credentials with the format of:
DB_NAME='ecommerce_db'
DB_USER='root'
DB_PW='yourpasswordhere'

To start, simply enter: npm start

WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database

## License

This project is covered under a MIT license. Feel free to use it as you wish.

## Questions

  GitHub User Name: willsan0723

  [GitHub Repository](https://github.com/willsan0723/)

  If you have any additional questions you can reach me at william.santee@gmail.com
