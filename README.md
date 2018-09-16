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

You can paste the JSON input right into a Grafana. Will add this to the Grafana community once v0.1 is ready for release.

<!--
## Grafana Privisioning

Maybe we should to this? 

http://docs.grafana.org/administration/provisioning/

-->