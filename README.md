# Kibana Dashboard

This project is supposed to create a kibana dashboard with built in elasticsearch. Here is service default configuration

|Service | Port | Url | Username  | Pass |
|---|---|---|---|---|
|elasticsearch|9200|localhost|-|-|
|kibana|5601|localhost|-|-|

## Configuration

You can update the configuration for kibana dashboard on `conf/kibana.yml`

## Run Service

Use this command to start the service

```
docker-compose up --d --build
```

Use this comman dto stop the service

```
docker-compose down
```


