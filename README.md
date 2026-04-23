# Analyzing Suricata Alerts for Network Security Threats

## Overview
This project focuses on analyzing a dataset of Suricata IDS alerts (AIT-ADS) to identify potential security threats, understand attack patterns, and apply data science techniques to network security logs. 

## Datasets Analyzed
The project utilizes real Suricata alerts in JSON format, specifically focusing on:
1. **AMiner Logs** (~55,000+ records)
2. **Wazuh Logs** (~698,000+ records)

## Key Objectives & Tasks
- **Data Parsing & Preprocessing:** Extracted and flattened complex, large-scale JSON log data into structured Pandas DataFrames.
- **Alert Analysis:** Analyzed top attack signatures, severity distributions, and timestamp patterns to identify network anomalies.
- **Data Visualization:** Built informative charts using Matplotlib and Seaborn to visualize alerts by hour of the day and severity proxies.
- **SOC Dashboard Concept:** Proposed a conceptual Analyst Workflow and clustering strategy to group incidents, handle low-severity alerts automatically, and prioritize deeper reviews.

## Technologies Used
- Python (Pandas, NumPy, Regex)
- JSON Data Handling
- Matplotlib & Seaborn (Data Visualization)
