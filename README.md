# Creating node Project

[![Build Status](https://travis-ci.org/chiukurt/NodeJs_TravisCi_mon.svg?branch=master)](https://travis-ci.org/chiukurt/NodeJs_TravisCi_mon)

- mkdir week03_node_example
- cd week03_node_example
- node --version
- npm --version
- npm init
- ls
- npm install -g express --save
- touch README.md
- Create index.js file
- Execute node app using node index.js
- npm ls
- npm search express
- npm publish

## Install nodemon

Nodemon is a utility that will monitor for any changes in your source and automatically restart your server. Perfect for development. Install it using npm. Just use nodemon instead of node to run your code, and now your process will automatically restart when your code changes.

Using nodemon you can speed up the development process and you can install as a dev dependency only with the following command and use it in the scripts section of package.json.

<https://nodemon.io/>

- npm install nodemon --save-dev

## put this under scripts section for the key dev

- "dev": "nodemon ./index.js localhost 3030"

## start the app

- npm run dev
