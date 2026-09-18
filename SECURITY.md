# Security Guidelines

This repository is intended for **public demonstration only**.

- Do not store Jira, Grafana, Zabbix, Prometheus or Elasticsearch credentials in dashboard JSON.
- Configure authentication in the Grafana datasource or a secret-management layer instead of embedding `Authorization` headers in a panel query.
- Use fictional hostnames, IP addresses, MAC addresses, serial numbers, project keys and application names.
- Review exported JSON before every public commit because Grafana exports can include datasource UIDs, URLs and plugin configuration.
- Screenshots should be reviewed separately for hostnames, usernames, ticket IDs, IP addresses and customer branding.

If a credential was ever committed publicly, removing it from Git history is not sufficient: revoke/rotate it at the provider.
