# Welcome to the Anythink Market repo

To run the app in your local environment follow the below steps !
- Install ([Docker](https://docs.docker.com/desktop/install/windows-install/)) (if you don't have it).
- Once Docker is installed run the command `docker -v` and `docker-compose -v` to verify that Docker is ready.
- Then, run `docker-compose up` from root directory of the project to load Anythink's backend and frontend.
- If everything went correctly the backend should be running and able to connect to your local database. 
- Test this by pointing your browser to http:localhost:3000/api/ping
- Now that the backend is working check the frontend and make sure it's connected to the backend.
- You can check that by going to http://localhost:3001/register and you should be able to create an account (Choose a cool nickname !).
- If everything worked correctly that Congrats you're done with the setup in your local device 🥳!

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
