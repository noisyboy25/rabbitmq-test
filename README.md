# rabbitmq-test

## Quickstart
Run this to start the Docker Compose stack
```sh
docker-compose up
```
Install dependencies
```sh
go mod download
```
Send a task to RabbitMQ
```sh
go run ./worker/ [message]
```
