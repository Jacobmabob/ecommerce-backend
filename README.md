

  # E-Commerce Backend


  ## Table of Contents
  
  - [Description](#description)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [Questions](#questions)

  ---

  ## Description

  This project is a simple implementation of an E-commerce Backend using Express.js, MySql and Sequelize. My objective was to fix the api routes test them with Insomnia, an API design platform. 

  ---
  ## Installation
  
  In order to run the application you need to already have installed a MySql server on your local machine as well as Insomnia (or your preferred API test program).

  Once you've installed the required technologies, follow these steps to get it up and running!

  1) Log into your MySql shell within the `db` folder and run the `source schema.sql` command to initialize your database.
  2) Open your terminal in the main directory and run the command `npm run seed` to seed your database.
  3) In that same directory, run the command `npm start` to start your server. 
  4) Once your server is running, you can open Insomnia and test the routes found in the `routes/api` folder.

  ---

  ## Usage
  The data is organized into three major components: Products, Tags and Categories, each with their own corresponding API routes. 

  ### Category routes
  - View all Categories
  - View one Category by ID
  - Create a Category
  - Update a Category property
  - Delete a Category by ID

  ![Screen shot of application](/assets/images/ecommerce-1.png)
  
  ### Tag routes
  - View all Tags
  - View one Tag by ID
  - Create a Tag
  - Update a Tag property
  - Delete a Tag by ID

  ![Screen shot of application](/assets/images/ecommerce-2.png)

  ### Product routes 
  - View all Products 
  - View one Product by ID
  - Create a Product
  - Update a Product property
  - Delete a Product by ID

  ![Screen shot of application](/assets/images/ecommerce-3.png)
  <br>
  [Walk-Through Video](https://watch.screencastify.com/v/nGxuTEPqNmakX2EQxdVY)
  ---

 ## Contributing
 - Node.js
 - Express.js
 - MySql
 - Sequelize package
 - Dotenv package
 - Express-Router package 
  

  ## Questions
  Have any questions? Feel free to check out my github or send me an Email!

  github.com/jacobmabob <br>
  thejacobmccarthy@gmail.com