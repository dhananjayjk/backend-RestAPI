# backend-RestAPI
- This is server side REST API that handles restaurant portal.
- MongoDB database is used
- Https traffic is supported
- Facebook OAuth2 Login Option
- Cross Origin File Sharing (MongoDB) 
- I found this course https://www.coursera.org/learn/server-side-nodejs very helpful for learning server side development
- Use Postman for testing your REST APIs https://www.postman.com/
- Starting MongoDB server
  - ```mongod --dbpath=data --bind_ip 127.0.0.1```
- Entering Mongo Envirnment
  - ```mongo```
 - Some Useful Commands
  -
    ```show collections
    use conFusion
    db
    db.stats()
    db.help()
    db.dishes.insert( {"name":"Uthappizza","description":"Test"} );
    db.dishes.find()
    db.dishes.find().pretty()
    var id = new ObjectId();
    id.getTimestamp();```
  
- Creating Admin Account by changing flag
  - ```db.users.update({"firstname":"dhananjay"},{$set:{"admin":true}})```
