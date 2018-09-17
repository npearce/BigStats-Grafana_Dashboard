# BigStats Dashboard for Grafana

Grafana Dashboards for the BigStats telemetry exporter.


<img align="right" width="150px" src="_static/BigStats-300dpi.png" alt="BigStats_Logo"/>

Requires F5 BIG-IP telemetry exporter, BigStats:

[https://github.com/f5devcentral/BigStats](https://github.com/f5devcentral/BigStats)

**Dashboard Overview Diagram**

![image](_static/dashboard_overview1.png)

Layout:

```
BigStats - Overview DB
|- Device: CPU
|- Device: RAM
|- Services: Variable
|- Tenant: Variable
|- Pool: variable
```

## Install

Per these instructions: [Grafana Export / Import](http://docs.grafana.org/reference/export_import/)

To import a Dashboard, in Grafana, open 'Dashboard Search and hit the 'Import' button...

OR, Search for **BigStats** in Grafa Dashboards.


<!--
## Grafana Privisioning

Maybe we should to this? 

http://docs.grafana.org/administration/provisioning/

-->