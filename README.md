# <a name="_toc1949047065"></a>**Project 1 - Exploratory Data Analysis**
<a name="_toc979250339"></a>**Project Description:** Exploratory Data Analysis (EDA) on Cultural Spaces in Vancouver

<a name="_toc498019745"></a>**Project Title:** Mapping Vancouver’s Cultural Spaces: An Exploratory Data Analysis

<a name="_toc1076036247"></a>**Objective:** The primary goal of this project is to perform exploratory data analysis (EDA) on Vancouver’s cultural spaces dataset to uncover patterns and trends and get insights into spatial, operational, and ownership trends. We aim to understand how cultural resources are allocated across neighbourhoods by analyzing facility size, ownership types, and operational status. 

<a name="_toc932132075"></a>**Dataset:** The dataset contains records of Vancouver’s museums, galleries, and cultural spaces (2014–2020), including:

- **Year**: Year of record (2014–2020).
- **Cultural Space Name**: Name of the institution (e.g., "Vancouver Art Gallery").
- **Website**: URL for the institution (if available).
- **Type/Primary Use**: Categorized as "Museum/Gallery."
- **Address**: Full street address, city, and postal code.
- **Local Area**: Neighborhood (e.g., Downtown, Strathcona, Fairview).
- **Ownership**: Type (Privately Owned, Government, Non-Profit, City of Vancouver).
- **Square Feet**: Size of the facility (30% missing values).
- **Active Space**: Operational status (Yes/No).
- **Coordinates**: Latitude and longitude for geospatial mapping.
## <a name="_toc694820834"></a>Data Analytics Platform Design
![image](https://github.com/user-attachments/assets/bfecb8c3-75d8-421b-a40d-2aa7deb71c23)
## <a name="_toc694820834"></a>Methodology:
1. **Data Collection and Preparation:**
   - The raw data is downloaded from the City of Vancouver website. 
   - Load the raw dataset in the AWS S3 raw bucket using the upload option. 
   - Perform data cleaning to address missing values, correct data types, and remove duplicates.
   - Rename the columns with the inconsistencies using the camel case format.
   - Create a data catalog using AWS Glue Crawlers to generate a schema from transformed data for querying purpose
1. **Descriptive Statistics:**
   - Average size (square feet) of museums/galleries.
   - Range of seating capacity across different cultural spaces (minimum and maximum)
   - Identify trends in the physical space (average size in square feet) of museums/galleries over time.
1. **Insights and Findings:**
   - A decline in average square footage in 2015-2016, stabilized in 2017-2018 and experienced significant expansion in 2020.
   - Declining trend in seating capacity
   - Average square footage and average number of seats from 2014 to 2020
## <a name="_toc2050187544"></a>**Tools and Technologies:**
- Draw.io for designing
- The following AWS services were used:
  - AWS S3 service for data storage 
  - AWS Glue Databrew service for data profiling and cleaning
  - AWS Glue for data cataloging
  - AWS Glue crawler to populate the Data Catalog 
  - AWS Glue service for summarization
  - AWS Amazon Athena service to run the SQL queries
## <a name="_toc1413021882"></a>**Deliverables:**
- A comprehensive report containing all analysis steps, design and implementation.

This EDA project helps to demonstrate my analytical and programming skills. It highlights my ability to derive meaningful insights from data. 
# <a name="_toc1725342580"></a>**Project 2- Descriptive Analysis** 
<a name="_toc1135837671"></a>**Project Description:** Descriptive Analysis of Cultural Spaces in Vancouver

<a name="_toc257945545"></a>**Project Title:** Understanding Cultural Spaces in the City of Vancouver

<a name="_toc1034375307"></a>**Objective:** The primary aim of this project is to perform descriptive analysis to identify trends in cultural space (museum/gallery) sizes and seating availability to guide and direct urban planning. This involves analyzing metrics over time to identify patterns. Through the analysis, we aim to answer the following descriptive analysis questions:

- How has Vancouver's average square footage of cultural spaces changed between 2014 and 2020? 
- What is the trend in the average number of seats in cultural spaces in Vancouver?

<a name="_toc1371416104"></a>**Dataset:** This data set provides locations and attributes of cultural spaces in the City of Vancouver, University Endowment Lands and Musqueam Community (*Cultural Spaces*, 2022). It contains information about museums and galleries in Vancouver from 2014 to 2020, including attributes like:

- Year: Year of record.
- Cultural Space Name: Name of the museum/gallery.
- Website: URL of the institution (if available).
- Type/Primary Use: Categorized as "Museum/Gallery."
- Address: Full street address, city, and postal code.
- Local Area: Neighborhood location (e.g., Downtown, Strathcona, Fairview).
- Ownership: Privately owned, government, non-profit, etc.
- Square Feet: Size of the space (if available).
- Number of Seats: Seating capacity (if available).
- Active Space: Operational status (Yes/No).
- Coordinates: Latitude and longitude for mapping.
## <a name="_toc694820834"></a>Data Analytics Platform Design
![image](https://github.com/user-attachments/assets/9aa6b681-8db7-4fb3-9139-9147646a05c8)
## <a name="_toc1246240713"></a>**Methodology:**
1. **Data Collection and Preparation:**
   - The raw data is downloaded from the City of Vancouver website. 
   - Load the raw dataset in the AWS S3 raw bucket using the upload option. 
   - Perform data cleaning to address missing values, correct data types, and remove duplicates.
   - Rename the columns with the inconsistencies using the camel case format.
1. **Descriptive Statistics:**
   - Calculate summary statistics for key variables, including:
     - Average size (square feet) of museums/galleries
     - Average number of seats available across cultural spaces over the years. 
1. **Insights and Findings:**
   - Summarize the insights derived from the analysis, highlighting:
     - Average square footage and average number of seats from 2014 to 2020
     - Declining trend in seating capacity
     - A decline in average square footage in 2015-2016, stabilized in 2017-2018 and experienced significant expansion in 2020.
## <a name="_toc1111413764"></a>**Tools and Technologies:**
- Draw.io for designing
- The following AWS services were used:
  - AWS S3 service for data storage 
  - AWS Glue Databrew service for data profiling and cleaning
  - AWS Glue for data cataloging
  - AWS Glue crawler to populate the Data Catalog 
  - AWS Glue service for summarization
## <a name="_toc59278851"></a>**Deliverables:**
- A detailed report summarizing the methods, findings, DAP design and implementation screenshots. 

This descriptive analysis project aims to provide a comprehensive understanding of cultural space trends in Vancouver, enabling better planning and development of diverse and accessible cultural venues.
# <a name="_toc307757619"></a>**Summary Statistics**
![image](https://github.com/user-attachments/assets/0d336706-bce0-4cf1-86aa-5ae7cd5f6c39)

# <a name="_toc307757619"></a>**Project 3- Data Wrangling** 
### <a name="_toc810874663"></a>**Project Description:** Data Wrangling for Vancouver’s Cultural Spaces
<a name="_toc409633099"></a>**Project Title:** Data Wrangling for informed and fair urban planning

<a name="_toc620227197"></a>**Objective:** To prepare a clean, standardized, and comprehensive dataset of Vancouver’s cultural spaces (2014–2020) by addressing data quality issues. This will enable accurate analysis for equitable resource allocation, policy development, and community engagement.

<a name="_toc404141085"></a>**Background:** The City of Vancouver’s cultural spaces dataset is vital for preserving arts and heritage, but raw data suffers from:

- **Missing Values**: Lack of values for square feet data and website.
- **Inconsistencies**: Varied labels for ownership (e.g., “Non-Profit” vs. “Non Profit”).
- **Duplicates**: Repeated entries for institutions like the “Vancouver Art Gallery” across the years.

Effective data wrangling will facilitate better decision-making and more targeted marketing strategies.

<a name="_toc1308325367"></a>**Dataset:** The data wrangling process will involve various datasets, including:

- **Cultural Spaces Data**: Annual records (2014–2020) with fields like name, address, ownership type, square footage, and coordinates.
## <a name="_toc1366712941"></a>**Methodology:**
1. **Data Collection:**
   - Raw data from City of Vancouver’s open data portal.
1. **Data Assessment:**
   - Use AWS Glue Databrew service to understand data issues. 
   - It also helps document data types, formats, and discrepancies.
1. **Data Cleaning:**
   - The AWS Glue Databrew service helps to perform data profiling.  
   - Remove duplicate records and correct inconsistencies in data formats (e.g., date formats, naming conventions).
   - Normalize categorical variables to ensure consistency across datasets.
1. **Data Transformation:**
   - Perform data type conversions to ensure that all fields are in suitable formats for analysis (e.g., converting strings to datetime objects).
   - Derive new features that may aid in analytics, such as report date time. 
1. **Documentation and Validation:**
   - Document the data wrangling process, including data sources, cleaning methods, and transformations applied to the dataset.
   - Validate the final dataset through exploratory data analysis (EDA) to confirm accuracy and completeness.
## <a name="_toc1264904900"></a>**Tools and Technologies:**
- AWS Glue Databrew Service for profiling and cleaning
- AWS S3 bucket to store the datasets.
## <a name="_toc86834294"></a>**Deliverables:**
- A clean and transformed dataset ready for analysis, available in a suitable format (e.g., CSV for user and parquet for system).
- A comprehensive report documenting the data wrangling process, including challenges encountered, methods employed, and final dataset characteristics.
## <a name="_toc177782647"></a>**Timeline:**
- Expected completion of the project: 3 months, including phases for assessment, cleaning, transformation, and documentation.

This data-wrangling project aims to ensure Vancouver’s cultural spaces dataset is a reliable foundation for inclusive urban development. 
