# BatteryReportAnalyzer
Desktop application that parses Windows Battery Report (`.html`) files and visualizes battery health, degradation, usage, and provides useful predictions

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PyQt5](https://img.shields.io/badge/Qt-%23217346.svg?style=for-the-badge&logo=Qt&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

## Key Features

*  **Automated Parsing:** Ingests and parses complex, unstructured battery HTML reports generated by Windows.
*  **Trend Analysis:** Analyzes battery health over time (daily, weekly, monthly, yearly).
*  **Pattern Detection:** Detects usage patterns and correlates them with battery degradation.
*  **Predictive Forecasting:** Predicts future battery health using a linear regression model. 
*  **Visual Insights:** Provides clear, interactive charts, tables, and statistics. 
*  **Hardware Lookup:** Includes a feature to search for battery replacements using model info.


# How to use the program 

 - Download zip file or copy paste the code from here
 - prerequisities
   
        pip install -r requirements.txt in powershell
 
 - To get BatteryReport.html

           powercfg /batteryreport

- Run BatterReportAnalyzer.py
- Upload the BattertReoport.html from the saved Directory
