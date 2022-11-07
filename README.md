Grafana Dashboards
=====================

These are Grafana dashboards we use at Oxeva.
It may only work here, but you are free to test and use it for you :)

How to use on Grafana helm chart
--------------------------------
complete grafana.yaml like this : 
```
dashboards: 
  default:
    alerting:
      url: https://raw.githubusercontent.com/oxeva/grafana-dashboards/main/general/alerting.json
```
