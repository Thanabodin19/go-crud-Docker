# Go-lang
### $ `go mod init api`
### $ `go get github.com/gorilla/mux`
### $ `go get github.com/lib/pq`
### $ `touch main.go Dockerfile docker-compose.yml`

# Docker compose
### $ `docker compose up -d go_db`
### $ `docker compose build`
### $ `docker compose up go-app`
up scall
### $ `docker compose up --scale go-app=3 -d --build`


## Create
POST : localhost:8000/humans

## Read 
all human\
GET : localhost:8000/humans

select human {id}\
GET : localhost:8000/humans/{id}

## Update
PUT : localhost:8000/humans/{id}

## Delete
DELETE : localhost:8000/humans/{id}
