# Jadro IoT Labu

Jadro obsahuje tieto služby:

* Portainer
* Mosquitto Broker
* Theengs Gateway
* Telegraf
* Chrony
* Traefik
* Homepage

## Spustenie

```bash
$ docker compose --env-file ../global.env --env-file core.env up --detach
```
