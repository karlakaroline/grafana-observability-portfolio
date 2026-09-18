# Sanitization performed

The public copies were generated from private working dashboards. The originals were left unchanged.

The sanitization process removes or replaces:

- organization/customer branding and logos;
- internal hostnames, application/service names and data-center references;
- IP addresses, MAC addresses and device serial numbers;
- Jira tenant URLs and project-specific JQL;
- embedded authorization headers and credential material;
- Grafana datasource UIDs and dashboard IDs/UIDs;
- embedded organization-specific font/logo assets;
- internal drill-down/dashboard identifiers where found.

## Important credential note

One source dashboard contained a Jira `Authorization` header embedded in the exported JSON. The public copy removes that header. The source credential should still be revoked/rotated because it existed in plaintext-equivalent exported configuration.

## What was intentionally preserved

The public copies retain the technical structure where possible: Grafana panel configuration, HTML Graphics/CSS/JavaScript logic, metric names that are generic to the integration, threshold/state handling and the overall dashboard design.
