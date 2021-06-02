# Kong Demo Using Docker
This is a demo of kong using docker
- kong
- konga
- kongDB

## Running

```
docker-compose up -d  
```

```
curl http://localhost:8000
curl http://localhost:8001
```

## Access

http://localhost:1337

## Edit

After change something in server or compose

docker-compose up --build -d

## Clean Up

Tear everything down using:

```
docker-compose down
```

***
