# Kubernetes Monitoring and Logging

## Objective

This project demonstrates how monitoring and logging can be implemented in a Kubernetes environment using Prometheus, Grafana, and the EFK Stack.

## Components

### Prometheus

Collects metrics from Kubernetes workloads and infrastructure.

### Grafana

Visualizes Prometheus metrics through dashboards.

### Elasticsearch

Stores application logs.

### Fluentd

Collects and forwards logs to Elasticsearch.

### Kibana

Visualizes and searches logs stored in Elasticsearch.

## Project Files

* prometheus.yml
* grafana-dashboard.json
* efk-deployment.yaml

## Monitoring Workflow

1. Prometheus collects metrics.
2. Grafana visualizes metrics.
3. Fluentd collects logs.
4. Elasticsearch stores logs.
5. Kibana displays logs.

## Example Commands

```bash
kubectl apply -f efk-deployment.yaml
kubectl get pods
kubectl get services
```

## What I Learned

* Kubernetes monitoring concepts
* Prometheus configuration
* Grafana dashboards
* Log aggregation using the EFK Stack
* Monitoring and observability best practices

## Challenges Faced

Understanding monitoring, metrics collection, and centralized logging was initially challenging. Learning how Prometheus, Grafana, Elasticsearch, Fluentd, and Kibana work together helped me understand observability in Kubernetes.
