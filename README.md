# rpi-exporter-helm-chart
Helm chart for adding Raspberry Pi CPU temps to the stats output by [kube-prometheus-stack](https://github.com/prometheus-community/helm-charts/tree/main/charts/kube-prometheus-stack).

This is a work in progress and not a fully-featured Helm chart, but if you are running
kube-prometheus-stack on a Raspberry Pi k3s cluster, installing this chart should provide
additional metrics for each node for use in Prometheus/Grafana, such as
`rpi_cpu_temperature_celsius` for monitoring CPU temperatures.
