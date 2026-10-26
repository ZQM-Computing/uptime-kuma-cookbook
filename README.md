# Uptime Kuma Cookbook

<!-- ZQM-START -->
<!-- markdownlint-disable MD033 -->
<p align="center">
  <strong>ZQM Computing — Geospatial Engineering & Scientific Computing</strong><br>
  <a href="https://github.com/ZQM-Computing">ZQM Computing</a>
</p>
<!-- markdownlint-enable MD033 -->
<!-- ZQM-END -->

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A **Uptime Kuma cookbook** — uptime monitoring with status pages and notifications. Queued in wave-11 (Node-3 hub set). Patterns are planned from the design, not yet from fleet runs. It is intended for Engineers who monitor services and publish status pages. Validate each pattern against your own data, software versions, and operating environment before adopting it.

## Repository role and status

**Status:** Active, public — seeding. Pattern passes land in follow-up work from fleet-verified setups; the tables below list what is planned, not what is already written.

**What this repository is:** Uptime Kuma patterns — see the table below.

**What it contributes:** Part of the ZQM Computing geospatial portfolio. The umbrella index for the series is [geospatial-cookbooks](https://github.com/ZQM-Computing/geospatial-cookbooks).

**Standing:** This repository is maintained independently. Automated checks cover only the paths and environments configured in its workflows; they do not establish production readiness or operational certification.

## Who this is for

Engineers who monitor services and publish status pages.

## Prerequisites

- Uptime Kuma via Docker
- Services to monitor
- A notification channel for the alert pass

## Patterns (planned)

| # | Example | What it will demonstrate |
|---|---------|--------------------------|
| 01 | `01-first-monitor` | HTTP, TCP, and keyword monitors |
| 02 | `02-status-page` | Publishing a public status page |
| 03 | `03-notifications` | Notification channels and alert routing |
| 04 | `04-api-notes` | Driving monitors through the API |

## Repository layout

```text
uptime-kuma-cookbook/
├── examples/          # pattern passes, landing in follow-up work
├── README.md
└── LICENSE
```

## Roadmap

- First pattern pass: the first two table rows
- Second pass: the remaining rows, from fleet-verified setups

## Contributing

A contributing guide lands with the first pattern pass. Report security issues to <zqmcomputing@gmail.com> — please do not open a public issue for those.

## More from this series

- [grafana-cookbook](https://github.com/ZQM-Computing/grafana-cookbook) — Dashboards, datasources, and alerts for geospatial stacks
- [prometheus-cookbook](https://github.com/ZQM-Computing/prometheus-cookbook) — Metrics, scrape jobs, PromQL, and alert rules
- [portainer-cookbook](https://github.com/ZQM-Computing/portainer-cookbook) — Container management with an API and UI
