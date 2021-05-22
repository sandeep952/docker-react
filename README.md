#Docker commands

## Run with docker volumes on windows
$ `winpty docker run -it -p 3000:3000 -v /app/node_modules -v "/$(PWD)":/app -e CHOKIDAR_USEPOLLING=true container_id`

## docker-compose
$ `environment only required in windows for hot reloading`



