# Critical Services Observability Dashboard

A multi-source Grafana dashboard for visualizing the operational health of critical services.

## Technical highlights

- **Zabbix** checks for synthetic/web scenarios, application state and supporting diagnostics.
- **Elasticsearch/APM** transaction data for failure-rate context.
- Custom **HTML Graphics + JavaScript + CSS/SVG** presentation.
- Service states such as `UP`, `ATTENTION`, `DOWN` and partial/unknown data.
- Separate technical bridge panels for selected detailed checks.
- Drill-down pattern to specialized dashboards.
- Logic that preserves the last valid visual state during intermediate Grafana refresh states.
- Reduced-motion handling for accessibility.

## Public-demo changes

Internal service names, production hostnames, bank/end-point identifiers, dashboard UIDs and datasource UIDs were replaced with fictional demo values.

## Datasources

- Zabbix datasource placeholder: `REPLACE_ZABBIX_DATASOURCE_UID`
- Elasticsearch datasource placeholder: `REPLACE_ELASTICSEARCH_DATASOURCE_UID`

## Files

- `dashboard.sanitized.json` — public-safe Grafana export
- `screenshots/` — add reviewed screenshots here
