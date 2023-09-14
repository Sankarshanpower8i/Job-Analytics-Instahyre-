# Project Name: Job Analytics - Data Analysis

![title](https://github.com/Sankarshanpower8i/Job-Analytics-Instahyre-/assets/133600711/62a4bcf7-cae8-4374-a71e-21b42abdd37a)


## Introduction

The project aims to analyze job data scraped from LinkedIn using Python libraries such as BeautifulSoup and Power Query. The primary goal is to gain insights into the job market trends, industry preferences, and other valuable information from the collected data.

## Problem Aimed to Solve

1. Analyzing the job market trends to identify the most in-demand skills.
2. Understanding the top hiring industries and job locations.
   
   ![job count by location](https://github.com/Sankarshanpower8i/Job-Analytics-Instahyre-/assets/133600711/d506aec0-6365-4437-901e-7f4e03ba1e1c)

4. Exploring the distribution of job types (e.g., full-time, internship).
5. Analyzing the company landscape, including industry preferences and company sizes.

## Data Description

The project uses three main tables:

- Jobs Table: Contains information related to job postings, including job ID, company ID, job location, job title, and details ID.

- Company Table: Contains information related to companies posting job listings, including the company ID, company name, industry, number of employees, and number of LinkedIn followers.

- Details Table: Contains additional details related to job postings, including the details ID, experience level, required skills, and the total number of job applicants.

## Methodology

The following methodology was used to accomplish the project objectives:

1. **Data Scraping:** Job data was scraped from LinkedIn using the Python library BeautifulSoup. The data was scraped based on specific search criteria, such as job titles, job locations, and company names.

2. **Data Transformation:** The scraped data was transformed into three tables: jobs, company, and details, using Power Query and Excel. Each table was structured with relevant attributes.

3. **Data Cleaning and Pre-processing:** The data cleaning process included eliminating irrelevant data, addressing missing values, standardizing formats, removing duplicates, cleaning textual data, handling outliers, converting data types, checking for inconsistencies, normalizing categorical data, and validating data integrity.

4. **Data Analysis:** The analysis focused on generating insights and visualizations from the collected data. Key analysis points included:

![Dashboard-1](https://github.com/Sankarshanpower8i/Job-Analytics-Instahyre-/assets/133600711/f528b3fa-de7d-4514-bd0e-143628e265a2)
   - Identifying the most in-demand skills based on job descriptions.
   - Determining the top hiring industries and job locations.
   - Exploring the distribution of job types (e.g., full-time, internship).
   - Analyzing the company landscape, including industry preferences and company sizes.

## Results

### Key Insights from Data Analysis

- Maximum job opportunities are in Bengaluru.
- Top hiring industries are Information and Technology, Financial, and Education.
- Top 5 states with the most jobs are Delhi, Maharashtra, Haryana, Karnataka, and Uttar Pradesh.
- Most jobs are full-time positions.
- Companies with 1000+ employees have the highest volume of job postings.

## Limitations

- The analysis is based on the data available from LinkedIn, and any changes in LinkedIn's data structure could affect the analysis.
- The accuracy of NLP in identifying skills from job descriptions depends on the quality of the data and the effectiveness of the NLP techniques used.

## Challenges

- Implementing NLP for skill extraction and analysis required in-depth research and technical expertise.
- Handling and cleaning a large dataset to ensure data quality and integrity was a challenging task.

## References

- Python Software Foundation. (2022). Python Language Reference, version 3.10. Retrieved from https://docs.python.org/3/reference/index.html
- Wikipedia contributors. (2023, April 19). BeautifulSoup. In Wikipedia, The Free Encyclopedia. Retrieved 15:44, April 22, 2023, from "https://en.wikipedia.org/wiki/Beautiful_Soup_(HTML_parser)"
- Pandas Development Team. (n.d.). pandas 1.4.5 documentation. Retrieved April 22, 2023, from "https://pandas.pydata.org/docs/"
- Scikit-learn developers. (n.d.). Clustering. Retrieved April 22, 2023, from "https://scikit-learn.org/stable/modules/clustering.html"
