# An ORM for node, express and postgresql

## Postgres in this application is dockerized.

```
docker-compose build
docker-compose up
```
## Install node js packages required for this application
### Migrate the schemas and run the application


```
yarn install
yarn migrate
yarn start
```

visit `localhost:5000` to run the mapper which populates the `User' table

visit `localhost:5000/project` to run the mapper which populates the `Project' table

