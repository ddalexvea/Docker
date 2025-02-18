### How to use

```
git clone https://github.com/ddalexvea/Docker.git
cd Docker/postgresql
```

```
DD_API_KEY=xxxxx DD_SITE=xxxxx docker-compose up -d
```

check postgres:

```
docker exec -ti postgresql-ddagent agent check postgres
```
