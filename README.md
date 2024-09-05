# newyork-bikes-aggregation-pipeline
An automated serverless data engineering pipeline that ingests NewYork city bikes data for each borough into an ETL (Extract Transform Load) workflow using AWS cloud services, followed by data visualization in Grafana.

# Aim
To populate the city bikes data in New York for each borough, aggregate them and visualize them on a Dashboard


# Data Source

https://data.cityofnewyork.us/Transportation/Bicycle-Parking/592z-n7dk/about_data
The data contains locations of all bike parking throughout the five boroughs as of the date of publication. The data is in shapefile format.

# What is in this Data set?


![image](https://github.com/user-attachments/assets/76f130fc-2c87-4c30-b35a-c26c1c3fb64f)



# Architecture Diagram
![NewYork_City_Bikes_Architecture](https://github.com/user-attachments/assets/cd1f680a-7cd7-48c7-bd92-b6cf2f5b8db6)

# Tech Stack
AWS Cloud Services
1. AWS Lambda
2. AWS EventBridge
3. AWS Glue
4. AWS Cloudwatch
5. AWS Athena
6. Grafana


# Data Visualization
https://gayathrig269.grafana.net/d/edwby32vlyl1cd/new-york-bikes-data?viewPanel=panel-1&from=2024-09-04T17:20:02.252Z&to=2024-09-04T23:20:02.253Z

