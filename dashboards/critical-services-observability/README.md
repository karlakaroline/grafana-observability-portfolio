# Critical Services Observability Dashboard

A multi-source Grafana dashboard for visualizing the operational health of critical services.

## Dashboard Preview

![Critical Services Observability Dashboard](screenshots/critical-services-preview.png)

## Technical Highlights

- **Zabbix** checks for synthetic/web scenarios, application state and supporting diagnostics.
- **Elasticsearch/APM** transaction data for failure-rate context.
- Custom **HTML Graphics + JavaScript + CSS/SVG** presentation.
- Service states such as `UP`, `ATTENTION`, `DOWN` and partial/unknown data.
- Separate technical bridge panels for selected detailed checks.
- Drill-down patterns to specialized dashboards.
- Logic that preserves the last valid visual state during intermediate Grafana refresh states.
- Reduced-motion handling for accessibility.

## Public Demo Changes

To make this project safe for public sharing, production-specific information was removed or replaced with fictional demo values, including:

- Internal service names
- Production hostnames
- Organization-specific identifiers
- Bank and endpoint identifiers
- Dashboard UIDs
- Datasource UIDs
- Internal infrastructure references

The dashboard preview also uses fictional data and generic service names.

## Datasources

This public version uses datasource placeholders that must be replaced after importing the dashboard:

- Zabbix: `REPLACE_ZABBIX_DATASOURCE_UID`
- Elasticsearch: `REPLACE_ELASTICSEARCH_DATASOURCE_UID`

## Files

- `dashboard.sanitized.json` — sanitized Grafana dashboard export for public use
- `screenshots/critical-services-preview.png` — sanitized dashboard preview
