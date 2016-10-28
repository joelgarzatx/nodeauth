# Tutorial Steps

* create project folder and setup directory structure
* git init
* add package.json
* npm install
* edit server.js

nothing works yet

* edit database.js, use localhost/passport
* git commit
* edit Routes app/routes.js
* ( myerror - fixed filename route.js to routes.js )

displays blank page

* add views ejs file content
* index.ejs, login.ejs, signup.ejs

diplays pages for /, /login, /signup

* user model, user.js
* passport.js
* edit routes.js
* uncomment in server.js the passport line
* test signup

signup works, adds info to db, no profile shown yet

* add login to passport and routes
* error - /login cannot be reached, console log Unexpected token
* fix - removed redundant }; at end of file

login page now works, still no profile shown yet

* added profle.js
* conclusion

works - signup, login, view profile page with profile detail for local 
