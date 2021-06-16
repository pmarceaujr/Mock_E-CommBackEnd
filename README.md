# **Object-Relational Mapping (ORM): E-Commerce Back End**

[![badge](https://img.shields.io/badge/license-MIT-green)](https://choosealicense.com/licenses/mit)

## **Description**

Your task is to build the back end for an e-commerce site by modifying starter code. You’ll configure a working Express.js API to use Sequelize to interact with a MySQL database.

## Table of Contents

- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Usage](#usage)
- [Required](#required)
- [Testing](#testing)
- [Questions And Support](#questions-and-support)
- [Contributors](#contributors)
- [Deployed Link](#deployed-link)
- [Media Links](#media-links)
- [License](#license)

---

## **User** **Story**

AS A manager at an internet retail company<br>I WANT a back end for my e-commerce website that uses the latest technologies<br>SO THAT my company can compete with other e-commerce companies

## **Acceptance** **Criteria**

GIVEN a functional Express.js API<br>WHEN I add my database name, MySQL username, and MySQL password to an environment variable file<br>THEN I am able to connect to a database using Sequelize<br>WHEN I enter schema and seed commands<br>THEN a development database is created and is seeded with test data<br>WHEN I enter the command to invoke the application<br>THEN my server is started and the Sequelize models are synced to the MySQL database<br>WHEN I open API GET routes in Insomnia Core for categories, products, or tags<br>THEN the data for each of these routes is displayed in a formatted JSON<br>WHEN I test API POST, PUT, and DELETE routes in Insomnia Core<br>THEN I am able to successfully create, update, and delete data in my database

## **Installation**

- Steps to install<br>+ Install Node.js<br>+ Clone repository to your local machine<br>+ Run "npm install" to install all dependencies<br>+ Open MYSQL workbench and execute the schema<br>+ Type "node seeds/index.js" on the root to seed the tables<br>+ Type "node server.js" on the root to run the application

## **Usage**

- Directions:<br>+ Once the application is running, open Insomnia at localhost:3001/api/<br>+ To View All products: localhost:3001/api/products<br>+ To View All categories: localhost:3001/api/categories<br>+ To View All tags: localhost:3001/api/tags<br>+ To View All products: localhost:3001/api/products<br>+ To view by ID, add an ID to the end of the "View All" route<br>+ To create a new item use POST<br>+ To Update an item use PUT<br>+ To remove an item use DELETE.

## **Media** **Links**

## Show All

![media file 3](./includes/images/Screenshot3.png)

## Update

![media file 3](./includes/images/Screenshot3.png)

## Delete Error Message

!![media file 3](./includes/images/Screenshot3.png)

## Full Demo video links:

Link1: Shows View(Get) All Categories, Products and Tags. View(GET) Category, Product and Tag by ID. Create New Category, Product and Tag:<br>
https://drive.google.com/file/d/1Y65BGXCjEACWaTeJ6sUOVwFr6w1abDNC/view?usp=sharing

Link2: Shows Updates and Deletes for Categories, Products and Tags:<br>
https://drive.google.com/file/d/1kd7Ncj7WUWcAaNIV0wL74uAyfYJp16Uj/view?usp=sharing

## **Required**

- The following node modules are required:<br>+ express<br>+ mysql2<br>+ sequalize<br>+ dotenv

## **Testing**

Each function was executed and tested

## **Questions** **And** **Support**

If you have any questions about the application or the repository, please open an [issue](https://github.com/pmarceaujr/Mock_E-CommBackEnd/issues) or contact me via email at paul@marceaus.net.  
 You can find more of my work on my [GitHub](https://github.com/pmarceaujr).

## **Contributors**

No other contributors at this time

## **Deployed** **Link**

No web deployment link for this app

## **License**

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit).
