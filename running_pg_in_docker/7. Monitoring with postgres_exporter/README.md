# Monitoring database with postgres_exporter

## Docker Compose
### Start
`docker-compose --project-name="habr-pg-14" up -d`

### Stop
`docker-compose --project-name="habr-pg-14" down`

## Access to PgAdmin
Open in browser [http://localhost:5050](http://localhost:5050)

## PostgreSQL Exporter for Prometheus
See [postgres_exporter on GitHub](https://github.com/prometheus-community/postgres_exporter)

Open in browser [http://localhost:9187/metrics](http://localhost:9187/metrics)
