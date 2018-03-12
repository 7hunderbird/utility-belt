## BOSH

     6868 - bosh-agent
    25555 - bosh-director

## Prometheus

What uses ports?

The **core components**, **exporters**, **adopters**, **webhooks**, use ports.

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
