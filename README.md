# Calorie Tracker
[![License: GNU GPL v3](https://img.shields.io/badge/License-GNU%20GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

## Table of Contents
* [Description](#description)
* [Built With](#built-with)
* [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing-to-calorie-tracker)
* [Test](#test)
* [Questions](#questions)
* [License](#license)

## Description
An application that stores your daily caloric intake and tracks your progress against user defined goals

View the application in action [here](https://warm-harbor-01230.herokuapp.com/).

## Screenshot
![Screenshot](./public/img/screenshots/001.jpg)

## Built With
- Node.js
- Express.js
- MySql
- Sequelize ORM
- Handlebars.js
- Cloudinary
- Multer
- Heroku

## Installation
    =============
    = Git Setup =
    =============
	$ git clone https://github.com/{your-username}/calorie-tracker
	$ cd ./tech-blog
	$ npm install

    ==========================
    = Local Deployment Setup =
    ==========================
    $ mysql -u your_username -p
    source db/schema.sql
    quit

    - Setup .env file with your database connection info
    - Setup .env file with your Cloudinary account info using CLOUD_NAME, CLOUD_API, CLOUD_KEY

    ===========================
    = Heroku Deployment Setup =
    ===========================
    $ heroku create heroku-deployment-name
    $ git push heroku main

    =====================
    =    Heroku Setup   =
    =====================
    - Setup Environment variable for your cloudinary account using CLOUD_NAME, CLOUD_API, CLOUD_KEY
    - Setup JawsDB Mysql addon

## Usage
	$ npm start

## Contributing to Calorie Tracker
Please follow contribution guidelines at the [Contributor Covenant](https://www.contributor-covenant.org/version/2/1/code_of_conduct/) to contribute to Calorie Tracker.

## Tests
    There are no tests available for this application

## Questions
Contact us at the following:
- [hsengu](https://github.com/hsengu)
- [hroddy](https://github.com/hroddy)
- [GTN-git](https://github.com/GTN-git)
- [dtuominen22](https://github.com/dtuominen22)

## License
This project is licensed under GNU GPL v3
