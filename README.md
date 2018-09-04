# prometheus-alerting-demo
Just a simple demo for synthetic Prometheus alerting metrics

Run `docker-compose up` and visit http://localhost:9090/graph?g0.range_input=1h&g0.expr=ALERTS&g0.tab=1.
You will see that Prometheus generates a synthetic metric for each pending/firing alert.
