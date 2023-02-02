
  # E Commerce Backend
  [![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)](https://opensource.org/licenses/ISC)

  ## Table of Contents
  - [Description](#description)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [Tests](#tests) 
  - [License](#license)
  - [Contact](#contact)

  ## Description
  This application establishes routes to enable dynamic access to a database consisting of products, categories, and tags where a product may have many tags but only one category, categories have many products, and tags can associate with several different products.

  ## Installation
  You will have to clone this repository to your local environment, then log into mysql and run "source db/schema.sql" to establish to database. You will then populate the database by running "npm run seed" and connect with npm start. You can also run "npm start watch" to use nodemon to keep the server running. At this point you can use insomnia to access the routes to the tables in the database and reference all data from each section, singular chunks of data by their ID numbers, add data, update data, and delete data by ID number.

  ## Usage
  demonstration video: https://drive.google.com/file/d/1-8dm192setJPp939oeFut5wj2dFPDNFR/view
  This route structure can be used to keep a complex inventory of items with intersecting attributes.

  ## Contributing
  Contact me through github with suggestions for contribution

  ## Tests
  This application can be tested with a program like insomnia or postman 

  ## License
  ISC

  ## Contact
  Github: https://github.com/reethd
  Email: reeth.dasgupta@gmail.com

