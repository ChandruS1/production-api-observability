🚀 Production API Observability Dashboard

Designed and implemented a production-grade observability system
for monitoring high-volume API traffic integrating multiple
third-party logistics providers.

Features

- P50 / P95 / P99 latency monitoring
- 5xx error rate tracking
- Top 5 busiest APIs
- Top 5 slowest APIs
- Traffic share visualization
- Per-provider latency breakdown
- SLO-focused panels

Tech Stack

- Grafana
- Prometheus
- PromQL
- Histogram-based metrics

Key Concepts Used

- histogram_quantile()
- rate() / increase()
- label_replace()
- topk()
- Percentile-based alerting
- SLO monitoring

Dashboard Preview

Overall Dashboard Overview
![Dashboard Overview 1](screenshots/dashboard_overview_1.png)
![Dashboard Overview 2](screenshots/dashboard_overview_2.png)

---

Error Rate Monitoring
![Error Rate Panel](screenshots/error_rate_panel.png)

---

Percentile Monitoring (P50 / P95 / P99)
![P50 Panel](screenshots/p50_sample_panel.png)
![P95 Panel](screenshots/p95_sample_panel.png)
![P99 Panel](screenshots/p99_sample_panel.png)

---

Alerting Example
![Alerts Overview](screenshots/alerts_overview.png)
![Sample Alert Message](screenshots/alert_sample_msg.png)

> Note: All service names and endpoints have been anonymized for confidentiality.
