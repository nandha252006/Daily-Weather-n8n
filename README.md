# Daily Weather Email Notification using n8n

## Overview
This project implements an **n8n workflow** that automatically fetches daily weather information from a public weather API and sends it as an **email notification**. The workflow can be triggered on a schedule (daily) or manually for testing purposes.

The goal of this project is to demonstrate workflow automation using n8n, API integration, data transformation, and email notifications in a clean and maintainable way.

---

## Use Case
- Receive daily weather updates via email  
- Automate weather monitoring without manual checks  
- Learn API-based automation using n8n  
- Demonstrate workflow orchestration for portfolio or academic purposes  

---

## Workflow Description


::contentReference[oaicite:0]{index=0}


The workflow consists of the following nodes:

1. **Schedule Trigger**
   - Triggers the workflow automatically at a defined time each day
   - Ensures consistent daily execution

2. **Manual Trigger**
   - Allows the workflow to be executed manually for testing and debugging

3. **HTTP Request**
   - Sends a GET request to a weather API (e.g., Open-Meteo)
   - Retrieves weather data such as temperature, humidity, and conditions

4. **Edit Fields**
   - Extracts and formats required weather information
   - Structures the data into a readable email-friendly format

5. **Send Email**
   - Sends the formatted weather report to the configured email address
   - Acts as the final output of the workflow

---

## Features
- Fully automated daily execution  
- Manual execution support for testing  
- API-driven data retrieval  
- Clean data transformation  
- Email-based notification delivery  

---

## Project Structure
```bash
n8n-weather-email-notification/
│
├── n8n-workflow/
│   ├── 20260109_13h47m40s_grim.png
│   ├── 20260109_13h47m55s_grim.png
│   ├── 20260109_14h15m49s_grim.png
│   ├── 20260109_14h55m44s_grim.png
│   ├── 20260109_14h58m02s_grim.png
│   ├── 20260109_14h59m13s_grim.png
│   ├── 20260109_14h59m38s_grim.png
│   ├── 20260109_15h00m05s_grim.png
│
├── outcome/
│   └── 20260109_15h07m42s_grim.png   # Screenshot of received weather email
│
└── README.md
