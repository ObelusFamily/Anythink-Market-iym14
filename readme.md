# Welcome to the Anythink Market repo

To start the app use, Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as a reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine._
## Steps to setup the machine
1. [Install Docker](https://docs.docker.com/get-docker/)
2. Verify whether docker is running or not by running the following commands `docker -v` and `docker-compose -v`
3. Now, Run `docker-compose up` from the project **root directory** to load *Anythink's backend and frontend*
4. If Docker is working correctly, the backend should be running and able to connect to your **local database**. Let's test this by pointing your **browser** to `http://localhost:3000/api/ping`
5. If you see the backend up and running, We can move to the next steps.
6. Now, it’s time to check the **frontend** and make sure it’s connected to the **backend**
7. If everything is working properly, you’ll be able to create a new user on `http://localhost:3001/register`
8. Create one (choose a cool nickname and everything)

