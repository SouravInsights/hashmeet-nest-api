# nest-api-starter - a starter api built using nest.js

This tiny repo is a starter kit for people getting started with [Nest.js](https://nestjs.com/). 
It might give you a practical walkthrough of some of the concepts of Nest.js. 

> Hope it helps you in some way with your learning journey.

## Built using
- [Nest.js](https://nestjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Mongoose](https://mongoosejs.com/)
- [Typescript](https://www.typescriptlang.org/)

## How to setup

### project setup
- `git clone https://github.com/SouravInsights/nest-api-starter.git`
- `cd nest-api-starter`
- `yarn install`
- `yarn dev`
### db setup

- mongodb installation
  - install [Mongodb Community Server](https://www.mongodb.com/try/download/community?tck=docs_server) and refer to [how to download and setup mongodb](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/) guide for more information.
- local setup
  - create data/db directory in any of your drive where mongodb will store all the data
    - `cd F:\`
    - `md "\data\db"`
  - run `mongod --dbpath "F:/data/db"` to start mongodb
- create your database
  -  run `use nest-api-db` which will craete your database, if the database doesn’t exist already
  
- mongodb compass installation
  - you can also [install mongodb compass](https://docs.mongodb.com/compass/master/install) as the gui for mongodb
  - open mongodb compass, connect to your local mongodb server and create your database from the gui

## Project structure
(to be added)
