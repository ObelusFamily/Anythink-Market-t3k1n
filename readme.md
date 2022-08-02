# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
[^1]: Clone the repository by running the command `git clone https://github.com/vanessa-cooper`.
[^2]: Install docker from [here](https://docs.docker.com/get-docker/).
[^3]: After installing verify if docker is running by following commands: `docker -v` and `docker-compose -v`.
[^4]: Run  `docker-compose up` from the project root directory to load Anythink's backend and frontend.
    * If Docker is working correctly, the backend should be running and able to connect to your local database.
    * Test this by pointing your browser to http://localhost:3000/api/ping
[^5]: Since backend is running now check for frontend and check it's connection with backend.
    * If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register
    * Create a new user.