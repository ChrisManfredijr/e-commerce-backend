# E-commerce Backend ORM (object relational mapping) 
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white) ![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=Sequelize&logoColor=white)	![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)	![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white)

![site gif](Untitled_%20Jun%2025%2C%202022%209_04%20PM%20(2).gif)


## Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Description
A mysql database and application backend for an e-commerce site. 
    Link: https://drive.google.com/file/d/1MqNUOxjTqnWGody5aFyWUdQh1yKxyldC/view

## User Story 
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
## Acceptance Criteria
```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## Installation
`npm init`

`npm install mysql2`

`npm install sequelize`

`npm install dotenv`

## Usage

Run the following command at the root of your project and answer the prompted questions:

`mysql -u root -p`

Enter your password when prompted, then enter the source of the database and then enter quit :

`source db/schema.sql`

`quit`

In gitbash, intiate the program with the following commands: 

`npm run seed`
  
`npm start`

## Contributing

Made by Chris Manfredi