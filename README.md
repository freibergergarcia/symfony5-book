# SYMFONY GUESTBOOK

Just saving as go.

## Branch strategy

Will create one branch by step, and I will have two environments:
- dev
- prod

Each step will be a feature branch which will be merge into its own environment.

## Docker commands
`docker-compose up -d` build and detach from images

`docker-compose ps` list services

## Run psql on docker
`docker exec -it guestbook_database_1 psql -U main -W main`

