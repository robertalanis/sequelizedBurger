# Node Express Handlebars Burger App

This is a burger logger with MySQL, Node, Express, Handlebars and a homemade ORM (yum!).

* [Check out the deployed app on Heroku](https://polar-depths-86699.herokuapp.com/).

### Overview

* Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat.

* Whenever a user submits a burger's name, the app will display the burger on the left side of the page -- waiting to be devoured.

* Each burger in the waiting area also has a `Devour` button. When the user clicks it, the burger will move to the right side of the page.

* The app will store every burger in a database, whether devoured or not until it is deleted by the user.

* Users can delete the burger from the database by using either the `Discard` or `Forget` buttons.


#### Directory structure

All the recommended files and directories from the steps above should look like the following structure:

```
.
├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   └── assets
│       ├── css
│       │   └── style.css
│       ├── img
│       │   └── burger.png
│       └── js
│           └── burgers.js
│   
│
├── server.js
│
└── views
    ├── index.handlebars
    ├── layouts
    │    └── main.handlebars
    └── partials
        └── burgers
            └── burger-block.handlebars               
```

