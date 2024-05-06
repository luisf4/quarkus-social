# How to run the postgress db
### Create a docker network
```
docker network create quarkus-social
```
This creates a network named quarkus-social, i do this for separing the project container.


### Run docker compose
```
docker-compose -f docker-compose.yml up
```
Here we will run the docker-compose.yml file 

#### done! now postgres are on port 5432 

