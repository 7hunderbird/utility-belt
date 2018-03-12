## BOSH

       22 - ssh
     6868 - bosh-agent
     8443 - UAA API (User Account and Authentication)
     8844 - Credhub API
    25555 - bosh-director

## Prometheus

### Core components

    9090 - Prometheus server
    9091 - Pushgateway
    9092 - UNALLOCATED (to avoid collision with Kafka)
    9093 - Alertmanager
    9094 - Alertmanager clustering

### Exporters we use

    9000 - Node exporter
    9190 - BOSH exporter
    9193 - CF exporter

For all other exporters and corresponding ports, check out [Default Port Alocations](https://github.com/prometheus/prometheus/wiki/Default-port-allocations).
