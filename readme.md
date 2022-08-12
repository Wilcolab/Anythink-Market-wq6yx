# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## Initial setup
1. Clone this repository
2. Install Docker for your machine [from here](https://docs.docker.com/get-docker/)
3. After successful installation of docker, open terminal to enter following commands to check it's installation :
    * `docker -v`
    * `docker-compose -v`
4. Open the cloned repo directory then, enter `docker-compose up` to build the frontend and backend of this project
5. To check backend is working properly and also, to see database is connected properly in your local machine visit [https://localhost:3000](https://localhost:3000)
6. Now, finally to check frontend is up and running visit [https://localhost:3001/register](https://localhost:3001/register)
7. Now, you can begin to create a new user and carry on ...
8. Congrats 🎉, you are now ready to use this project now !!