This code base contains:
    A server.js file, which is the project launch file;
    An app.js file, which is the Express server and the one on which the project's routes are grafted;
    An images folder for storing images;
    A middleware folder for the middlewares: this folder already contains two middlewares, one for authentication and another for incoming POST requests with a file;
    A routes folder for routes;
    A models folder for data schemas;
    A controllers folder for the project's controllers (application logic).

All you need to do is clone the project and run npm install to install all the dependencies (Express, mongoose, jsonwebtoken, multer, bcrypt).

You can also install nodemon with npm install -g nodemon so that once the server has been launched it is restarted after each code modification.

The launch commands are node server (without nodemon installed) and nodemon server.js (with nodemon installed).