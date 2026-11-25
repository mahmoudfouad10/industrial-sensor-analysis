# Industrial Sensor Data Analysis - Power BI

An interactive Power BI dashboard analyzing industrial sensor readings with Pass/Fail quality outcomes.

## Pages

**Operations Overview**
- KPI cards: Total Records, Total Pass, Total Fail, Pass Rate %
- Pass/Fail split donut (50% / 50% in this dataset)
- Average sensor readings by status (Temperature, Pressure, Vibration, Sensor_A)
- Status slicer for filtering the whole page

**Sensor Deep Analysis**
- Average and maximum cards for all four sensor readings, with warning flags on the max cards
- Average temperature by status
- Temperature x Vibration scatter colored by status: Fail records cluster at higher temperature and vibration readings, Pass records at lower ones - the separation is directly visible in the chart
- Status slicer

## Tools

- Power BI Desktop
- DAX measures: Total Records, Total Pass, Total Fail, Pass Rate %, and Average/Maximum for Temperature, Pressure, Vibration, and Sensor_A
