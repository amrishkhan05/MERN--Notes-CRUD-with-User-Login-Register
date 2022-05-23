# MERN Notes App with Login and Register
A simple nodejs application with ejs.
This Application has 
1.login , register features
2.once logged in user can access the ToDo list App.
3.the user can perform CRUD operations on the todo list

step 1:

add a file config.env

MONGO_URI=your mongo connection details here
TOKEN_SECRET = secret
note: whitelist your ip if you are using atlas mongodb
## Connnect to your mongodb 
step 2:

  npm install

step 3 :

## Run the client & server with concurrently
npm run dev

## Run the Express server only
npm run server

## Run the React client only
 npm run client

 Server runs on http://localhost:5000 and client on http://localhost:3000



