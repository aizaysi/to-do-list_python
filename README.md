# To-Do
#### Video Demo:  <https://youtu.be/oLErhe-VuRM>
#### Description:
My project is a simple Todo list web app that i made it using html, css, javascript and flask (python). Through this app you can add your daily tasks and make it checked or unchecked or removed. There is also some other features in the project such as log in, register and change password. The project deeply based on finance project but with completely diffrent front-end and some changes in the back-end.

I made the project for my use as i wanted a simple website to manage my daily tasks on, the project might be basic and so simple now but hopefully i am going to add more features in the future.

The main project directory consists of two folders (templates and static) and two files (app.py, helpers.py and users.db).

static directory contains the images, css and javascript files that i have useed in the project.

templates directory contains five html files: apology.html which is a page that shows when someone enters something wrong the same as finance, changePassword is a page that enables the user to change his password, index.html is the page that contains the home page which is the todo list box, login.html enables you to log into your account, register.html enables you to create new account if you do not have one and layout.html is the default page that contains the navigation bar and the head meta tags.

helpers.py is a file that i took from finance but i deleted some functions that have no use in my project and remained just two funnctions apology (a function that shows an error message when the user enters something wrong) and login_required (a function that make sure that the user have logged in already before using the website).

app.py is the file that has all the backend of the project such as how you log in, how you register, change your password and all those stuff. The mainly used library in this file is flask. The file contains five main routes and functions (index, login, logout, register, changePassword).

users.db is a db file that have one table called users that has three columns: a column for id, one for password called hash that contains all the passwords but hashed using the hash function and one for username, and when someone register we add a new row and when someone log in we compare the username and password in the table with those that the user have entered and when someone change his password we change the hash columns where the id equal the user id.

I think that all i can say about my final project, it is so small and simple and i hope it would be useful.