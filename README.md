# PyMongo-CRUD
Jupyter Notebook demonstrating CRUD operations on MongoDB

**Installation: **

1.https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/

2.While installing Mongodb also install MongoDB Compass to play with GUI



**Data Source:**

https://media.mongodb.org/zips.json


To convert data into required format refer below

https://stackoverflow.com/questions/55808904/how-to-add-comma-in-between-curly-braces-notepad

You can use pattern \}(\s*)\{ and replace it with pattern\}\n,\1\{

**Explanation:**

\} - match } literally

(\s*) - match zero or more white sapces and store it into capturing group

\{ - match { literally

Replacement: \1 - paste what is in first capturing group
