# NOC Ticket Queue Overview

A Grafana NOC operations dashboard combining monitoring information from Zabbix with service-management queues from Jira.

## Technical highlights

- Mixed Grafana datasource model.
- Zabbix event/problem streams.
- Jira REST search through an Infinity datasource.
- Operational queue summaries and ticket lists.
- Custom HTML Graphics/CSS/JavaScript presentation.

## Security note

The private source export contained an embedded Jira `Authorization` header. **The public JSON removes it entirely.** Configure Jira authentication in a secure datasource/proxy configuration instead.

The demo also replaces the Jira tenant, project-specific JQL and customer branding.

## Datasources

- Zabbix: `REPLACE_ZABBIX_DATASOURCE_UID`
- Infinity: `REPLACE_INFINITY_DATASOURCE_UID`
