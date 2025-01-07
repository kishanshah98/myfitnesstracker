# Running Performance Tracking and Analysis

## Project Overview
This project analyzes personal running performance using historical data logged on Strava. By leveraging statistical calculations, visualizations, and time series analysis in Microsoft Excel, it aims to uncover trends in running distance, pace, and duration over days, weeks, and months. External factors such as weather and time of day are also considered to provide deeper insights into running performance.

<img src="images/image1.jpg" alt="Aesthetic Picture" width="400">

---

## Data Summary
The dataset tracks several metrics from runs over the past few months. Key columns include:

- **Date**
- **Distance (in miles)**
- **Cumulative Miles Completed**
- **Duration (in minutes)**
- **Cumulative Time Ran (in minutes)**
- **Average Pace (minutes per mile)**
- **Weather**
- **Time of Day**

![Sample Data Screenshot](https://prod-files-secure.s3.us-west-2.amazonaws.com/a5896cf7-e3d0-41ee-9de5-8a038eaa3ec7/a1243e4e-0472-4626-bfa1-91a83df6ec55/Screenshot_2024-09-23_at_12.11.07_PM.png)

---

## Exploratory Data Analysis

### **Statistics**
Using Excel formulas like `AVERAGE`, `SUM`, `STDEV.S`, and `MEDIAN`, basic statistics were calculated for metrics like distance, pace, and duration. These calculations provide a quantitative view of performance over time.

### **Data Visualizations**
Key trends and patterns were visualized through graphs, including:

- **Distance Over Time**
- **Cumulative Miles Ran**
- **Average Pace Over Time**
- **Time of Day Analysis**
- **Weather-Based Performance Trends**

![Graph Example](https://prod-files-secure.s3.us-west-2.amazonaws.com/a5896cf7-e3d0-41ee-9de5-8a038eaa3ec7/2976991a-bfbd-465f-a784-346bd8e6b5da/4fd68b5c-342c-4a4b-9d89-9b691cda5a28.png)

---

## Key Insights

### **Time of Day Analysis**
- **Morning Runs** showed the fastest average pace (10.67 min/mile), outperforming afternoon and evening runs.
- Distance remained consistent across times of the day, indicating the time of day impacts pace more than distance.

### **Weather Analysis**
- Runs on **cloudy days** were both longer and faster than on sunny days, suggesting cooler conditions positively influence performance.
- July showed the most significant difference, with a pace of 10.37 min/mile on cloudy days compared to 11.40 min/mile on sunny days.

![Weather Pivot Table](https://prod-files-secure.s3.us-west-2.amazonaws.com/a5896cf7-e3d0-41ee-9de5-8a038eaa3ec7/70727f8a-4491-4504-b874-2028816415c1/Screenshot_2024-09-23_at_1.36.02_PM.png)

---

## Future Work
- **Continuous Updates**: The dataset will be updated regularly to track progress throughout the next year.
- **Advanced Analysis**: Incorporate time series analysis for predictive modeling and deeper performance insights.
- **Automation**: Use Excel VBA for dynamic performance alerts, monthly summaries, and custom data entry forms.

Stay tuned for more updates as this journey progresses!
