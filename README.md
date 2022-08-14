# Prometheus Grafana Sandbox

## Running Prometheus + Grafana
Running the docker-compose, Prometheus will be available on http://localhost:7000 and Grafana on http://localhost:7001

```sh
docker-compose up -d
```

The Prometheus is pulling every 5 seconds the target host.docker.internal:8080

## Grafana Dashboards
### Throughput

![throughput](img/throughput.png)
