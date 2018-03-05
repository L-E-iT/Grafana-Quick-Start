# Grafana-Quick-Start

### Requires:
- Docker

### How to start:
- Pull down into local directory
- run ```docker-compose up``` or ```docker-compose up -d``` for a less verbose output.

### Services started:
Service | Host:Port | Purpose
--- | --- | ---
Grafana | 127.0.0.1:3000 | Data graphing and server monitoring
Prometheus | 127.0.0.1:9090 | Data gathering and exporting
Node-Exporter-1 | 127.0.0.1:9100 | Data output
Node-Exporter-2 | 127.0.0.1:9200 | Data output
Node Exporter-3 | 127.0.0.1:9300 |  Data output
