PROJECT OVERVIEW:
The following files includes the necessary codes to create a standalone Authentication API using Express.js and MySQL.
The files includes Signup, Login, Logout (token revocation), and a protected profile endpoint using JWT.

SETUP
In order to implement the system, you will need XAMPP for the creation of tables and MySQL database, VScode for coding, 
and Postman to test the requests sent to the server or system.

HOW TO RUN
After creating the database through XAMPP and confirming in the terminal of your respective VScode that your server is 
running and that MySQL is connected, you are now able to use the system. 

ENDPOINTS:
The features included are:
* POST /auth/signup - for creating a new user
* POST /auth/login - for users to log in
* GET /profile - getting user details
* POST /auth/logout - for users to log out
