# VPC Networks – Controlling Access (GSP213)

## Objective
To understand how to control network access in Google Cloud using VPC networks, firewall rules, network tags, and IAM service accounts. The lab demonstrates securing web servers and managing permissions.

## Key Steps Performed

### 1. Created Web Servers
- Created two VM instances:
  - blue server (with network tag: web-server)
  - green server (without tag)
- Installed nginx-light on both servers
- Customized default web pages:
  - Blue server → “Welcome to the blue server!”
  - Green server → “Welcome to the green server!”

### 2. Created Firewall Rule
- Created firewall rule:
  - Name: allow-http-web-server
  - Target tag: web-server
  - Protocol: TCP port 80 (HTTP)
  - Source IP: 0.0.0.0/0
- Verified HTTP access behavior:
  - Blue server accessible externally
  - Green server not accessible externally

### 3. Created Test VM
- Created VM instance: test-vm using gcloud CLI
- Used it to test internal and external connectivity

### 4. Tested Connectivity
- Used curl to test:
  - Internal IP access (blue & green) → SUCCESS
  - External IP access:
    - Blue → SUCCESS
    - Green → FAILED (expected)

### 5. IAM & Service Accounts
- Created service account: Network-admin
- Assigned role: Compute Network Admin
- Downloaded credentials.json key file
- Activated service account on test-vm

### 6. Role Testing
- Network Admin role:
  - Can list firewall rules
  - Cannot delete firewall rules
- Upgraded to Security Admin role:
  - Can delete firewall rules
  - Verified deletion removed external HTTP access

## Tools / Services Used
- Google Compute Engine
- VPC Network
- Firewall Rules
- Network Tags
- IAM Service Accounts
- gcloud CLI
- Cloud Shell
- nginx-light
- curl

## Results
Successfully implemented network-level security using firewall rules and tags. Demonstrated role-based access control using IAM service accounts and verified differences between Network Admin and Security Admin permissions.
