# docker-compose-db

```
# setup ENV
cp .env.sample .env
```

```
# run postgresql
docker compose up
```

```
# connect psql
psql -h localhost -U $POSTGRES__USER -d $POSTGRES__DATABASE_NAME
```