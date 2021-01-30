# TEAM SPACE
Team project was done during Sourcery Academy. The website has 3 main functions:
- newsfeed – where the team can share photos, videos and celebrate birthdays
- reservation pages – to easily find available devices, books and meeting rooms
- eat-out pages – where people can find different places to go to eat

## Run the project

- To run this project you will need [Node](https://nodejs.org/en/). We strongly recommend to use [nvm](https://github.com/nvm-sh/nvm) for installing node.
- After installing nvm go to project directory and run:
  - `nvm install [version in .nvmrc file]`
  - `nvm use`
  - `npm install`
  - `npm run start-server` - runs server
  - `npm start` - builds project for development
- .env - this website uses some environment variables. You will need to create a file .env and insert these variables (don't forget to restart server `npm start` after updating .env file):<br />
  - To access the hosted database use this:<br />
    `REACT_APP_DATABASE_URL = "https://sfe2020-status202.azurewebsites.net"`<br />
    Also, it could be run in the local host:<br />
    `REACT_APP_DATABASE_URL = "http://localhost:3008"`<br />
  - To reach the interactive google maps, you will need to insert your google maps api key:<br />
    `REACT_APP_GOOGLE_MAPS_API_KEY=""`

## Available Scripts

In the project directory, you can run:

### `npm run start-server`

Runs JSON server. Edit `db.json` to update data.

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run lint`

Runs all linters and prettier and shows any warnings/errors in console.
