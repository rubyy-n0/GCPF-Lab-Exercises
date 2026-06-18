# Cloud Monitoring: Qwik Start (GSP089)

## Objective
To learn how to monitor a Google Compute Engine virtual machine using Cloud Monitoring and Cloud Logging, and to configure uptime checks, alerting policies, and dashboards.

## Key Steps Performed
1. Created a Compute Engine VM instance named **lamp-1-vm**.
2. Configured machine type (e2-medium) and enabled HTTP firewall rule.
3. Installed Apache2 web server and PHP on the VM.
4. Accessed the Apache default webpage using external IP.
5. Set up Cloud Monitoring metrics scope for the project.
6. Installed Cloud Ops Agent (Monitoring + Logging agent) on the VM.
7. Verified agent installation using systemctl status.
8. Created an uptime check for the VM using HTTP protocol.
9. Created an alerting policy for network traffic (VM instance interface).
10. Created a custom dashboard with:
    - CPU Load chart
    - Received Packets chart
11. Viewed logs using Cloud Logging (Logs Explorer).
12. Stopped and restarted the VM to observe log changes.
13. Verified uptime check status and alert incidents.

## Tools / Services Used
- Google Compute Engine
- Cloud Monitoring
- Cloud Logging
- Cloud Ops Agent
- Apache2 Web Server
- gcloud CLI
- Cloud Console Dashboards
- Alerting Policies
- Uptime Checks

## Results
Successfully monitored a VM instance using Google Cloud Monitoring. Configured dashboards, alerting policies, and uptime checks. Verified system logs and observed VM lifecycle events through Cloud Logging.
