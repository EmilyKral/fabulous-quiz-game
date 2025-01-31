# LAP 3 Portfolio Project: Fabulous Quiz Game

A project to create an online quiz game where multiple users can compete against each other in a trivia quiz. The host of the quiz can choose the category, question difficulty, number of questions, and time per question. Other users can join the game by using the game ID and all players recieve the same questions from the Open Trivia Database API. At the end of the game, players can see the results, and there is also a leaderboard to show the top scoring players who have used the app.

Done as a part of futureproof's Conway cohort

## Installation and Usage

**Installation**

- Clone or download the repo
- Run `git submodule update --init` to get the submodules

**Usage**

- `cd` into `/server`
    - `bash _scripts/startDev.sh` starts the server and database and serves the api on localhost:3000
    - `bash _scripts/stop.sh` stops running all services but keeps updates to the database
    - `bash _scripts/teardown.sh` stops running all services and removes all containers and volumes
- `cd` into `/client`
    - `npm run dev` runs the client on localhost:8080

## Technologies

- HTML/CSS/React for client side
- Socket.io for multi-user functionality
- Jest for testing
- PostgreSQL for database
- Docker

## Wins and Challenges

**Wins**

- Successfully implementing socket.io to make the game playable by multiple users on multiple devices
- Meeting all requirements of the brief

**Challenges**

- Implementing, and keeping track of, the functionality of socket.io was a challenge

## Contributors

- [Peter Andrews-Briscoe](https://github.com/PeterAndrewBriscoe)
- [Rhys Cairns](https://github.com/cairnsy6)
- [Emily Kral](https://github.com/EmilyKral)
- [Kelvin Stephano](https://github.com/kstephano)