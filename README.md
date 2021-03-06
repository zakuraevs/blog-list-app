## Single-page social blogging app
live version: https://polar-taiga-96722.herokuapp.com/

This project is WIP

### Contents of the repository:
- bloglist-backend:
  - build: the frontend build which backend routes lead to
  - controllers: routing for site URLs
  - models: mongoose models for users and posts
  - requests: helper request templates
  - tests
  - utils: helper middleware
  - app.js: the file where all the controllers and middleware are applied
  - config.js: a helper file where the environmental variables are defined
  - index.js: the main file where the server is defined
  
- bloglist-frontend:
  - cypress: testing
  - public: favicon, index.html
  - src: React App, index, components and helper services; Redux reducers

## You can log in using the following credentials:
login: sergey
password: sergeypass

## Features in development:
- Liking only once per user
- Preview of post text
- Improved deletion and editing of posts
- Improved GUI

## Tools used:
**Frontend:**
- React
- Redux
- React Bootstrap

**Backend:**
- NodeJS
- Express
- jsonwebtoken
- bcrypt
- cors
- dotenv
- lodash
- Mongoose
- MongoDB

**Testing**
- cypress
- jest

## Known issues:
- comments are not added from some mobile browsers
- the "No post with such id exists..." message is displayed upon actions and reloading
