# Classified App

Build with microservices structures

to run the migration we need to do

```
docker exec -it 16634718a672 bash
```
the number above is the docker ps hash
and then run

```
yarn db:migrate
```


Database connection info:

HOST: 127.0.0.1
USER: root
PASSWORD: password
PORT: 7200 (for listing service)
PORT: 7201 (for user service)