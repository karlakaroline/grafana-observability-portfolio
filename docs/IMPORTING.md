# Importing the demo dashboards

1. Install the plugins required by the dashboard (for example Zabbix datasource and HTML Graphics where applicable).
2. Create your own datasource(s) in Grafana.
3. Replace placeholder datasource UIDs in the JSON or remap them during import when your Grafana version supports it.
4. Update demo host/group/item filters to match your lab environment.
5. For the NOC ticket dashboard, configure Jira authentication in a datasource/proxy rather than putting an `Authorization` header inside the dashboard JSON.
6. Validate queries in Query Inspector before adapting thresholds or status logic.
