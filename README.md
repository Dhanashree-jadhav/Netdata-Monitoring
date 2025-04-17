# Netdata-Monitoring
# Monitor System Resources Using Netdata

## Objective
Install Netdata using Docker and visualize system and app performance metrics.

## Steps
1. Installed Docker and verified with `docker --version` (Version 28.0.4).
2. Ran Netdata container with: `docker run -d --name=netdata -p 19999:19999 netdata/netdata`.
3. Accessed dashboard at `http://localhost:19999` and explored CPU, memory, disk, and network metrics.
4. Zoomed into charts to analyze trends (e.g., CPU spikes).
5. Checked alerts (0 active) and reviewed logs with `docker logs netdata`.

## Deliverables
- Screenshot: `netdata_dashboard.png` shows zoomed metrics and dashboard.
- Logs: Reviewed via `docker logs netdata` (no errors observed).

## Outcome
Gained hands-on experience with Netdata for lightweight system monitoring.
