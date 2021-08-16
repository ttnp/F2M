# Data Engineer Test from Free2Move

Build & lauch:

> docker-compose up --build

## Create db table

Commands to connect the db table:

> docker ps 

Used to identify the CONTAINER ID of postgres

> docker exec -it <CONTAINER_ID> bash

> psql postgres://dataengineer:secret@localhost:5432/database
