## [Live Demo](https://welcome-to-storybook.herokuapp.com)

# Introduction

This is a full application build of the StoryBooks app which uses Node.js, Express, MongoDB, Passport with a Google OAuth strategy and more.

[<img src="https://github.com/Flash2022/StoryBook/blob/main/main.gif" width="480" height="270">](https://mern-hangout.herokuapp.com)

## Tools:
- [Express](https://expressjs.com) - [Node.js](https://nodejs.org) framework
- [Postman](https://www.postman.com) - API testing
- [dotenv](https://www.npmjs.com/package/dotenv) - For Config
- [Materialize-css](https://materializecss.com/) - front-end framework
- [Morgan](https://expressjs.com/en/resources/middleware/morgan.html) - logging
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) - NoSQL cloud database
- [Google Cloud Console](https://console.cloud.google.com/apis/credentials/oauthclient?previousPage=%2Fapis%2Fcredentials%3Fproject%3Dconcrete-sol-309418&project=concrete-sol-309418) - Google authentication
- [Passport](http://www.passportjs.org/packages/passport-google-oauth20/) - Using Googlo Auth2O Strategy
- [Heroku](https://www.heroku.com) - Deployment

## Key features:
- Authentication with Passport using Google Auth2O
- Create Public and Private Stories
- User can only Edit Story of same Account
- Dashboard Showing only users stories(both i.e public & private)
- Logout by clicking on logout from sidebar

## Getting Started

**Step 1: Clone the code into a fresh folder**

```
$ git clone https://github.com/Flash2022/StoryBook.git
$ cd StoryBook
```

**Step 2: Create a Virtual Environment and install Dependencies**

Create a new Virtual Environment for the project and activate it. If you don't have the `virtualenv` command yet, you can find installation [instructions here](https://virtualenv.readthedocs.io/en/latest/).

```
$ virtualenv venv
$ source venv/bin/activate
```

Next, we need to install the server dependencies, which are listed in `package.json`.

```
(venv) $ npm install
```

**Step 3: Run application**

Now we're ready to start our server using [Nodemon](https://nodemon.io):

```
(venv) $ npm run dev
```

Open http://localhost:3000 (port number is prompted) to view it in your browser.
The app will automatically reload if you make changes to the code.
You will see the build errors and warnings in the console.

Try hosted app [here.](https://welcome-to-storybook.herokuapp.com)
