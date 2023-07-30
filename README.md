# Admin-Portfolio
A profile with front-end side which contain my personal information as follows.

-Home
-About
-Skills/Education
-Portfolio
-Reviews from mentors

And the backend side which contain the Admin Panel where user can

-Create
-Read
-Update/Edit
-Delete, using the contact form.


## Dependencies
- Express
- Ejs
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

