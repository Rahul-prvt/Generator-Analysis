This repository contains a Power BI project that analyzes critical power infrastructure metrics, including generator activity, fuel consumption, grid supply stability, and battery health. The analysis identifies system behaviors, anomalies, and vulnerabilities during critical event windows, and provides actionable recommendations to enhance facility resilience and operational efficiency.

Features
Fuel Consumption Analysis:
Detects and visualizes sudden changes and anomalies in fuel levels.

Generator Monitoring:
Tracks generator activity and identifies alignment with fuel usage patterns.

Grid Supply Insights:
Monitors grid voltage stability and flags outages or disconnections.

Battery Performance Tracking:
Assesses battery voltage trends and backup capacity during interruptions.

Event Timeline Correlation:
Correlates system instabilities during outage windows for root-cause analysis.

Key Insights
Unexplained fuel drop observed without corresponding generator activity.

Generator mostly inactive except for brief test/startup spikes.

Grid supply is stable, then abruptly lost, aligning with battery discharge.

Battery backup may be insufficient during prolonged grid outages.

Critical outage window highlights backup system vulnerabilities.

Recommendations
Investigate possible fuel leakage, theft, or sensor malfunction.

Verify and maintain generator auto-start and response mechanisms.

Check battery health and consider increasing backup capacity.

Set up proactive grid outage alerts and improve monitoring.

Usage
Clone the Repository


git clone https://github.com/yourusername/powerbi-generator-fuel-analysis.git
Prepare Data

Place your raw data files in the /data directory.

Ensure the data structure matches the requirements in the Power BI report.

Open Power BI Report

Open PowerBI_Project_Report.pbix in Power BI Desktop.

Refresh data, customize visuals, and update as per your needs.

Folder Structure
├── data/
│   └── [Raw and sample data files]
├── PowerBI_Project_Report.pbix
├── report/
│   └── PowerBI_Analysis_Report.pdf
├── README.md
Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss proposed enhancements or bug fixes.

License
MIT# Generator-Analysis
