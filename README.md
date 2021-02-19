# hw12 Eat-da-Burger, 18 FEB 21

#### By Ashley Stith

## Description
This application is a burger logger that uses MySQL, Node, Express, Handlebars and an ORM.  The MVC design pattern is used, as well as, Node and MySQL to query and route data in the app. Express Handlebars is used to generate the HTML.

The application allows users to input names of burgers that they would like to eat.  A user submits a burger's name and clicks the *burger* submit button.  The name of the burger is displayed on the left-hand side of the page (under the Orders section: To be devoured).  Each burger input includes a "Devour It!" button.  When clicked, the burger name is deleted from the left-hand side and moved to the right-hand side of the page (under the Orders section: Have been devoured).  Each burger is stored in a database, whether it is devoured or not.

## Live Site
The site has been deployed to Heroku. Click the screenshot to view.
![Screenshot](/public/assets/img/screenshot.PNG)

## Dependencies
[mySQL database service](https://www.mysql.com/)

[Node.js](https://nodejs.org/)

[Epress NPM package](https://www.npmjs.com/package/express)

[Epress Handlebars](https://www.npmjs.com/package/express-handlebars)

The application is invoked by using the following command:

```bash
node employeeTrackerCode.js
```

## Installation
* Create a `.gitignore` file and include `node_modules/` and `.DS_Store/`
* Install npm dependencies using the following command:
```bash
npm i
```
* Create database using the schema.sql file in the db folder.  Insert test entries using the seeds.sql file (optional)

## Features
* The application files and directories are saved in the following structure:

├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   └── assets
│       ├── css
│       │   └── burger_style.css
│       └── img
│           └── burger.png
│  
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars

## Known Bugs
Site has no known bugs

## Technologies Used
* node.js
* mySQL
* Express
* Express-Handlebars

## Contribution Guidelines
Direct link to repository: https://github.com/stithac/burger
