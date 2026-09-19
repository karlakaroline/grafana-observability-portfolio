# Security Guidelines

This repository is intended for **public demonstration only**.

- Do not store Grafana, Zabbix, Prometheus, Elasticsearch or third-party credentials in dashboard JSON.
- Configure authentication in the Grafana datasource, a secure proxy or a secret-management layer instead of embedding authentication headers in panel queries.
- Use fictional hostnames, IP addresses, MAC addresses, serial numbers, project identifiers and application names.
- Review exported JSON before every public commit because Grafana exports can include datasource UIDs, URLs and plugin configuration.
- Screenshots should be reviewed separately for hostnames, usernames, ticket IDs, IP addresses, internal names and organization branding.

If a credential is ever exposed in a public commit, removing it from Git history is not sufficient: revoke or rotate it at the provider.
