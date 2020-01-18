# Getting Started

Create a `.env` file in the repo top level directory that defines the following
environment variables

```
DOCKER_VERNEMQ_ALLOW_ANONYMOUS=on
INFLUXDB_USERNAME
INFLUXDB_PASSWORD
INFLUXDB_USER_TELEGRAF
INFLUXDB_USER_PASSWORD_TELEGRAF
GRAFANA_USERNAME
GRAFANA_PASSWORD
```

Here is an example `.env` file with insecure, default passwords:

```
DOCKER_VERNEMQ_ALLOW_ANONYMOUS=on

INFLUXDB_USERNAME=admin
INFLUXDB_PASSWORD=admin

INFLUXDB_USER_TELEGRAF=telegraf
INFLUXDB_USER_PASSWORD_TELEGRAF=telegraf

GRAFANA_USERNAME=admin
GRAFANA_PASSWORD=admin
```

Start with with following command:

```
docker-compose up
```

