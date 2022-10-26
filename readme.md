# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

### Instructions for setting up the environment

- If you do not have Docker in you local computer get it [here](https://docs.docker.com/desktop/install/linux-install/) and follow the installation instractions

- After installing Docker install Docker Compose using this manual [here](https://docs.docker.com/compose/install/)

- Run `docker-compose -v` on your terminal to see if you've successfully installed Docker compose

- Run `docker-compose up` and wait for everything to download and finishing setting up.

- If Docker is working correctly, the backend should be able to connect to your local database test this by going to [http://localhost:3000/api/ping](http://localhost:3000/api/ping)
