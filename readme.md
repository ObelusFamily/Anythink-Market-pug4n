# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Instal docker from https://docs.docker.com/get-docker/
To make sure you have installed docker succefuly run `docker -v` in the terminal. In addition run `docker-compose -v`.
Then, run `docker-compose up` and wait until it finish.
To make sure the backend id up, go to http://localhost:3000/api/ping
To make sure the backend and frontend are conected go to http://localhost:3001/register. If everithing worked, you will be able to register.
