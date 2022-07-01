# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

For initial setup, one needs to:
1. Install Docker
2. Run docker-compose up in the root folder
3. Once "docker-compose up" has run, if you see an error message of pending migrations just click on Run Migrations button
4. Visit [localhost:3000/api/ping] to test backend, and
5. Visit http://localhost:3001/register to test frontend
This should be enough for initial setup.

