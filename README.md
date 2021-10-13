# Boiler plate template for a docker php, apache, and sql wrapper
## Useful commands
- remove all stopped containers:
    - ```docker rm $(docker ps --filter status=exited -q)```
- startup app
    - ```docker-compose up```
- build and startup app
    - ```docker-compose up --build```
- stop app
    - ```docker-compose down```