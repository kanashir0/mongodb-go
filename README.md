# mongodb-go

> :warning: This is a repository created to learn a specific technology, it does **NOT** follow the best practices for a **production environment**: Be very careful here!

## Using MongoDB

In this project we'll use **docker-compose** to host our MongoDB instance. So make sure you have **docker** and **docker-compose** installed in your machine, and modify the `docker-compose.yml` file to fix the MongoDB data directory in the `volumes` section. To get the database up and running just run the below code in your terminal.

```bash
cd mongodb-go && mkdir database 
docker-compose up -d
```