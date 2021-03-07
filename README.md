# Grafana + Prometheus monitoring on localhost
Sample setup for running ready to use grafana + prometheus on local developer machine. This project is releated to a small and focused tutorial published on [ProductionReady.dev](https://productionready.dev)

## Running
For Linux machines you may need to uncomment:
```
    extra_hosts:
      - "host.docker.internal:host-gateway"
```
For Mac and Windows host machines no changes needed.

Running localhost monitoring stack:
```docker-compose up```

## Overview
![Overview](http://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/rutkowskij/tutorials/master/localhost-metrics-prometheus/overview.iuml)

