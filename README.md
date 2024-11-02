# amazon_top_ssellers
A Case Study Project 

## Table of Content 
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Project Structure](#project-structure)
- [Data Analysis](#data-analysis)
- - [Data Visualiation](#data-visualization)
- [Results](#results)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
  
## Project Overview 
  You are a jjunnior data analyst working for a busness intelligence company.you've been there for 6 mmonths, and your boss feels youare ready for more responsibility. he has asked you to lead a project for a brand neww client - he wants you tocarry out an analysis for a book store. they want you to use the amazon top 50 best sweller from 2009 to 2019 to provide insights for them to stock their inventory and maximize thier sales.
## Data Source
  Amazon Top 50 best sellers
  https://www.kaggle.com/datasets/sootersaalu/amazon-top-50-bestselling-books-2009-2019
  
## Tools
  Big Query sql | Ms Excel | Tableau
  
## Project Structure
  Data
  - Data Collection
      ![image](https://github.com/user-attachments/assets/e5509fc2-a13f-4897-97ca-938294c08821)


  - Data Overview
    excel spread sheets was used in data overview to get he general understanding of the dataset
    ![Screenshot 2024-11-02 002015](https://github.com/user-attachments/assets/2084826f-f05f-4d02-ace5-443d797a1758)

 
  - Data Transfromation
    big query's sql was used to perform data transformation. that transformatio can be performed easily with big query
    ![image](https://github.com/user-attachments/assets/a2e910a0-529a-4ea2-9d95-ec948c3e77d8)

    
## Data Analysis 
  analysis of the dataset was done with sql on the big query platform. sql is a perfect tool for carrying out data analysis and manupulation
  
  ![image](https://github.com/user-attachments/assets/a653acf0-5945-46b8-b390-724a3b70685f)

  
  in the images below we can see a code snippet of how sql was used to analze the dataset 

  - genre analysis
    ![image](https://github.com/user-attachments/assets/410a66b7-a853-4732-87e3-6a7977a995cd)
      using genre and year colums to producee information about the dataset
  
 - price analysis 
    ![image](https://github.com/user-attachments/assets/3ca8269f-d660-4a04-bffa-88140b2a5af4)
    here we query for aerage prices of books, minimum orices, maximum prices of books sold.

  - rating analysis 
    ![image](https://github.com/user-attachments/assets/e334520b-5469-41e9-8b14-7d50f1065964)
    this query is showing the rating distribution and correlaation with reviews

  - author analysis 
    ![image](https://github.com/user-attachments/assets/f7c1ac0d-e0c7-4400-963f-9ba030b6bb13)
    this query shows top authors by appearance, frequncy and ratings 

  - review impact analysis 
    ![image](https://github.com/user-attachments/assets/880d716b-ce5d-4351-ae64-31c765dd2d00)
    analyzes relationship between reviews and ratings 
  

  


  
## Data Visualization
  - python can alaso be used to carry out data visualization    
    ![output_20_0](https://github.com/user-attachments/assets/67a589cf-6277-4ce5-ac91-dc308ab6f87f)
    the above image showing rides by hour stats between the casual riders and members

  - Number of rides days of the week stats between the casual and member
    ![output_21_0](https://github.com/user-attachments/assets/96a9c694-269e-4f2c-ba52-29ab254980d3)

  - ride length distribution between casuals and member customers
    ![output_21_0](https://github.com/user-attachments/assets/cbcc8428-fe25-47d7-9969-d9837d83b73e)
  
## Results 
  the reults of the analysis  shows 
  - the members have a higher activity rate from the 7am to 9pm 
  - but in the case of rides more causals riders makes trips on everyday of the weeek than the members
  -  wednesdays and thursdays are the days with the most bike trips by casuals
  -  saturdays and sunday is the time when members make the most bike trips
## Recommendations 
  - Target casual riders with promotions for weekday rides: Incentivize weekday usage to increase casual         rider engagement.
  - Offer trial memberships: A limited-time offer for casual riders to experience member benefits may             encourage them to convert to annual members.
  - Digital media campaigns: Use social media and targeted ads focusing on convenience, flexibility, and cost savings to appeal to casual riders.
## Limitations
  i was not able to use sql for this project because my Sql won't let me import multiple data, big query won't let me unless i suncribe to google cloud services and big query sub.
