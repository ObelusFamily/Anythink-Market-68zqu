# Welcome to the Anythink Market repo

To start the app you will need to have Docker installed (follow the instruction here: https://docs.docker.com/get-docker/). 

After you installed Docker navigate to the root directory of the repository, you will find there a docker-compose.yml file.

Run: 'docker-compose up -d'  it will start both frontend and backend, including all the relevant dependencies, and the db.

Check that the backend is up and running by ping to it (run 'ping http://localhost:3000/api/ping') if you didnt get error it's mean the backend is up.

Check that the client is ok too, navigate to http://localhost:3001/register and register yourself while you are there.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.
