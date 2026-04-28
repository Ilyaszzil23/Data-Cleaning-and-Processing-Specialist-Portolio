# Ilyas Mohamed - Data Cleaning Specialist Portfolio

## Hi, I hope you are interested in reading my portfolio project!

## About

Hi, I’m Ilyas, a Freelance Data Cleaning Specialist with a strong background in Business and Mathematics (Joint Honours). I help businesses turn messy, unstructured data into organised, reliable, and easy-to-use systems.

I specialise in Python, data visualisation, forecasting, and business-focused data analysis. Whether you need help cleaning datasets, organising income and expenses by date, or building clear dashboards, I focus on delivering practical solutions that improve accuracy and save you time.

Alongside my technical skills, I bring strong business understanding—allowing me to quickly identify issues, structure data effectively, and present insights in a simple, actionable way.

In my role as a Part-time Assistant Accountant, I regularly work with financial records, helping to organise and maintain accurate data for tasks such as tax returns and business registrations. This has strengthened my attention to detail and ability to manage data with precision and confidentiality.

As a freelancer, my priority is to deliver reliable, high-quality work that simplifies your processes and supports better decision-making.


My CV in 

This is a repository to showcase skills, share projects and track my progress in Data cleaning Specialist related topics.

# Table of contents

- [About](#About)

- [Portfolio Projects](#Portfolio-Projects)

  - Pandas - Cleaning data:
  
      - [Global Demographic Data Cleaning (1960–2013)](#global-demographic-data-cleaning-19602013)
    

  - Spreadsheet techniques in Execl (Sample Financial Data Project):
 
  
      - [Cleaning and Organising Raw Data in Excel](#Cleaning-and-Organising-Raw-Data-in-Excel)
   
        
        
      - [Avoid Common Pitfalls in Excel](#Avoiding-Common-Excel-Pitfalls)
   
    
- [Education](#Education)

  

- [Certificates](#Certificates)



- [Contact](#Contact)


# Portfolio Projects

In this section I will list data and processing specalist projects briefly describing the technology stack and data technique used to solve cases.



## Global Demographic Data Cleaning (1960–2013)

**Goal statement:** I cleaned and standardised global demographic data to ensure reliable analysis of life expectancy and fertility rates across countries and regions.


The project focuses on:

  - Handling missing and inconsistent data
  - Standardising country and regional classifications
  - Building reproducible data cleaning workflows in Python
  - Preparing analysis-ready datasets for accurate trend validation

This analysis aims to support the World bank's understanding of global health and demographic shifts.

**Code:** ['World Trends.ipynb'](https://github.com/Ilyaszzil23/Portfolio-Projects/blob/main/World%20Trends.ipynb)

**Raw Data:** ['Demographic-Data World trends.csv'](https://github.com/Ilyaszzil23/Portfolio-Projects/blob/main/Demographic-Data%20World%20trends.csv)


**Skills:** Data Cleaning, Data Preprocessing, Data Validation, Extract-Transform-Load (ETL), Data Standardisation

**Tools:** Jupyter Notebook, Visual Studio Code (offline), Matplotib, Seaborn, Python (Pandas & Numpy), Excel



# Spreadsheet Techniques in Excel (Sample Financial Data Project)

## Data Organisation & Management

In this example, I structured a dataset of income and expenses into a clean, logical format:

- Transactions organised by date for accurate tracking

- Clear categorisation of income and expense types

- Separate columns for amounts, descriptions, and references

- Structured tables to support financial reporting (e.g. profit & loss)

This approach ensures that messy or unstructured data becomes reliable, easy to manage, and ready for analysis.

## Formatting & Presentation

I applied professional formatting techniques to make the spreadsheet user-friendly and visually clear:

- Consistent formatting for dates and currency

- Use of Excel tables, filters, and sorting

- Conditional formatting to highlight key values (e.g. high expenses)

- Clean layout designed for easy navigation and updates

- The goal is to make financial data not just accurate, but easy to understand at a glance.



## Example: Cleaning and Organising Raw Data in Excel

In this example, I created a raw dataset (messy version) to demonstrate how I organise and clean unstructured data step by step.

**Raw Data in Excel:** ['Raw-data-(messy-Version).csv'](https://github.com/Ilyaszzil23/Portfolio-Projects/blob/main/Raw%20data%20(Messy%20Version).csv)



Step 1: Sorting Data

Highlight all data (excluding the headers), then go to Sort & Filter and click Sort.
Select the Amount column and sort from largest to smallest, then click OK.


<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/f5810917-d924-491f-bf64-051a57ee1d47" />



Step 2: Separating Income and Expenses

Next, I split the Amount column into two separate columns: Income and Expense, to improve clarity and make the data easier to analyse.


<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/d43f323a-a8ac-4fb1-9fa0-0c829afb9ce0" />



Step 3: Cleaning Expense Values

Highlight the Expense column, then go to Find & Replace.
In Find what, type - and leave Replace with blank.


<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/aafc40f6-6b1d-4216-ac0f-71b0b27f1f2e" />




Step 4: Applying Replace

Click Replace All to remove negative signs and standardise the data format.


<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/8acdb151-7296-49b5-88f9-2f4a88c582ea" />




Final Step: Sorting by Date

Finally, sort the data by date to ensure all transactions are in chronological order.
Highlight the table and use Sort (Oldest to Newest).


<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/733a1fbf-09b6-4492-bcc9-f19a2fc8941e" />


Result

The dataset is now clean, structured, and easy to analyse. This demonstrates my skills in **data organisation and management**, as well as **formatting and presentation** in Excel.


<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/18e627ee-c810-4058-a7a7-20f1dd274bbc" />


**Clean Data in Excel**: ['Raw data (Clean Version).csv'](https://github.com/Ilyaszzil23/Portfolio-Projects/blob/main/Raw%20data%20(Clean%20Version).csv)

## Avoiding Common Excel Pitfalls

This project also demonstrates best practices to maintain accuracy and prevent errors:

- Avoiding hard-coded values inside formulas

- Ensuring consistency in data entry (dates, categories, formats)

- Minimising duplication and keeping datasets clean

- Using formulas (e.g. totals, summaries) instead of manual calculations

- These techniques are essential when working with financial data, where accuracy and reliability are critical.


This example demonstrates how to efficiently use a conditional formula in expense spreeadsheet.

First, there is no need to manually copy and paste costs into the table, as this would be time-consuming and may lead to errors or confusion.

<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/4ade505e-644d-450f-bb5f-c5d1e26f7a0f" />


Next, a conditional formula is used to simplify the process. By entering a reference number, the formula automatically retrieves and displays the corresponding cost in the correct column.


<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/29797ccb-0c2b-4f0f-9e13-5e71c8eb7d18" />


Finally, the formula uses a combination of absolute and relative cell references. The **$**  symbol locks either the row or the column (e.g., **$H12** fixes the column, while **H$12** fixes the row), allowing the formula to be copied across the table without breaking. This ensures that each value is placed correctly based on the matching number and column header.

<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/747a786b-d920-4ccb-8b94-564c69065769" />


# Education

**BSc (Joint Honours) in Business and Mathematics (2:1)**
University of Hertfordshire - Graduated in 2021

**Relevant Modules for Tech/Programming Roles (Mathematics):**

- Mathematics Techniques level 1 & 2
- Linear Algebra
- Differential Equations
- Number Theory
- Real Analysis
- Nonlinear Systems
- Combinatorics

**Relevant Modules for Business Analysis/Data-Driven Roles (Business):**
- Business Analysis Tools
- Quantitative Methods for Business
- Financial Analysis Techniques
- Management Science in Business
- Performance Strategy
- Principles of Operations Management

**Key skills:**
- Analytical Thinking & Problem-Solving
- Data Analysis & Visualisation
- Financial Modeling & Business Strategy
- Mathematical Optimisation & Statistical Techniques

This combination of skills and knowledge allows me to bridge the gap between **technical development** and **business insights**, ensuring data-driven decision-making and effective problem-solving.

# Certificates

To support my academic background, I have also completed several certifications that demonstrate my practical skills in data analysis, business analysis, and programming. Here are my certifications in reverse-chronolgoical order:

- [Excel (Nov 2021)](https://www.udemy.com/certificate/UC-eecbc119-e324-4e76-8471-b8acc234cd4d/)
- [Python (Mar 2022)](https://www.udemy.com/certificate/UC-baf8f1d5-a867-43fc-bc35-3a4f0a5db8ab/)
- [The SQL Bootcamp (Apr 2022)](https://www.udemy.com/certificate/UC-7bcc7ceb-432a-4879-b336-eaee35b5264b/)
- [Power BI - Data Analytics (Jun 2022)](https://www.udemy.com/certificate/UC-102aa202-6dfc-46ee-97ca-69e4d627ead7/)
- [Business Analysis fundamental (Apr 2024)](https://www.udemy.com/certificate/UC-9b0193bd-a00b-48ee-843a-67d8fe2dfd1e/)


# Contact

- LinkedIn: [Ilyas88](https://www.linkedin.com/in/ilyas88)
- Email:  ilyasM23@outlook.com
- Upwork: 









