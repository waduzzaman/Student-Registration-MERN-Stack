# Student Registration
MERN Stack - Bootstrap - Deploy on Heroku


## Table of Contents
* [About The Project](#about)

* [Tech Stack](#tech-stack)

* [Work flow](#work-flow)

* [Getting started](#getting-started)

## About The Project
A web application to register student information with a selection of majors

## Tech Stack
  * ##### MERN: MongoDB, Express, ReactJS, NodeJS
  * ##### Bootstrap  
  
## Work Flow
* User can view, register, update and delete student information

* User can view, add, edit and delete majors


## Getting started
**1.** In order to run this app, you need to have `node.js` installed.

**2.** Install server-side and client-side dependencies

##### Environment variables

Create `.env` file in root folder

```
NODE_ENV=development
PORT=5000
MONGO_URI=mongodb+srv://<DB_USERNAME>:<DB_PASSWORD>@cluster0.i5v06.mongodb.net/<DB_NAME>?retryWrites=true&w=majority
```
Server-side

```
npm install
```
Client-side

```
cd client
npm install
```
Run app

```
npm run dev
```
