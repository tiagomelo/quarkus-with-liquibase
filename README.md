# quarkus-with-liquibase

This sample project shows how to use [Liquibase](https://www.liquibase.com/) for database migrations with [Quarkus](https://quarkus.io/).

It also aims to show how to configure your local environment in a way you don't lose your data, which is what happens when you launch the project with `quarkus dev`.

## using dev profile

```
$ quarkus dev
```

## using `local` profile

1. launch [Docker](docker.com)
2. `docker-compose up -d books_psql_db`
3. `quarkus dev -Dquarkus.profile=local`