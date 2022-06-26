# FreyHacks
This is our code repository for our project submission for FreyHacks

## Tech Stack:
<div align="center">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="50rem" height="50rem" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="react" width="50rem" height="50rem" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/graphql/graphql-plain.svg" alt="graphql" width="50rem" height="50rem" /> 
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="50rem" height="50rem" /> 
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flask/flask-original.svg" alt="flask" width="50rem" height="50rem" /> 
<!-- <img src=".github/flask-original.svg" alt="flask" width="50rem" height="50rem" />  -->
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="postgresql" width="50rem" height="50rem" /> 
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/github/github-original.svg" alt="github" width="50rem" height="50rem" /> 
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/digitalocean/digitalocean-original.svg" alt="digitalocean" width="50rem" height="50rem" /> 
</div>o

## Team Members:
* Zac: Full Stack Developer and Project Leader
* Luke: Frontend and Integration Developer
* Greyson: Frontend Developer and UI Designer
* Kellan: Frontend Developer and UI Designer
* Matthew: Backend Python Developer (backbone of the project)
* Scott: Backend Python Developer
* Hargun: DevOps Engineer

## Project Description 📝:

As the weather gets warmer and more activties become accessible, it becomes increasingly difficult to chose what to do in your past time. Our team has developed an app that can solve that problem. our carefully formulated software is capable of processing local weather data and reccommending weather dependant activities based on current and future weather conditions. Not only is the schedule capable of reccomding activities based on weather conditions, the app can also be used to plan events for you and your friends all within the app.

## Inspiration💡:
- We are lonely and want to find friends who do fun things

## What it does 📱:
- helps people plan and attend activities
- feature to find and add friends
- feature to find public events
- suggests activities and events based on conditions (weather, location, time, etc.)

## How we built it 💻:
- We built our mobile application in react native with TypeScript
- We used Bottom Tab Navigation as our primary navigation, then Stack Navigation as secondary navigation
- We used graphql to integrate our mobile app with our server
- We built our server in python with flask
- For graphql, we used Ariadne and SQLAlchemy
- We used PostgreSQL from our database


## CI/CD Pipeline :
- Automated by **Github Actions**
- Builds docker image, and pushes to Docker Hub
- Authenticates by SSH into **Digital Ocean** droplet linux server
- Pulls image from Docker hub into remote server and runs container
- GraphQL domain is live: sum-fun.xyz/graphql

## Challenges we ran into 💥:
- nested queries in graphql didn't work
- sql alchemy is refusing to have multiple subsequent queries
- most of us had never written in the language our whole job was in

## Accomplishments that we're proud of 🍀🍾:
- getting the weather api to work
- solving nested queries issue
- completely custom cidc piplines through github actions digitalocean ssh

## What we learned 🧠👍:
- Learned how to access and integrate data from an api

## What's next for Activity 🥚🐣🐥:
- Adding more activities
- Adding more paramaters to validity
- Improving UI

## Frontend
- React Native with TypeScript

## Backend
- GraphQL API in python with flask

