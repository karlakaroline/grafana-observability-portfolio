# Veeam Backup Monitoring Dashboard

A Grafana dashboard for backup operations using Prometheus metrics exported from a Veeam collector.

## Dashboard Preview

![Veeam Backup Monitoring Dashboard](screenshots/veeam-backup-preview.png)

## Metrics Used

- `veeam_job_last_result`
- `veeam_job_last_run_timestamp_seconds`
- `veeam_repository_capacity_bytes`
- `veeam_repository_free_bytes`
- `veeam_collector_success`
- `veeam_collector_last_run_timestamp_seconds`
- `veeam_collector_duration_seconds`
- `veeam_job_next_run_timestamp_seconds`
- `veeam_job_state_info`

## Technical Highlights

- Backup job result and current-state visualization.
- Last execution and next scheduled execution tracking.
- Repository capacity and free-space monitoring.
- Collector health, freshness and execution-duration indicators.
- Job filtering and automatic pagination implemented with HTML Graphics JavaScript.
- Responsive dark NOC-style interface designed for operational monitoring.
- Visual separation between healthy, warning, failed and no-data states.
- Dashboard layout optimized for large-screen NOC visualization.

## Public Demo Changes

To make this project safe for public sharing, production-specific information was removed or replaced with fictional demo values, including:

- Organization names and logos
- Backup job names
- Repository names
- Environment-specific identifiers
- Datasource UIDs
- Infrastructure references
- Capacity and operational values shown in the public preview

The dashboard screenshot uses fictional data and generic naming for portfolio purposes.

## Datasource

Prometheus datasource placeholder:

`REPLACE_PROMETHEUS_DATASOURCE_UID`

After importing the dashboard, replace the placeholder with the UID of your own Prometheus datasource.

## Files

- `dashboard.sanitized.json` — sanitized Grafana dashboard export for public use
- `screenshots/veeam-backup-preview.png` — sanitized dashboard preview
