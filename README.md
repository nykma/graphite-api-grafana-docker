# graphite-api + Grafana docker-compose recipe

## Usage

    $ docker-compose up -d

## Configure

### Containers

See `./docker-compose.yml`

> Notice that `grafana` and `graphite` are not linked with each other - you can deploy them on separate servers, just deleting the part you don't need.

### Carbon / Whisper

`./conf`

> SEEALSO: [ennexa/graphite](https://hub.docker.com/r/ennexa/graphite/~/dockerfile/)

### Grafana

Add `environment` in `./docker-compose.yml`.

> SEEALSO: [grafana/grafana](https://hub.docker.com/r/grafana/grafana), [Configuration - Grafana Documentation](http://docs.grafana.org/installation/configuration/)
