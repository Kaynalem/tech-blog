  # MVC Tech Blog
  ![License](https://img.shields.io/badge/License-MIT-blue.svg)

  ## Description
  A CMS-style blog site similar to a Wordpress site, where developers can publish their blog posts and comment on other developers’ posts as well. This app follows the MVC paradigm in its architectural structure, using Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication. 
  Try it live [here](https://serene-eyrie-02684.herokuapp.com/)  
  ![mockup](https://raw.githubusercontent.com/Kaynalem/tech-blog/master/utils/mockup.PNG)
  ## Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Contributing](#contributing)
  * [Questions](#questions)
 
  ## Installation
  To install necessary dependencies, run the following command in your terminal:
  ```
  npm install 
  ```
  ## Usage
  * Be sure to create the .env file in your root directory with your MySQL user/password information.  
  ```
  DB_NAME='tech_blog_db'
  DB_USER='root'
  DB_PW='your password'  
  ```
  * To initiate the MySQL command line, type: `mysql -u root -p` in your command line and then your MySQL password.
  * To execute the `schema.sql` file, type into the MySQL command line: `source db/schema.sql` and `use tech_blog_db`
  * To exit the MySQL command line, type `quit;` or `exit;`
  * Once updated, run `npm start` in your terminal to get started!
  ## License
  This project is licensed under the MIT license.
  ## Contributing
  If you would like to contribute please file an issue
  ## Questions
  If you have any questions about the repo, open an issue or contact me directly at [kaynalem@gmail.com](mailto:kaynalem@gmail.com).  
  You can find more of my work at my [Github](https://github.com/kaynalem) page.
