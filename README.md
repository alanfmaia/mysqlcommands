# mysqlcommands
 docker container run -d -p 3306:3306  -e MYSQL_DATABASE=docker_db -e MYSQL_USER=docker_usr -e MYSQL_PASSWORD=docker_pwd mysql

# postgres
docker container run -d -p 5432:5432  -e POSTGRES_DB=curso_docker -e POSTGRES_USER=docker_user -e POSTGRES_PASSWORD=docker_pwd postgres

# Mongo
docker container run -d -p 27017:27017 -e MONGO_INITDB_ROOT_USERNAME=mongo_usr -e MONGO_INITDB_ROOT_PASSWORD=mongo_pwd

