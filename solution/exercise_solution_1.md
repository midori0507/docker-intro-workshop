1a. 
`docker container run --name=digia -p 80:100 nginx`
`docker container rename digia foo`
1b.
`docker rm foo`

2a.
`docker container run --name=database -d -e MYSQL_RANDOM_ROOT_PASSWORD=true -p 8081:8082 mysql`
2b.
`docker rm -f [database_container_hash]`
2c.
`docker logs database | grep "GENERATED"`

3a.
`docker container run -d node:13-alpine`
`docker container run -d node:11`
`docker container run -d node:10-slim`

3b.
`docker container prune`
OR
`docker rm -f [those_container_hash by space]`