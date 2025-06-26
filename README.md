# Traffic Analysis for City Planning

## Overview
This project analyzes hourly traffic volume data from `traffic.csv` to support urban planning and route optimization. Covering traffic data across four junctions from November 2015 to June 2017, the script generates visualizations and reports to identify peak traffic hours, daily trends, and actionable recommendations for traffic management.

## Dataset
- **File**: `traffic.csv`
- **Columns**:
  - `DateTime`: Hourly timestamp (e.g., 2015-11-01 00:00:00)
  - `Junction`: Junction ID (1, 2, 3, 4)
  - `Vehicles`: Number of vehicles per hour
  - `ID`: Unique record identifier
- **Time Range**: November 2015–June 2017
- **Note**: Place `traffic.csv` in the `/content/` directory for Google Colab or update the file path in `traffic_analysis.py`.

## Requirements
- **Python**: 3.8 or higher
- **Dependencies**:
  ```bash
  pip install pandas matplotlib seaborn ipython
