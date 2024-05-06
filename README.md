# Big Data Analytics Kimia Farma x Rakamin Academy 
## Performance Analytics Kimia Farma Business Year 2020-2023

# Repository Structure
- kimia_farma_analytics.sql: This file consists of SQL queries utilized in the data analysis process.
- kimia_farma_analytics.pdf: This document contains data visualizations presented as links to Looker Studio.

# SQL Tool: Google BigQuery 
- View SQL Script

# Visualization Tool: Google Looker Studio 
- View Dashboard

# Dataset Source: PBI Kimia Farma x Rakamin Academy

# Introduction 
The Project Based Internship (PBI) is an immersive virtual internship program offered by Rakamin Academy in collaboration with various companies. The objective is to explore potential and enhance the experience of PBI participants. In this program, I assume the role of a Big Data Analytics intern at Kimia Farma, tasked with analyzing and reporting on Kimia Farma's Performance Analytics from 2020 to 2023.

# Challenge 
The main objectives include:
- Creating an analysis table from the dataset provided by Kimia Farma.
- Developing visualizations/dashboard for Kimia Farma's Performance Analytics from 2020 to 2023, with specific objectives:
  - Comparing Kimia Farma's Revenue year over year.
  - Identifying the Top 10 Total transaction branches by province.
  - Identifying the Top 10 Nett sales branches by province.
  - Identifying the Top 5 Branches with the highest rating but lowest transaction rating.
  - Determining the Total Profit of Each Province in Indonesia.

# Dataset 
The dataset includes:
- Final transaction
- Inventory
- Kantor Cabang
- Product

# Creating a Datamart 
Utilizing four CSV format files from the dataset, they were imported into Google BigQuery for further processing.

# Preview of Dataset in BigQuery 
The datasets imported into BigQuery include:
- kf_Final_transaction
  ![image](https://github.com/danielrowin/kimia_farma_analytics/assets/151427276/0904d22b-2e2d-4dd9-a58c-9a381d457695)
- kf_Inventory
  ![image](https://github.com/danielrowin/kimia_farma_analytics/assets/151427276/fa5aaa82-b610-449b-8e61-6c65ed9ee79d)
- kf_Kantor_Cabang
  ![image](https://github.com/danielrowin/kimia_farma_analytics/assets/151427276/a37e1524-24d0-4344-8d27-7b924be68ae1)
- kf_Product
  ![image](https://github.com/danielrowin/kimia_farma_analytics/assets/151427276/5d07c837-e40c-483b-afb4-fb4e867a52ce)

# My Query 
An analysis table was created using a query similar to the one displayed in the provided image.
![image](https://github.com/danielrowin/kimia_farma_analytics/assets/151427276/93dd2226-a87d-459e-b97b-8c5d055027cf)

# Preview of Table Result 
The resulting table from the query is showcased in the provided images.
![image](https://github.com/danielrowin/kimia_farma_analytics/assets/151427276/a8d7d4c2-dd44-4b81-b2bb-e49413995479)

# Data Visualization 
Visualizations were crafted using Looker Studio. The visualization results from the Datamart are provided, enabling interaction with the data visualization in Looker Studio.
![image](https://github.com/danielrowin/kimia_farma_analytics/assets/151427276/76a39f9d-34ea-43c0-846c-04499535e276)

# Top 10 Branch Transaction By Province 
This visualization showcases data on the top 10 branches' transactions by province.
![image](https://github.com/danielrowin/kimia_farma_analytics/assets/151427276/003c5080-d5ae-43b4-bf12-9446f52d31cf)

# Top 10 Branch Sales By Province 
This visualization presents data on the top 10 sales branches by province.
![image](https://github.com/danielrowin/kimia_farma_analytics/assets/151427276/cb4167c4-5eae-4343-a35b-3613b9b796bc)

# Top 5 Branches with Highest Ratings but Lowest Transaction Ratings 
This visualization displays the top 5 branches by province with the highest branch ratings but the lowest transaction ratings.
![image](https://github.com/danielrowin/kimia_farma_analytics/assets/151427276/a2078e77-2feb-411a-9bdf-7e2d9b83dd3b)

# Comparison of Kimia Farma's Profit Over the Years 
This visualization illustrates Kimia Farma's profit range from 2020 to 2023.
![image](https://github.com/danielrowin/kimia_farma_analytics/assets/151427276/e7085413-1134-46fc-a191-e12610cbb398)

# Summary 
A summary map of Indonesia is provided, showing the income of each province from 2020 to 2023. Additionally, total transactions, total sales, and total profit figures for Indonesia from 2020 to 2023 are presented.
![image](https://github.com/danielrowin/kimia_farma_analytics/assets/151427276/cb9928be-b5f6-458b-9baf-617cf594c5f2)


# Link Datamart & Filter 
Buttons are available to access the table analytics and filter data by province or date.
![image](https://github.com/danielrowin/kimia_farma_analytics/assets/151427276/82b46490-c679-448f-879d-c2b5c2a28b69)

# Conclusion 
In conclusion, this README provides a comprehensive overview of the project, including installation steps, usage instructions, and relevant additional information. We trust that the information provided herein will be valuable to both users and contributors of this project. Thank you for your interest in our project!







