# Node-Express-app-Readme

## Create Node Project

- mkdir
- npm init -y
- touch index.js 
- npm i // express(or others like express-ejs-layouts, dotenv...)
- echo "node_modules" >> .gitignore

## Routes
| HTTP  | CRUD   | Example        |
|-------|--------|----------------|
| GET   | READ   | Read profile   |
| POST  | CREATE | Post a comment |
| PUT   | UPDATE | Change password|
|DELETE | DELETE | Delete a photo |

## Sequelize

-npm i -g sequelize-cli to install globally
- run your usual to create a node project (check node notes)
- run npm i pg sequelize
- sequelize init
- sequelize db: (name of the app)
- sequelize model:create -name user --attributes (all the attributes(make sure you have no spaces))
- run sequelize db: migrate
- run sequelize db:migrate:undo (undoes the last migration)

