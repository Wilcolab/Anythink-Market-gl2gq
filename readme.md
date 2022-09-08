# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

After you finish setting up the docker.Check whether the docker is working or not with the command docker --v.

Then, run docker-compose up from the project root directory to load Anythink's backend and frontend.

If Docker is working correctly, the backend should be running and able to connect to the local database.

Test whether the backend is able to connect to the local database

Then check whether the frontend is working and make sure its connected to the backend.

If everything is working properly you will be able to create a new user on the local database

