# Uptime Monitoring & Alert System (n8n)

## Overview
This project is a simple but powerful automation system built using n8n that monitors website availability and sends real-time alerts when a failure is detected.

It simulates a basic DevOps monitoring pipeline used in real-world production systems.

---

## How it works
The workflow runs on a schedule and performs the following steps:

1. Schedule Trigger runs every 5 minutes  
2. HTTP Request checks if the target website is reachable  
3. IF condition verifies HTTP status code  
4. Gmail node sends alert email if the site is down  

---

## Tech Stack
- n8n (Workflow Automation)
- HTTP Request Node
- Gmail API (OAuth2)
- Docker (for local deployment)

---

## Workflow Architecture
Schedule Trigger → HTTP Request → IF Condition → Email Alert

---

## Features
- Automated uptime monitoring
- Real-time email alerts on failure
- Fully no-code workflow automation
- Easily extendable to multiple websites
- Beginner-friendly DevOps simulation project

---

## Future Improvements
- Multi-website monitoring
- Telegram/Discord alerts
- Response time tracking
- Logging system for failures
- Cloud deployment (AWS/DigitalOcean)

---

Built as a learning project exploring DevOps automation and workflow engineering using n8n.
