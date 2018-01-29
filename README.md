# databaselesson

## start database

   docker-compose up -d


## connect to mongo db

   docker exec -it mongo101 mongo


## stop database 

   docker-compose down


## some useful commands

   docker ps
   docker-compose ps

## delete all containers

   docker rm -f `docker ps -q`