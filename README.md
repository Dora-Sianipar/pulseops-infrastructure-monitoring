# PulseOps — Infrastructure Monitoring & Incident Response Platform

PulseOps is a polished, browser-based infrastructure operations dashboard built as a portfolio project. It simulates the workflow of monitoring services, reviewing alerts, managing incidents, and keeping an operational activity trail.

> **Important:** This is a front-end simulation for learning and portfolio demonstration. It does not connect to real servers, cloud infrastructure, monitoring agents, or alerting systems.

## Features

- **Operations overview:** availability, incident count, response-time KPI, service health.
- **Performance chart:** switch between response time, CPU utilization, and memory metrics.
- **Service inventory:** service type, health, response time, CPU, memory, and uptime.
- **Search and filtering:** find services and filter by health status.
- **Incident management:** create, acknowledge, and resolve incidents.
- **Incident simulation:** trigger a simulated service outage and automatically create an incident.
- **Alert rule view:** example threshold rules for CPU, memory, health checks, and response time.
- **Activity log:** operator actions are recorded.
- **Report export:** export the current demo state as JSON.
- **Persistent demo data:** changes persist in browser `localStorage`.
- **Responsive layout:** desktop, tablet, and mobile-friendly navigation.
- **Dark/light mode:** switch themes.

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Canvas API for chart visualization
- LocalStorage for demo persistence

## Run Locally

No installation is required.

1. Download or clone this repository.
2. Open `index.html` in a browser.
3. Use the sidebar to explore Overview, Services, Incidents, Alert Rules, and Activity Log.
4. Use **Simulate incident** to trigger a demo outage.
5. Acknowledge or resolve the incident in the Incidents page.
6. Use **Export report** to download a JSON snapshot.

## Project Structure

```text
PulseOps/
├── index.html
├── styles.css
├── app.js
└── README.md
```

## Suggested Demo Walkthrough

1. Start on the Overview page and explain the four KPIs.
2. Show the performance chart and change its metric.
3. Open Services and explain health status, response time, CPU, memory, and uptime.
4. Click **Simulate incident** to trigger a service outage.
5. Open Incidents and acknowledge the new incident.
6. Resolve the incident and show how the service status returns to healthy.
7. Open Activity Log to review the operational audit trail.
8. Export the report to JSON.

## Skills Demonstrated

- Building operational dashboards and data visualization
- Monitoring concepts and service health indicators
- Incident lifecycle: open → acknowledged → resolved
- Basic troubleshooting workflow
- State persistence with LocalStorage
- UI filtering and search
- Responsive interface design
- JSON report export

## Future Improvements

Potential next steps for a production-style version:

- Flask or Node.js backend API
- PostgreSQL database
- Authentication and role-based access control
- Real metrics collection via Prometheus
- Grafana dashboards
- WebSocket-based live updates
- Docker Compose deployment
- CI/CD workflow with GitHub Actions
- Unit and integration tests

## Portfolio Summary

**PulseOps — Infrastructure Monitoring & Incident Response Dashboard**

Designed and developed a responsive operations dashboard that simulates infrastructure monitoring and incident management workflows. Implemented service health tracking, performance visualization, alert-rule display, incident creation/acknowledgment/resolution, activity logging, and JSON report export using HTML, CSS, and JavaScript.

---
Created as a learning and portfolio project.
