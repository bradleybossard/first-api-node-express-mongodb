# first-api-node-express-mongodb
First API with MEN of MEAN.js

## Instructions

Step 1 : Start mongod

``mongod``

Step 2 : Load data in mongo

``mongoimport --db simple --collection people --jsonArray data.json``

Step 3 : Install dependencies

``npm install``

Step 4 : Run server (use nodemon to automatically pick up changes
``nodemon server.js``
Step 5 : Copy url and view in browser
``http://localhost:9113/people``


## Mongo commands
use the imported simple database

``use simple``

get one user

``db.people.findOne()``

remove people collection
``db.people.remove()``
drop database
db.dropDatabase()
show current databases
``show dbs``

