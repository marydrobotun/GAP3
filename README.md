# GAP1
Homework for Monitoring course

# WordPress Stack with Monitoring

A Docker Compose setup for running WordPress with Nginx, PHP-FPM, MySQL, and comprehensive monitoring using Prometheus and various exporters.

## Stack Components

- **WordPress**: PHP-FPM 8.2 with WordPress
- **Database**: MySQL 8.0
- **Web Server**: Nginx (latest)
- **Monitoring**:
  - Prometheus
  - Node Exporter (system metrics)
  - MySQLd Exporter (database metrics)
  - Nginx Exporter (web server metrics)
  - Blackbox Exporter (probe metrics)
  - Alertmanager (for alerts)

## Prerequisites

- Docker installed
- Docker Compose installed
- Ports 80, 9090, 9100, 9104, 9113, 9115, 9093 available

## Quick Start

1. Clone this repository

2. Create a `wordpress` directory for WordPress files:
   ```bash
   mkdir wordpress
   ```
3. Run command
   ```bash
	docker-compose up -d
   ```
