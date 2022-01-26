# mongodb-practice

Reference - https://www.youtube.com/watch?v=pWbMrx5rVBE

basic commands
-----------------

- To check the databases we have

*> show dbs*


- To check which database we currently in

*> db*


- To switch to a different databases

*> use mycustomer*


- To check the collections we have

*> show collections*


- To create an user

*> db.createUser({
  user: "Joy",
  pwd: "passcode",
  role: ["myAdmin", "readWrite"]
})*


- To create a collection
*> db.createCollection('cusotmers')*


- To Insert one data

*> db.cusotmers.insert({.........})*

- To read the data inside a collection in pretty format

*> db.customers.find().pretty()*


- To Update one data

*> db.cusotmers.update({"user_id": uuid_............ }, {$set:{"gender":"male"}})*

