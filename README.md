## --help

* Show command line options

## --nodb

* Start mongo shell without connecting to a database.

## --shell

* Used in conjunction with a JavaScript file (i.e. <file.js>) to continue in the mongo shell after running the JavaScript file.

## help

* Show help.

## db.help()

* Show help for database methods.

## db.<collection>.help()
  
* Show help on collection methods. The <collection> can be the name of an existing collection or a non-existing collection.

## show dbs
  
* Print a list of all databases on the server.

use <db>
  
  
Switch current database to <db>. The mongo shell variable db is set to the current database.

show collections
  
  
Print a list of all collections for current database.

show users
  
  
Print a list of users for current database.

show roles
  
  
Print a list of all roles, both user-defined and built-in, for the current database.

show profile
  
  
Print the five most recent operations that took 1 millisecond or more.

show databases
  
  
Print a list of all available databases.

load()
  
  
Execute a JavaScript file.

db.auth()
  
  
If running in secure mode, authenticate the user.

coll = db.<collection>
  
  
Set a specific collection in the current database to a variable coll, as in the following example:
coll = db.myCollection;
You can perform operations on the myCollection using the variable, as in the following example:
coll.find();

db.collection.find()
  
  
Find all documents in the collection and returns a cursor.

db.collection.insertOne()
  
  
Insert a new document into the collection.

db.collection.insertMany()
  
  
Insert multiple new documents into the collection.

db.collection.updateOne()
  
  
Update a single existing document in the collection.

db.collection.updateMany()
  
  
Update multiple existing documents in the collection.

db.collection.deleteOne()
  
  
Delete a single document from the collection.

db.collection.deleteMany()
  
  
Delete documents from the collection.

db.collection.drop()
  
  
Drops or removes completely the collection.

db.collection.createIndex()
  
  
Create a new index on the collection if the index does not exist; otherwise, the operation has no effect.

db.getSiblingDB()
  
  
Return a reference to another database using this same connection without explicitly switching the current database. This allows for cross database queries.
