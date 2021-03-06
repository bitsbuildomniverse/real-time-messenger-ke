# react-live-messenger
## Description
A real-time chat web app where users can log in, add friends and communicate with them in real time.
This application was built publicly with the entire build process avaiable on YouTube in a tutorial format.

[YouTube Playist](https://www.youtube.com/playlist?list=PLBieMfwfePY-PPxTYmYZteqYpC_D7W1JT)

## Why?
This was a passion project. I built it for fun and to challenge myself.

## What I Learned
Through the creation of this project I gained a foundation in systems design and project management.

I learned how to use JWT for authentication and the basics of NGINX. 

Most of my growth came from the back-end implementations as I used front-end technology that was familiar to me. 

## Packages
- client - react.js frontend
- server - node.js backend
- common - code shared between client and server

## How it works
* Front-End: React.js
* Back-End: Node.js / Express.js / Socket.io
* Authenticaion: JWT
* Database: PostgreSQL and Redis
* Hosting: Digital Ocean Linux Server with NGINX and SSL

## Installation
* Clone the repository
* CD into the repository and run ```yarn``` or ```npm install```
* Make sure redis is installed and the ```redis-cli``` functions properly
* Create a postgres database and a table called users, as defined in ```./packages/server/database.sql```
* Create a file named ```.env``` in ```./packages/server``` and make sure it has the following variables defined:
<br/>DATABASE_NAME=
<br/>DATABASE_HOST=
<br/>DATABASE_USER=
<br/>DATABASE_PASSWORD=
<br/>DATABASE_PORT=
<br/>COOKIE_SECRET=
* Run ```yarn dev:server``` and ```yarn dev:client```
