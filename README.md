# Express user authentication (with express-session)
Express bookcart starter project

1. Clone the repository
2. Start mongoDB server, run `mongod`
2. Run `npm install`
3. For file changes watch, run `npm install -g nodemon`
3. For local development, start the server `nodemon app.js`
4. The app runs on: http://localhost:3000
5. TODO: allow user to reset password (http://sahatyalkabov.com/how-to-implement-password-reset-in-nodejs/)
6. Authentication was done with "connect-mongo" by saving session id in mongoDB, other options including Json web token, passport middleware.