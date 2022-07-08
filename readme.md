# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup - Installation

GITHUB

Step 1:<br> 
a. Install Git on your local machine.([Link](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git))<br>
b. Fork this repository on your Github.<br>
c. Create a folder on your Desktop and open it with your command line or bash.<br>
d. Write the following command `git clone https://github.com/github-username/Anythink-Market-6qihj.git`.Put your username inside `github-username`.

DOCKER

Step 2:<br>
a. Install Docker on your Machine.([Link](https://docs.docker.com/get-docker/))<br>
b. To verify Docker is ready run the following command `docker -v`.<br>
c. Run `docker-compose up` from the project root directory to load Anythink's backend and frontend.<br>
d. To verify the backend should be running and able to connect to your local database. Open any Browser on your System and paste the following link `http://localhost:3000/api/ping`.<br>
e. If you see something like this on your Browser it means you have succesfully connected with your Backend:
![ping](https://user-images.githubusercontent.com/55699684/177951060-516c920f-2e03-424b-b053-b6df64aa9d6e.png)<br>

FRONTEND

<p>It’s time to check the frontend and make sure it’s connected to the backend.</p>

Step 3:<br>
a. If everything is running perfectly, you’ll be able to create a new user on `http://localhost:3001/register` paste this link on your Browser.<br>
b. Everthing should work perfectly fine:![home](https://user-images.githubusercontent.com/55699684/177952379-008b5875-5c19-4987-ba57-f9a777315cd3.png)


