# Monitoring Stack Setup

## Services Used
- Prometheus
- Grafana
- Node Exporter

## Setup Steps

1. Install Docker and Docker Compose
2. Create docker-compose.monitoring.yml
3. Create prometheus.yml
4. Start containers:

docker compose -f docker-compose.monitoring.yml up -d

## Access URLs

Prometheus:
http://<EC2-IP>:9090

Grafana:
http://<EC2-IP>:3001

## Grafana Login

Username: admin
Password: admin

## Dashboard

Imported Node Exporter dashboard using ID 1860.
