Connect the Dots with  Data Engineering Project

Project Overview :
This project involves the design and implementation of a data analytics platform for ingesting, transforming, and analysing Network Rail movement data in the UK. The objective is to enable the railway company to monitor performance, detect bottlenecks, and make data-driven operational decisions.


 "Data collection, storage, and transformation, leading to the use of the obtained data to solve various problems."


<img width="2172" height="930" alt="image" src="https://github.com/user-attachments/assets/41b3925c-7551-4bc9-8cfd-f9a790d4a25a" />

Objectives
•	✅ Ingest & parse raw Network Rail movement and schedule data
•	✅ Clean, standardize, and join data sources
•	✅ Build analytical models to:
o	Track train punctuality
o	Measure delay propagation
o	Identify underperforming routes/stations
•	✅ Enable easy reporting and dashboarding for business users

Work to do in Project
● Develop data pipelines for Network Rail movement data 
● Apply analytics engineering on the dataset (DBT)
● Build data models to answer business questions 
● Create a dashboard (Looker studio)

Network Rail Data Questions?
●Which train has the highest number of off route records? 
● Which operating company has the highest number of on time/late trains? 
● Which train has never been late and off route? 
● Which hour of each day has the highest number of late trains?

Dataset Raw  data : https://datafeeds.networkrail.co.uk

<img width="398" height="611" alt="image" src="https://github.com/user-attachments/assets/d0b3824f-d80c-4efd-ad13-8ba33638d3ce" />


Data Models & Diagrams
1. Data Pipeline Architecture
Stages:
•	Ingestion: Fetch raw movement/schedule data
•	Staging: Parse & normalize formats
•	Transform: Join and clean datasets
•	Modeling: Create fact tables and metrics
•	Reporting: Expose to BI tools or dashboards
________________________________________
2. Entity-Relationship Diagram
Core Tables:
•	stg_trust_data: Cleaned TRUST events
•	stg_cif_schedule: Parsed CIF schedule entries
•	fact_train_punctuality: Final model for on-time performance

Dashboard

<img width="723" height="458" alt="image" src="https://github.com/user-attachments/assets/992c2450-821a-469d-88fa-3dd639295b10" />














