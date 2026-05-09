# Website Uptime Monitor & Alert System

An automated workflow that monitors website availability and sends real-time email alerts on downtime detection, built with n8n.

---

## How it Works

    Schedule Trigger → HTTP Request → IF Condition → Gmail Alert

1. Schedule trigger runs every 5 minutes
2. HTTP request checks if the target website is reachable
3. IF condition evaluates the HTTP status code
4. Gmail node sends an alert email if the site is down

---

## Tech Stack

`n8n` `HTTP Request Node` `Gmail API (OAuth2)` `Docker`

---

## Features

- Automated uptime checks on a configurable schedule
- Real-time email alerts on failure
- Easily extendable to monitor multiple websites

---

## Setup

1. Install and run n8n locally or via Docker
2. Import the workflow JSON into your n8n instance
3. Configure the target URL and Gmail OAuth2 credentials
4. Activate the workflow
