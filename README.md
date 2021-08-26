# Docker Compose Nodejs and MongoDB example

## Run the System
We can easily run the whole with only a single command:
```bash
docker-compose up
```

Docker will pull the MongoDB and Node.js images (if our machine does not have it before).

The services can be run on the background with command:
```bash
docker-compose up -d
```

## Stop the System
Stopping all the running containers is also simple with a single command:
```bash
docker-compose down
```

If you need to stop and remove all containers, networks, and all images used by any service in <em>docker-compose.yml</em> file, use the command:
```bash
docker-compose down --rmi all
```

For more detail, please visit:
> [Docker Compose Node.js Express and MongoDB example](https://www.bezkoder.com/docker-compose-nodejs-mongodb/)

Related Posts:
> [Node.js, Express & MongoDb: Build a CRUD Rest Api example](https://bezkoder.com/node-express-mongodb-crud-rest-api/)

> [Server side Pagination in Node.js with MongoDB and Mongoose](https://bezkoder.com/node-js-mongodb-pagination/)

Security:
> [Node.js + MongoDB: User Authentication & Authorization with JWT](https://bezkoder.com/node-js-mongodb-auth-jwt/)

Associations:
> [MongoDB One-to-One relationship tutorial with Mongoose examples](https://bezkoder.com/mongoose-one-to-one-relationship-example/)

> [MongoDB One-to-Many Relationship tutorial with Mongoose examples](https://bezkoder.com/mongoose-one-to-many-relationship/)

> [MongoDB Many-to-Many Relationship with Mongoose examples](https://bezkoder.com/mongodb-many-to-many-mongoose/)
