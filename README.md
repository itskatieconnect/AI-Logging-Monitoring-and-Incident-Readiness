# AI Logging, Monitoring & Incident Readiness with Splunk

This project demonstrates how to monitor an AI-powered API using Splunk in a SOC-style environment.

## Tools
- FastAPI
- Ubuntu Linux
- Splunk Enterprise
- Splunk Universal Forwarder

  Ubuntu VM
 ├── FastAPI AI Application
    └── Logs: ai_app.log
 ├── Splunk Universal Forwarder
      └── Monitors ai_app.log
 ↓
Splunk Enterprise
 ├── Custom Index: ai_security
 ├── Field Extractions
 ├── Searches & Reports
 └── Security Dashboard


## What This Project Covers
- Structured AI application logging
- Log forwarding into Splunk
- Field extraction for security analysis
- Detection logic using SPL
- Monitoring dashboards
- Incident readiness workflows

## Key Learning
Low-volume environments may not trigger detections immediately. This project shows how to validate detection logic and rely on dashboards for visibility.

## Architecture
FastAPI → Log File → Splunk Forwarder → Splunk Enterprise


