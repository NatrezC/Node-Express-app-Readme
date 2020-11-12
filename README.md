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

## Using Postgres

- type in psql -U postgres -h localhost in terminal
- type in your password
- You are now connected into postgres

## Functions of Postgres

- \q quit sql
- \l Lets you view all your db
- \c "nameofdb" connects to db
- \dt view the tables in th db that you are connected to
- \d "example" look at the structure of the table
- SELECT * FROM "table"; see all data from that table
- DROP DATABASE "name" delete db

### How to find somone in a table
- by name = SELECT * FROM "example" WHERE name = 'Paul';
- by ids = SELECT id, name FROM students;
- delete from table =  DELETE FROM students WHERE name = 'Paul'; 'n ALTER TABLE
  
