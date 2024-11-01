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
    
 
  - Data Transfromation
    
    jupyter note book is used to perform the data transformation because we are using python to analyse this dataset 
    python gives us a lot of flexibility when handling data
    ![image](https://github.com/user-attachments/assets/90460f10-0d6b-412a-a79c-08149a6e742e)
## Data Analysis 
  jupyter note book is used to perform the data anlysis because we are using python to analyse this dataset 
  python gives us a lot of flexibility when handling data.
  
  ![image](https://github.com/user-attachments/assets/e98754df-9f83-4059-9489-fb035209d470)
  
  in the image we can see how we can use jupyter notebook and python can perform analysis. the image shows     us   the calculation of the ride lenght in minutes.

  here we convert the started at column and the ended at column to datetime format
  ![image](https://github.com/user-attachments/assets/426e2e7b-8e36-4c7b-85a4-ef2991a201f8)
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
