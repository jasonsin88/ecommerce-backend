# E-Commerce Backend (Object-Relational Mapping)

## Description 
This project is the creation of the back end for an e-commerce site. This application used Express.js API and Sequelize to interact with a MySQL database. This application displays creation of database using mySQL with models and associations. Then demonstrates the API Routes to perform RESTful CRUD operations displayed in my walk through videos.

## Table of Contents
* [Technologies](#technologies)
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)

## Technologies
Project is created with 
* [Javascript](https://www.javascript.com/)
* [Node.js](https://nodejs.org/en/)
* [Sequelize](https://www.npmjs.com/package/sequelize)
* [MySQL2](https://www.npmjs.com/package/mysql2)
* [Express](https://www.npmjs.com/package/express)
* [Dotenv](https://www.npmjs.com/package/dotenv)

## Installation 
To get started clone this repository using 
<br>
```terminal
git clone git@github.com:jasonsin88/ecommerce-backend.git
```
Both Node.js and MySQL must be installed on your computer.

Install dependencies 
```terminal
npm i
``` 
Open up MySQL shell and input 
```terminal
source db/schema.sql
```
and 
```terminal
use ecommerce_db
```
Then quit MySQL shell and input the following in your terminal
```terminal
npm run seed
```
to start running application simply input 
```terminal
node server.js
```
Open up Insomnia core to GET, POST, PUT and DELETE from different routes.

## Usage 
This application will allow users to view, add, edit, and delete categories, products, and tags.

[View video](https://youtu.be/z7okIszuqdI) to see walk through of MySQL.<br>
[View videos](https://youtube.com/playlist?list=PLIBybC2oQOH3C0f4Vai1x5BAQxyhZVPJv) to see walk through of the GET commands.<br>
[View videos](https://youtube.com/playlist?list=PLIBybC2oQOH23_Ymxr0AYHg5RSTeXxeR0) to see walk through of POST/PUT/DELETE commands.

## License 
![Github licence](http://img.shields.io/badge/license-MIT-blue.svg)
This project is license under MIT
