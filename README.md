# microservices monitoring

## Architecture

- Traefik
- Prometheus
    - Pushgateway missing
- Grafana
    - Visualizations
- Alertmanager
    - Configured to send alerts regarding resource usage and container states.
    - Alerts sended to a Slack channel
- Microservices: ui + webservices
    - 2 replicas each which we loadbalance using Traefik

## Traefik
![](/docs/traefik.PNG)
![](/docs/traefik1.PNG)
![](/docs/traefik2.PNG)
![](/docs/traefik3.PNG)

## Grafana
![](/docs/grafana-docker.PNG)
![](/docs/grafana-node.PNG)
![](/docs/grafana-traefik.PNG)
