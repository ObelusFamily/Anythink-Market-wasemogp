# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

  **1. Clone the repo.**
  
  **2. cd into the project folder (cd Anythink-Market-wasemogp)**

## Second Setup

   **Run docker-compose -up in your codespace's terminal to load Anythink's backend and frontend.**
 
## Third Setup
 **1. Once docker-compose finishes loading up, the backend should be running and able to connect to the database.**
 
 **2. After the server is up, make sure you test the backend it by pointing your browser to https://taofeek-ob-upgraded-space-cod-xx7jrw9xxxwcv7p5-3000.preview.app.github.dev/api/ping**
 
 **3. Now, it’s time to check the frontend and make sure it’s connected to the backend.**
_If everything is working properly, you’ll be able to create a new user on https://taofeek-ob-upgraded-space-cod-xx7jrw9xxxwcv7p5-3001.preview.app.github.dev/register Create one (choose a cool nickname and everything) and you’ll be able to move to the next task._
