# Additional Services

For adding additional services, which are not part of the *Open IoT Gateway* stack, use additional `docker-compose.yaml` file. For `homepage.group` use label `Services`

if you want to connect to some core services, you can connect with IP address or you can connect your services to the same network `iotlab` by specifying the network in `docker-compose.yaml` file following way:

```yaml
networks:
  iotgw:
    external: true
```


## Running

```bash
$ docker compose --env-file ../global.env --env-file services.env up --detach
```

