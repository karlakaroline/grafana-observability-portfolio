# FortiGate Health Monitoring Dashboard

A Grafana dashboard focused on operational health, interface visibility and network traffic monitoring for a Fortinet FortiGate appliance.

## Dashboard Preview

![FortiGate Health Monitoring Dashboard](screenshots/fortigate-preview.png)

## Technical Highlights

- **Zabbix** datasource integration for firewall monitoring.
- Device availability and overall health-state visualization.
- CPU, memory and temperature monitoring.
- Active sessions and session context visibility.
- Physical and logical interface monitoring.
- Uplink and traffic-volume analysis.
- HA synchronization status handling.
- Interface-level throughput and utilization insights.
- Custom **HTML Graphics + JavaScript + CSS** visualization.
- Responsive KPI-based dashboard layout suitable for NOC monitoring.
- Visual distinction between operational, warning and unavailable states.

## Public Demo Changes

To make this project safe for public sharing, production-specific information was removed or replaced with fictional demo values, including:

- Organization names and branding
- Firewall hostname
- Interface names
- Uplink names
- Serial numbers
- Location names
- Datasource UIDs
- Internal infrastructure references

This public version uses generic demo values such as `LAB-FGT-01` and a sanitized dashboard preview image.

## Datasource

Zabbix datasource placeholder:

`REPLACE_ZABBIX_DATASOURCE_UID`

After importing the dashboard, replace the placeholder with the UID of your own Zabbix datasource.

## Files

- `dashboard.sanitized.json` — sanitized Grafana dashboard export for public use
- `screenshots/fortigate-preview.png` — sanitized dashboard preview
