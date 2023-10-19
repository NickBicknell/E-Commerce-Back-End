# E-Commerce Back-End

<p>
<img src="https://img.shields.io/badge/-JavaScript-yellow" />
<img src="https://img.shields.io/badge/-Node-green" />
<img src ="https://img.shields.io/badge/-Express-red" />
<img src="https://img.shields.io/badge/-MySQL-magenta" />
<img src ="https://img.shields.io/badge/-Sequelize-blue" />
</p>

## Desctiption

This e-commerce back-end was developed to give an organized and efficent way to store data of a e-commerce web application. The development of this application has helped me become more efficent at using MySQL, Sequelize, and Express to create databases, store, and fetch data.

## Table of Contents 

[Installation](#installation)

[Usage](#usage)

[Tutorial Video](#tutorial-video)

[Credits](#credits)

[License](#license)

## Installation

`npm i`

In the root directory, create a .env file with the following:
```
DB_NAME=ecommerce_db
DB_PASSWORD=*your password here*
DB_USER=root
```

## Usage

- Create a MySQL database on your local machine using the schema.sql file located in the /db/schema.sql
- Seed the database with sample data by running `npm run seed`
- Start the application by running `npm start`
You can now make requests in an application like Insomnia. Avaliable requests are: GET, POST, PUT, or DELETE routes for categories, products, tags, and each individual category, product, or tag id. 


## Tutorial Video

[Tutorial Video](https://watch.screencastify.com/v/or28n8eusYkkk7ENffIJ)

## Credits

Nicholas Bicknell

## License

N/A