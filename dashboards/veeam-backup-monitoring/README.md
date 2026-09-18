# Veeam Backup Monitoring Dashboard

Grafana dashboard for backup operations using Prometheus metrics exported from a Veeam collector.

## Metrics used

- `veeam_job_last_result`
- `veeam_job_last_run_timestamp_seconds`
- `veeam_repository_capacity_bytes`
- `veeam_repository_free_bytes`
- `veeam_collector_success`
- `veeam_collector_last_run_timestamp_seconds`
- `veeam_collector_duration_seconds`
- `veeam_job_next_run_timestamp_seconds`
- `veeam_job_state_info`

## Technical highlights

- Backup-job result and state visualization.
- Last and next execution time.
- Repository capacity/free-space monitoring.
- Collector health and freshness indicators.
- Filtering/pagination logic implemented in HTML Graphics JavaScript.
- Responsive dark NOC-style interface.

## Datasource

`REPLACE_PROMETHEUS_DATASOURCE_UID`
