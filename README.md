# data-analyst-ishita
Projects
Overview of the projects done in Cloud Computing course
Project 1
Project Description: Descriptive Analysis of Cultural Spaces in Vancouver
Project Title: Understanding Cultural Spaces in the City of Vancouver
Objective: The primary aim of this project is to perform descriptive analysis to identify trends in cultural space (museum/gallery) sizes and seating availability to guide and direct urban planning. This involves analyzing metrics over time to identify patterns. Through the analysis, we aim to answer the following descriptive analysis questions:
•	How has Vancouver's average square footage of cultural spaces changed between 2014 and 2020? 
•	What is the trend in the average number of seats in cultural spaces in Vancouver?
Dataset: This data set provides locations and attributes of cultural spaces in the City of Vancouver, University Endowment Lands and Musqueam Community (Cultural Spaces, 2022). It contains information about museums and galleries in Vancouver from 2014 to 2020, including attributes like:
•	Year: Year of record.
•	Cultural Space Name: Name of the museum/gallery.
•	Website: URL of the institution (if available).
•	Type/Primary Use: Categorized as "Museum/Gallery."
•	Address: Full street address, city, and postal code.
•	Local Area: Neighborhood location (e.g., Downtown, Strathcona, Fairview).
•	Ownership: Privately owned, government, non-profit, etc.
•	Square Feet: Size of the space (if available).
•	Number of Seats: Seating capacity (if available).
•	Active Space: Operational status (Yes/No).
•	Coordinates: Latitude and longitude for mapping.
Methodology:
1-	Data Collection and Preparation:
o	The raw data is downloaded from the City of Vancouver website. 
o	Load the raw dataset in the AWS S3 raw bucket using the upload option. 
o	Perform data cleaning to address missing values, correct data types, and remove duplicates.
o	Rename the columns with the inconsistencies using the camel case format.
2-	Descriptive Statistics:
o	Calculate summary statistics for key variables, including:
	Average size (square feet) of museums/galleries
	Average number of seats available across cultural spaces over the years. 
3-	Insights and Findings:
o	Summarize the insights derived from the analysis, highlighting:
	Average square footage and average number of seats from 2014 to 2020
	Declining trend in seating capacity
	A decline in average square footage in 2015-2016, stabilized in 2017-2018 and experienced significant expansion in 2020.
Tools and Technologies:
•	Draw.io for designing
•	The following AWS services were used:
o	AWS S3 service for data storage 
o	AWS Glue Databrew service for data profiling and cleaning
o	AWS Glue for data cataloging
o	AWS Glue crawler to populate the Data Catalog 
o	AWS Glue service for summarization
Deliverables:
•	A detailed report summarizing the methods, findings, DAP design and implementation screenshots. 
This descriptive analysis project aims to provide a comprehensive understanding of cultural space trends in Vancouver, enabling better planning and development of diverse and accessible cultural venues.
