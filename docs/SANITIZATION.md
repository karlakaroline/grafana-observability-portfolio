# Sanitization performed

The public copies were generated from private working dashboards. The originals were left unchanged.

The sanitization process removes or replaces:

- organization/customer branding and logos;
- internal hostnames, application/service names and data-center references;
- IP addresses, MAC addresses and device serial numbers;
- private tenant URLs, project-specific filters and internal API references;
- embedded authentication headers and credential material;
- Grafana datasource UIDs and dashboard IDs/UIDs;
- embedded organization-specific font/logo assets;
- internal drill-down/dashboard identifiers where found.

## Credential safety

Public dashboard exports must not contain passwords, API tokens, authentication headers, cookies or other credential material.

If credential material is ever discovered in an exported dashboard, remove it from the public copy and revoke or rotate the credential at its provider.

## What was intentionally preserved

The public copies retain the technical structure where possible: Grafana panel configuration, HTML Graphics/CSS/JavaScript logic, generic integration metric names, threshold/state handling and the overall dashboard design.
