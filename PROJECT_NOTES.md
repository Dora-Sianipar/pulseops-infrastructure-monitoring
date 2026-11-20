# PulseOps Project Notes

## Objective
Build a portfolio-ready operations dashboard that communicates practical IT Operations, Cloud, DevOps, and monitoring concepts through an interactive simulation.

## Demo data
Eight services are preloaded. One service is marked down and one degraded to demonstrate service health distribution and incident visibility. This is fictional sample data.

## Incident lifecycle
- Open: incident is reported and requires action.
- Acknowledged: an operator has taken ownership.
- Resolved: the issue is marked resolved; a simulated down service is restored.

## Metrics
- Availability percentage: sample KPI, not calculated from actual infrastructure.
- Response time: sample latency data.
- CPU / Memory: sample utilization values.
- Uptime: fictional demo values.

## Known limitations
- No actual server checks or external integrations.
- Metrics and chart data are simulated.
- Alert rules are demonstration-only.
- Data is stored in LocalStorage on the current browser.
- No authentication or authorization.

## Demo scenarios
1. Trigger a simulated incident from the sidebar.
2. Acknowledge the incident from the Incidents page.
3. Resolve the incident.
4. Observe service health and dashboard metrics update.
5. Export a JSON report.
