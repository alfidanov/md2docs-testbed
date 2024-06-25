---
title: Markdown Table
---

# Tables Use Cases

 ## Tables with hyphens and pipes

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Table Alignment

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

## Advanced Table Example

| Alert Name | Threshold | -> Status | Alert Level | Triggered When |
|-------|---------------------|---|---|---|
| AGENT_CONNECTIVITY   | N/A | Degraded | CRITICAL | The Agent VM lost connectivity to the control plane. |
| CLOUDSTORAGE   | N/A | Degraded | CRITICAL | The Agent VM is not able to connect to the Cloud Storage Repo. |
| DATA_DISK_HEALTH_ALERT   | >= 90% | Degraded | CRITICAL | The data disk on the Agent VM has reached 90% capacity. |
| DATA_DISK_HEALTH_ALERT   | >= 70% | Warning | WARNING | The data disk on the Agent VM has reached 70% capacity.|
| INFLUXDB   | N/A | Degraded | CRITICAL | The Influxdb service running in the Agent VM is down. |
| KAPACITOR   | N/A | Degraded | CRITICAL | The Kapacitor service running in the Agent VM is down. |
| LOCALSTORAGE   | N/A | Degraded | CRITICAL | The Agent VM is not able to connect to the Local Storage Repo. |
| MONITORING   | N/A | Degraded | CRITICAL | The monitoring service running in the Agent VM is down. |
| ONBOARDING   | N/A | Warning | CRITICAL | The onboarding service running in the Agent VM is down. |
| RCLONE   | N/A | Degraded | CRITICAL | The rclone service running in the Agent VM is down. |
| SYSTEM_DISK_HEALTH_ALERT   | >= 90% | Degraded | CRITICAL | The system disk on the Agent VM has reached 90% capacity. |
| SYSTEM_DISK_HEALTH_ALERT   | >= 70% | Warning | WARNING | The system disk on the Agent VM has reached 70% capacity. |
| TELEGRAF   | N/A | Degraded | CRITICAL | The Telegraf service running in the Agent VM is down. |
| VCENTER   | N/A | Degraded | CRITICAL | Data Management for VMware Tanzu is unable to connect to vCenter. |