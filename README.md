# Accenture: Data Analytics and Visualization Job Simulation  

## Overview  
- **Role:** Data Analyst at Accenture.  
- **Project:** Delivering actionable insights for **Social Buzz**, a social media and content creation platform.  
- **Opportunity:** Showcase data analysis and visualization skills for a potential promotion.  

## Tools Used
**🔨PowerBI**

## About the Client: Social Buzz  
- **Industry:** Social Media & Content Creation  
- **HQ Location:** San Francisco  
- **Founded:** 2010  
- **Employees:** 250 (80% technical staff)  
- **Users:** 500M+ active users monthly  
- **Business Model:**  
  - Focuses on anonymous users and content-centric reactions (100+ reaction types).  
  - Manages unstructured data from 100,000+ daily content uploads (text, images, videos, GIFs).  

## Challenges Faced by Social Buzz  
1. Preparing for an IPO by next year.  
2. Scaling efficiently with limited internal resources.  
3. Learning big data best practices from large corporations.  

## Project Objectives  
1. **Audit** Social Buzz's big data practices.  
2. **Recommend** strategies for a smooth IPO.  
3. **Analyze** and identify the top 5 most popular content categories.  

## Tasks for the Data Analyst  
- Extract and merge sample datasets using SQL.  
- Perform data analysis and create visualizations for insights.  
- Present findings in simple and clear formats.  
- Document the analysis process thoroughly.  

## Team Collaboration  
- Work with Accenture’s cross-functional team and Social Buzz stakeholders.
  
## Skills
- Data extraction, cleaning, and merging (SQL).  
- Data analysis and visualization.  
- Business communication and strategic insights delivery.

## Data Assets
The client has sent -
- **7 data sets -** each data set contains different columns and values
  - User
  - Profile
  - Location
  - Session
  - Content
  - Reaction
  - ReactionTypes
- **A data model -** this shows the relationships between all of the data sets, as well as any links that you can use to merge tables.
  
  ![image](https://github.com/user-attachments/assets/6f7c8bf7-821b-4c85-b3b3-55fa3054f02d)

## Dataset Selection 
- As explained in the data model, popularity is quantified by the “Score” given to each reaction type.
- We therefore need data showing the content ID, category, content type, reaction type, and reaction score.
  These parameters we will get through below tables -
  - ReactionTypes
  - Reaction
  - Content
- So, to figure out popularity, we’ll have to add up which content categories have the largest score.

## Data Cleaning
- In data cleaning process, I removed unnecessary columns.
- Removed rows that had values which were missing.
- Changed data types of some values within a column

**End result is three cleaned data sets.**

## Data Modelling
Created a final data set by merging three tables in PowerBI Power Query Editor


## Result

![image](https://github.com/user-attachments/assets/9fda8fbc-9080-4494-95af-dac90b667292)

## Completion Certificate
![image](https://github.com/user-attachments/assets/bd0487a4-d76f-4205-9e49-a9d1a439a1a9)
