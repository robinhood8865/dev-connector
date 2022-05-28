# DevConnect Project - MERN Full Stack (Front End + Back End)

This repository contains the API of "DevConnect" project handled by the back-end server. Features: user authorization and user registration and handles profile, posts and users. 

The server-side web framework Express.js is used to help deploy our own back-end server faster, work with databases, set up security and testing, as well as deploying the back end on a VM in the Cloud. 

**Features**
The project interactivity includes:

- Updating profile info and avatar image
- Adding and Deleting user's own profile only
- Liking and unliking posts
- Sign up and Sign in

**Technologies**

Stack: HTML5, CSS3, JavaScript/JSX, DOM, Debugging Git, Git/Github, Form validation, NPM, React, React components, React hooks, Node.js, Express.js, Database, MongoDB, Mongoose, OpenShift

**Takeaway**
- Building an extensive backend API with Node.js & Express
- Protecting routes/endpoints with JWT (JSON Web Tokens)
- Extensive API testing with Postman
- Integrating React with the backend bt creating seamless workflow
- Building the frontend to work with the API
- Using Redux for app state management
- Creating reducers and actions for the resources
- Creating reusable container components that integrate with Redux
- Testing with the Redux Chrome extension
- Creating a build script, securing our keys and deploy to OpenShift using Git

## Directories

`/models` — database schemas and models

`/routes` — routing files HTTP requests

`/middleware` — middleware authentication and logging

`/public` — static files from the build of the React front-end app.

## Running the Project

`npm run dev` — to launch concurently the front-end and the server with the hot reload feature.
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

`npm run start` — to launch the server.
Open [http://localhost:5000](http://localhost:5000) to view it in the browser.


This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.