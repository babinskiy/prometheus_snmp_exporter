# prometheus_snmp_exporter

https://github.com/prometheus/snmp_exporter
https://github.com/prometheus/snmp_exporter/tree/master/generator

```
cd generator
docker buid -t snmp_exporter:generator
cd mikrotik
docuer run -v $(pwd):/opt/ snmp_exporter:generator generate
```
