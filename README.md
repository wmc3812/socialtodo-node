# CPSC113 Social todo app

This is my starter app. It is going to be sick.

## How to run this

Get the repo

    git clone https://github.com/kljensen/cpsc113-social-todo-node
    cd cpsc113-social-todo-node

Install the dependencies

    npm install

You'll need to start MongoDB somewhere to store data. And, you'll need to
choose a secret for signing browser cookies.

You can run the server with something similar to

    PORT=5000 SESSION_SECRET='sdf' MONGO_URL="mongodb://localhost:27017/social-todo" ./node_modules/.bin/nodemon index.js

where your values of `PORT`, `SESSION_SECRET`, and `MONGO_URL` could be different.
If you are on Cloud9, don't set `PORT`. `SESSION_SECRET` can be whatever you
want.

Start the app using node index.js or nodemon ./index.js.

You can either login or register on the homescreen. For registered users, logging will take you to your task screen.

On your task screen, you can both add and delete tasks. Tasks must have both a title and a description in order to 
be successfully submitted. 



