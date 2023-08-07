
# Admin-Portfolio
A profile with two separate version front-end and back-end side which contain my personal information as follows.


# Front-End
- Home
- About
- Skills/Education
- Portfolio
- Reviews from mentors.


# Back-end side which contain the Admin Panel where user can
- Create
- Read
- Update/Edit
- Search
- Delete.


## Dependencies
- Express-handlebars
- Express
- Mysql2
- Dotenv


### Database connection
```
// Database connection
const pool = mysql.createPool({
  host: 'localhost',
  user: 'root',
  password: 'Mrsowusu',
  database: 'user_management'
});

```



## Installation
To run this project, install it locally using npm:


```
$ npm install
$ npm start
```

## Deployment
https://velvety-clafoutis-2dab42.netlify.app/
