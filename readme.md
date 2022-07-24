# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Install docker from https://docs.docker.com/get-docker/
Once installed you should be able to check via running `docker -v` and `docker-compose -v`
In the root directory of this repo, run `docker-compose up` to start the builder process.
You should be able to see a response from http://localhost:3000/api/ping
You should be able to register a user at http://localhost:3001/register

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
