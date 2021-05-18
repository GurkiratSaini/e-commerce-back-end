# E-Commerce-Back-End
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

  ## Description
  This is a Node.js application that simulates a back end for an e-commerce company with a built-in API capable of handling CRUD requests. This application was built with Express, MySQL2, Sequelize and DotEnv packages.

  ## Deployed Application
  The deployed API can be found on Heroku at this [link.](https://mysterious-shelf-97572.herokuapp.com/api/categories)

  A video walkthrough of the application can be found at this link: [Video Walkthrough](https://drive.google.com/file/d/1oNqYBlt1Ph8h047YHNLN-iHUhT5Hxm4m/view?usp=sharing)

  ## Table of Contents
  - [Preview](#preview)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [Tests](#tests)
  - [Questions](#questions)
  - [License](#license)

  ## Preview
  ![In Insomnia Core, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.](./assets/13-orm-homework-demo-01.gif)
  ![In Insomnia Core, the user tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”](./assets/13-orm-homework-demo-02.gif)
  ![In Insomnia Core, the user tests “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”](./assets/13-orm-homework-demo-03.gif)

  ## Installation
  To install this application, clone the repository and run `npm install` to install all dependencies. Once done, run `npm start` to run the express app and build the database. You are free to seed the database as you wish, but a seeds file is included in the application. To run the seeds file, run `npm run seed` from the command line/terminal. For making API calls, feel free to use any platform you feel comfortable using.

  ## Usage
  The API has been deployed to Heroku and is pre-seeded to see requests in action! The API supports the following requests for each end-point: <br>
  - `GET All entries`<br>
  - `GET One entry by requesting id number at the end of url`<br>
  - `POST new entry by sending data in request body`<br>
  - `PUT request by sending id number as parameter and data in body`<br>
  - `DELETE request by sending id number as a parameter`<br>

  The following API endpoints are available for CRUD operations: <br>
  - `/api/categories`
  - `/api/products`
  - `/api/tags`

  ## Contributing
  Fork repository and make a new pull request.

  ## Tests
  There are no tests for this repository.

  ## Questions
  If you have any questions, feel free to reach out to me at below- 

  GitHub: [GurkiratSaini](https://github.com/GurkiratSaini)

  ## License
  This project is licensed under the terms of MIT License
  