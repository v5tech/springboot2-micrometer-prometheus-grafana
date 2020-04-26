# springboot2-micrometer-prometheus-grafana

# Screenshots

![](Screenshots/prometheus_alerts.png)
![](Screenshots/prometheus_config.png)
![](Screenshots/prometheus_disco.png)
![](Screenshots/prometheus_rules.png)
![](Screenshots/prometheus_targets.png)
![](Screenshots/prometheus_alertmanager.png)
![](Screenshots/cadvisor.png)
![](Screenshots/grafana_jvm.png)
![](Screenshots/grafana_redis_dashboard_for_prometheus.png)
![](Screenshots/grafana_docker_container_hostmetrics.png)
![](Screenshots/skywalking_1.png)
![](Screenshots/skywalking_2.png)
![](Screenshots/skywalking_3.png)
![](Screenshots/skywalking_4.png)

skywalking 添加jvm启动参数

```
-javaagent:/Users/amz/develop/skywalking-apm/agent/skywalking-agent.jar
-DSW_AGENT_COLLECTOR_BACKEND_SERVICES=127.0.0.1:11800
-DSW_AGENT_NAME=springboot2-micrometer-prometheus-grafana
```

# 参考文档

https://prometheus.io/docs/prometheus/latest/installation

https://prometheus.io/docs/prometheus/latest/getting_started

https://prometheus.io/docs/guides/cadvisor

https://micrometer.io/docs/registry/prometheus

https://blog.csdn.net/aixiaoyang168/article/details/100866159

https://www.jianshu.com/p/1cb66d48920b

https://www.jianshu.com/p/1f05476ebcee

https://github.com/percona/grafana-dashboards

https://github.com/oliver006/redis_exporter

# Grafana Dashboard

https://grafana.com/grafana/dashboards/7362

https://grafana.com/grafana/dashboards/763

https://grafana.com/grafana/dashboards/4701

https://grafana.com/grafana/dashboards/3457

https://grafana.com/grafana/dashboards/10619