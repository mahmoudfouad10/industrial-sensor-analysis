<p align="center">
  <img src="https://github.com/mahmoudfouad10/industrial-sensor-analysis/releases/download/v1.0/logo.png" alt="Mahmoud Fouad" width="140">
</p>

# Industrial Sensor Data Analysis - Power BI

An interactive Power BI dashboard analyzing industrial sensor readings with Pass/Fail quality outcomes.

## Pages

**Operations Overview**
![Operations Overview](https://github.com/mahmoudfouad10/industrial-sensor-analysis/releases/download/v1.0/overview.jpg)

- KPI cards: Total Records, Total Pass, Total Fail, Pass Rate %
- Pass/Fail split donut (50% / 50% in this dataset)
- Average sensor readings by status (Temperature, Pressure, Vibration, Sensor_A)
- Status slicer for filtering the whole page

**Sensor Deep Analysis**
![Sensor Deep Analysis](https://github.com/mahmoudfouad10/industrial-sensor-analysis/releases/download/v1.0/deep-analysis.jpg)

- Average and maximum cards for all four sensor readings, with warning flags on the max cards
- Average temperature by status
- Temperature x Vibration scatter colored by status: Fail records cluster at higher temperature and vibration readings, Pass records at lower ones - the separation is directly visible in the chart
- Status slicer

## Tools

- Power BI Desktop
- DAX measures: Total Records, Total Pass, Total Fail, Pass Rate %, and Average/Maximum for Temperature, Pressure, Vibration, and Sensor_A

## Files

Download from the [v1.0 release](https://github.com/mahmoudfouad10/industrial-sensor-analysis/releases/tag/v1.0):

- [`report.pbix`](https://github.com/mahmoudfouad10/industrial-sensor-analysis/releases/download/v1.0/report.pbix) - the full Power BI report (open with Power BI Desktop)
- Page captures of Operations Overview and Sensor Deep Analysis (shown above)
