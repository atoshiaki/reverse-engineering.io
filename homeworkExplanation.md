1. A simple application to allow user to setup acount
2. MySQL as the database, Sequlize as Models, express.js as routes, and bcryptjs to keep user's password safety
File Sturcture
Develop
├── config
│   ├── middleware
|   |   └── isAuthenticated.js
|   ├── config.json
|   └── passport.js
├── models
│   ├── index.js
|   └── user.js
├── public
│   ├── js
|   |   ├── login.js
|   |   ├── members.js
|   |   └── signup.js
|   ├── stylesheets
|   |   └── style.css
|   └── html
├── routes
|   ├── spi-toutes.js
|   └── html-routes.js
├── server.js
└── package.json
3. Install
$ npm install
    "bcryptjs"
    "express"
    "express-session"
    "mysql2"
    "passport"
    "passport-local"
    "sequelize"
Usage
4. Change the directory to Develop folder
5. $ node server.js
6. Sign up and Login
Language written in are as follows
    Javascript
    Node.js
    Express.js
    Sequlize
    MySQL
    bcrypt.js