# Covid-19 India Data Analysis

### *INTRODUCTION*

#### This project is a data analysis project on COVID-19 in India. It aims to provide insights into the patterns and trends of the pandemic in India and identify potential implications for different sectors, such as healthcare, retail, travel, and investment. The goal of the project is to help organizations make informed decisions by leveraging data-driven insights and evidence-based strategies. 
<br /> 

![266233740-0779a54a-f3e0-4548-8e96-8da8558b7578](https://github.com/OmMahalle/Covid-19-EDA/assets/133775655/3e0f6f09-9d3f-4c1b-9b7d-24cd255e4698)


<br />

### *TABLE OF CONTENTS*

| Files/Folder | Description |
| -----------  | ----------- |
| CSV Files       | This folder contains cleaned csv data files          |
| Excel File Dashboard    | This folder contains Dashboard file     |
| Jupyter Notebook Files | This folder contains Jupyter notebook file & Web driver used for Web scraping   |
| Presentation | This is a powerpoint presentation file that contains all major insights and conclusion |


<br />

### *DATA COLLECTION AND PRE-PROCESSING*
The data collection and preprocessing phase of the project involves gathering relevant data on COVID-19 in India and preparing it for analysis.
An API is used to fetch data related to Covid19. 
![image](https://github.com/Rushikesh-Kharat/Covid19-India-Exploratory-Data-Analysis/assets/99657888/f8848f61-b9ca-4604-bec2-318efd701460)

<br /> 

#### The following technologies are used to collect and work on data:
1. Python programming with Pandas Library.
2. SQL (Structured Query Language)
3. Requests module to retrieve data from online sources(API).
4. Microsoft Excel for data visualisation and analysis.

<br />

* The data was in JSON format, using Pandas and Python, data is converted to a dataframe. Then Data Cleaning was performed on the dataframe object. *
Data is then categorized as State-wise, District-wise data and based on timeline.

 <br /> 

## *Data Scraping:*

![image](https://github.com/Rushikesh-Kharat/Covid19-India-Exploratory-Data-Analysis/assets/99657888/db65bbcc-054f-47ed-98a1-19c590966f90)

 <br /> 

## *Data Transformation including flattening of the data:*

![image](https://github.com/Rushikesh-Kharat/Covid19-India-Exploratory-Data-Analysis/assets/99657888/fb4d510d-44fa-4205-87cd-1df63ec70a6c)

![image](https://github.com/Rushikesh-Kharat/Covid19-India-Exploratory-Data-Analysis/assets/99657888/e42afd08-adb0-43b1-b9d7-dcce4b3b32a6)

 <br /> 

## *Data cleaning - It typically involves removing irrelevant or duplicate data, handling missing values, and ensuring data consistency and integrity.*

 <br /> 
 
### *Dropping Duplicate Records:*

![image](https://github.com/Rushikesh-Kharat/Covid19-India-Exploratory-Data-Analysis/assets/99657888/20608d8a-15ee-4078-847f-8837acb48caf)


### *Dropping Unnecessary columns from the dataframe:*

![image](https://github.com/Rushikesh-Kharat/Covid19-India-Exploratory-Data-Analysis/assets/99657888/ad40521f-c64f-47bc-bd55-4e826d2e359e)


![image](https://github.com/Rushikesh-Kharat/Covid19-India-Exploratory-Data-Analysis/assets/99657888/6c287826-fc7f-493c-9bdd-58f140bb4f74)

### *Converting into csv files:*

![image](https://github.com/Rushikesh-Kharat/Covid19-India-Exploratory-Data-Analysis/assets/99657888/173d74a2-16fa-4e7e-8b14-9a9642fc5da7)
 
<br />

### *KEY PERFORMANCE INDICATORS*
#### *A KPI, or Key Performance Indicator, is a measurable value that helps assess how effectively an organization or individual is achieving important goals. KPIs provide insights into performance, guiding decisions and improvements by offering quantifiable information on various aspects of success. * 
![image](https://github.com/Rushikesh-Kharat/Covid19-India-Exploratory-Data-Analysis/assets/99657888/7387c7d2-cbcd-4767-8fd1-56f4dcc9d01a)
<br />

### *KEY FINDINGS*
![image](https://github.com/Rushikesh-Kharat/Covid19-India-Exploratory-Data-Analysis/assets/99657888/292fdb4d-752c-4f9e-aaeb-2e33c07068c6)

<br />

### *VISUAL REPRESENTATION AND ANALYSIS*
![image](https://github.com/Rushikesh-Kharat/Covid19-India-Exploratory-Data-Analysis/assets/99657888/fe8b70b8-cdb9-4749-8015-3060eb4f7e42)

<br />

## CHALLENGES FACED

During the development of this project, several challenges were encountered, and here are some of the major ones:

### 1. Data Scraping

Obtaining the initial data from the web posed several challenges. Some of the issues faced during data scraping included:

- *Website Structure*: The target website frequently changed its structure, which required constant adjustments to the scraping code.

### 2. Data Transformation

Converting the scraped data, which was in JSON format, into the required dataframes and CSV files was another challenge. Key challenges in this phase included:

- *Data Structure*: The JSON data had a nested structure that needed to be flattened to fit into dataframes.

- *Data Integration*: Merging data from multiple sources while maintaining data integrity required careful planning and coding.

### 3. Data Cleaning

Cleaning the data was an essential step to ensure the accuracy and reliability of the final dataset. Some of the challenges encountered in data cleaning were:

- *Missing Values*: Dealing with missing values and deciding on appropriate imputation methods.

- *Inconsistent Data*: Handling inconsistencies and errors in the data, such as typos and formatting issues.

These challenges were overcome through collaboration, research, and iterative development. Documenting these obstacles and solutions here will help future contributors and developers understand the project's history and complexities.

### *CONCLUSION*
![image](https://github.com/Rushikesh-Kharat/Covid19-India-Exploratory-Data-Analysis/assets/99657888/8198805b-b6d8-4b11-8087-784fe9254957)

##Thank You !
