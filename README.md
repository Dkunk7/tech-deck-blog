# Tech Deck Blog
  
  ## Description
  This application is a basic CMS-style blog site that allows a user to create an account, log in, and create, view  and interact with posts.

  

  ## Table of Contents
  - [Installation](#installation)
  
  
  
  - [Questions](#questions)

  ## Installation
  To run this app yourself, run `npm i` to install the necessary tools. These dependencies are as follows:
  - `bcrypt`
  - `express`
  - `sequelize`
  - `mysql2`
  - `express-handlebars`
  - `express-session`
  - `connect-session-sequelize`  

You'll then need to create a `.env` file to contain your connection variables, which will be `DB_NAME=`, `DB_USER=`, and `DB_PW=`, with your database name, user, and password respectively (in quotes). After that, you'll need to sign into the mysql shell with `mysql -u root -p` and run `SOURCE db/schema.sql;` in order to create the database. After that, `npm start` will start the app.
  

  

  

  

  ## Questions
  If you have any questions:

  Find me on <a href = "http://www.github.com/Dkunk7" target = "_blank">GitHub</a>

  or

  Contact me at drkunkel7@gmail.com.