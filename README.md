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
 You are a junior data analyst working for a business intelligence company. You've been with the company for six months, and your boss feels you are ready for more responsibility. He has asked you to lead a project for a new client—a bookstore. The client wants you to conduct an analysis using the Amazon Top 50 Bestsellers from 2009 to 2019 to provide insights that will help them stock their inventory and maximize sales.
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
    
       using genre and year colums to producee information about the dataset
      ![image](https://github.com/user-attachments/assets/410a66b7-a853-4732-87e3-6a7977a995cd)
        
  
 - price analysis

    here we query for aerage prices of books, minimum orices, maximum prices of books sold.
   ![image](https://github.com/user-attachments/assets/3ca8269f-d660-4a04-bffa-88140b2a5af4)
       

  - rating analysis

    this query is showing the rating distribution and correlaation with reviews
   ![image](https://github.com/user-attachments/assets/e334520b-5469-41e9-8b14-7d50f1065964)
          

  - author analysis

    this query shows top authors by appearance, frequncy and ratings  
     ![image](https://github.com/user-attachments/assets/f7c1ac0d-e0c7-4400-963f-9ba030b6bb13)
          

  - review impact analysis

    analyzes relationship between reviews and ratings 
    ![image](https://github.com/user-attachments/assets/880d716b-ce5d-4351-ae64-31c765dd2d00)
          
  

  
  
## Data Visualization
  - Tableau is one of the best softwares out there to carry our data visuaization. it is able to bring to life both simple and complex visualizations to life.
    https://public.tableau.com/app/profile/jide.ewuola/vizzes
    
    

  - Genre distribution over time 
    ![image](https://github.com/user-attachments/assets/76ac2f42-4889-44a3-abbb-8533abfd654b)


  - book price analysis by genre year
    ![image](https://github.com/user-attachments/assets/5599d7f0-9560-44cf-8271-a14bf68a0c6b)

  - rating distribution
    ![image](https://github.com/user-attachments/assets/560a6713-fd94-4895-bfb1-75a95dbf04fb)
    
  - author performace analysis
    ![image](https://github.com/user-attachments/assets/43d3a01e-5d92-4789-a319-36935187083f)

    

## Results 
  he analysis of the Amazon Top 50 Bestselling Books dataset (2009 - 2019) using SQL and Tableau provides insights into key factors that make books successful on Amazon. Here’s a breakdown of findings based on common trends and patterns in the data:

1. Genre Popularity
Top Genres: Some genres consistently dominate the bestsellers list, likely due to reader preferences. For example, genres like "Fiction" or "Non-Fiction" may show higher counts than niche genres.
Recommendation: Authors and publishers focusing on these popular genres might have better chances of success. However, less competitive genres could provide opportunities for unique entries.
2. Price vs. Reviews
Correlation between Price and Engagement: By analyzing the number of reviews against book prices, we might see that books priced moderately (e.g., $10 - $15) receive more reviews, suggesting an ideal pricing range.
Recommendation: Pricing competitively within this range could encourage more customer engagement without compromising perceived value.
3. Average Rating by Genre
Higher Ratings in Certain Genres: Some genres tend to receive higher average ratings, indicating reader satisfaction. For instance, educational or self-help genres might show higher ratings, suggesting they deliver on reader expectations.
Recommendation: New authors should consider genre-specific reader expectations, especially in categories where readers consistently rate books highly.
4. Annual Trends
Rise or Decline in Genre Popularity Over Time: Line charts showing bestsellers by year reveal if certain genres gain or lose popularity. For example, a steady rise in self-help or thriller genres over the years might reflect current trends.
Recommendation: Publishers could benefit by focusing on genres that show upward trends or by innovating within declining genres to rekindle interest.
5. Impact of Ratings and Reviews
Reviews and Ratings Relationship: Books with higher ratings often have a high number of reviews, indicating reader engagement plays a role in sales ranking. A few outliers may have high reviews despite average ratings, likely due to hype or publicity.
Recommendation: Authors should focus on quality and encourage readers to leave positive feedback, as ratings and reviews impact book visibility and success.

## Recommendations 
   Based on the findings, here are a few broader recommendations:

-    Genre-Specific Marketing: Invest in marketing for high-performing genres, while also exploring niche     categories to capture unique audiences.
-   Optimized Pricing: Moderate pricing aligns with higher customer engagement. Promotions and discounts within a specific range might help boost visibility without diminishing perceived quality.
-   Focus on Reader Engagement: Encouraging reviews and improving ratings (through quality writing and targeted marketing) can enhance a book's ranking and appeal.
    This analysis provides a foundation for understanding bestselling patterns and could help authors, publishers, and marketers make strategic decisions to improve book performance on Amazon.
## Limitations
  i was not able to use sql for this project because my Sql won't let me import multiple data, big query won't let me unless i suncribe to google cloud services and big query sub.
