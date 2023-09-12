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
![2](https://github.com/OmMahalle/Covid-19-EDA/assets/133775655/9cabd93d-7779-49ba-895b-227a5ad5aa31)


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

![3](https://github.com/OmMahalle/Covid-19-EDA/assets/133775655/301f3385-2e84-45a5-86be-32bcfb0452d9)


 <br /> 

## *Data Transformation including flattening of the data:*

![4](https://github.com/OmMahalle/Covid-19-EDA/assets/133775655/2d259fa7-8144-4d81-8425-ca619ee00ea4)


![5](https://github.com/OmMahalle/Covid-19-EDA/assets/133775655/9fa9d741-99af-4c17-830b-ca4fa8512128)


 <br /> 

## *Data cleaning - It typically involves removing irrelevant or duplicate data, handling missing values, and ensuring data consistency and integrity.*

 <br /> 
 
### *Dropping Duplicate Records:*

![6](https://github.com/OmMahalle/Covid-19-EDA/assets/133775655/379706e9-fb4f-4d50-8080-a240ac40adb4)



### *Dropping Unnecessary columns from the dataframe:*

![7](https://github.com/OmMahalle/Covid-19-EDA/assets/133775655/2b019476-5f38-4f3c-be24-83996df9e702)



![8](https://github.com/OmMahalle/Covid-19-EDA/assets/133775655/eeee4e37-65c1-46f8-9a86-8637cc0a3856)


### *Converting into csv files:*

![9](https://github.com/OmMahalle/Covid-19-EDA/assets/133775655/22d89573-490b-4003-ae5f-3bd8a73bfb70)

 
<br />

### *KEY PERFORMANCE INDICATORS*
#### *A KPI, or Key Performance Indicator, is a measurable value that helps assess how effectively an organization or individual is achieving important goals. KPIs provide insights into performance, guiding decisions and improvements by offering quantifiable information on various aspects of success. * 
![10](https://github.com/OmMahalle/Covid-19-EDA/assets/133775655/0fc04e9e-ecb9-4a8e-86b4-ad2a6f579ce9)

<br />

### *KEY FINDINGS*
![11](https://github.com/OmMahalle/Covid-19-EDA/assets/133775655/bb62bc5d-808c-4d1f-ad83-d7a465cb2ea8)


<br />

### *VISUAL REPRESENTATION AND ANALYSIS*
![12](https://github.com/OmMahalle/Covid-19-EDA/assets/133775655/b6cb87a4-ad34-400d-be88-2d8996f2079e)


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
![13](https://github.com/OmMahalle/Covid-19-EDA/assets/133775655/6e3051a2-7af3-417c-b46a-9bc4e1a87d11)


##Thank You !
