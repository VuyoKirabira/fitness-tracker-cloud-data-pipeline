## Fitness-track-cloud-data-pipeline with Free Google Tools
link to YouTube demo - https://youtu.be/nLTLBkiQTI4
This project shows you how I built a full end-to-end cloud BI pipeline using only free Google tools — no subscriptions, no servers, no stress.

## What It Does
Collects data via Google Forms
Stores & cleans it with Google Sheets
Automates processing with Google Apps Script
Visualizes insights through Looker Studio (insights update every 15mins)
Publishes dashboards on Google Sites

This system is fully automated, making it perfect for lean teams or solo analysts.

## Tools & Tech Stack
Google Forms	Front-end data collection
Google Apps Script	Automation, everytime there is a new submission it gets appended to the spreadsheet
Google Sheets	Storage and data cleaning using formula logic like arrayformula to clean data as soon as it gets appended into the sheet from the form. 
Looker Studio	Near real-time dashboards and analytics
Google Sites UI.

## Different use cases
Business surveys & feedback forms
Internal KPI tracking
Customer satisfaction dashboards
Personal metrics (fitness, habits, etc.)
Education & student progress reporting

The pipeline was originally built for my running data, but the same logic applies to most structured feedback or data entry forms.

## Auto-Refresh
The pipeline auto-updates every 15 minutes using Google Apps Script, so your dashboards stay fresh—without manual updates.
