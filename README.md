# Grafana Observability Portfolio

Portfolio of Grafana dashboards focused on infrastructure monitoring, NOC operations, backup observability and network/security visibility.

> **Public demo repository:** all organization-specific names, hostnames, IP addresses, dashboard/datasource UIDs, logos, internal application names and authentication material were removed or replaced with fictional values before publication.

## Projects

| Dashboard | Main technologies | What it demonstrates |
|---|---|---|
| [Critical Services Observability](dashboards/critical-services-observability/) | Grafana, Zabbix, Elasticsearch/APM, HTML Graphics | Multi-source service-health logic, partial-data handling, state mapping, custom UI, drill-down patterns |
| [FortiGate Monitoring](dashboards/fortigate-monitoring/) | Grafana, Zabbix, FortiGate | Firewall health, HA status, CPU/memory/temperature, sessions, interfaces and traffic |
| [Veeam Backup Monitoring](dashboards/veeam-backup-monitoring/) | Grafana, Prometheus, Veeam | Backup job status, next/last run, repository capacity and collector health |
| [Palo Alto Monitoring](dashboards/palo-alto-monitoring/) | Grafana, Zabbix, Palo Alto Networks | Firewall availability, resource health, interface state, throughput and custom visualization |
| [NOC Ticket Queue](dashboards/noc-ticket-queue/) | Grafana, Zabbix, Jira, Infinity | Unified operational view of monitoring events and service-management queues |

## Repository structure

```text
grafana-observability-portfolio/
├── README.md
├── SECURITY.md
├── docs/
│   ├── IMPORTING.md
│   └── SANITIZATION.md
└── dashboards/
    ├── critical-services-observability/
    ├── fortigate-monitoring/
    ├── veeam-backup-monitoring/
    ├── palo-alto-monitoring/
    └── noc-ticket-queue/
```

## Import notes

The JSON files intentionally use placeholder datasource UIDs such as `REPLACE_ZABBIX_DATASOURCE_UID`. After importing a dashboard, map or replace those placeholders with the datasource UIDs from your own Grafana environment.

## Security

Never commit credentials, API tokens, cookies, private URLs, production hostnames or customer identifiers. See [SECURITY.md](SECURITY.md) and [docs/SANITIZATION.md](docs/SANITIZATION.md).

## Author

**Karla Karoline**  
IT Support Analyst | NOC | Infrastructure | Monitoring & Observability
