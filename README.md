# Dev-Connector

A MERN stack social media app which is based on the Udemy tutorial, and original Github repo which can be found here [devconnector by Brad Traversy](https://github.com/bradtraversy/devconnector)

## Still under construction!

This is still a project that is under construction, and not yet done.
However, it is possible to access either the back end on PORT 5000 or the Front-End at PORT 3000 if you are running either of the respective servers.

With that being said, the app is not complete. So if something breaks, it breaks :wink:

### How to get it up and running

First go ahead and clone this repository either by downloading the .ZIP file or by entering `https://github.com/petercr/dev-connector.git` into your terminal.

Next to install the dependancies and run this project requires [Node JS & NPM package manager](https://www.nodejs.org) version 10 or higher.

```bash
# Install dependencies for server
npm install

# Install dependencies for client
npm run client-install

# Run the client & server with concurrently
npm run dev

# Run the Express server only
npm run server

# Run the React client only
npm run client

# Server runs on http://localhost:5000 and client on http://localhost:3000
```

This project also requires a MongoDB database or other NoSQL database in order to store the user & posts data. In order to connect this project to a MongoDB database follow the instructions below.

You will need to create a keys.js in the server config folder with

```
module.exports = {
  mongoURI: 'YOUR_OWN_MONGO_URI',
  secretOrKey: 'YOUR_OWN_SECRET'
};
```
# DevConnector2.0
