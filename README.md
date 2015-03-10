# first-api-node-express-mongodb
First API with MEN of MEAN.js

## Instructions

Step 1 : Start mongod
``mongod``
Step 2 : Load data in mongo
``mongoimport --db simple --collection people --jsonArray data.json``



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

