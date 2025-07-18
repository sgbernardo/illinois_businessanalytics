# Learnings from the Business Analytics Focus Area
This repository serves as an exhibit of what I learned in the business analytics focus area during my time at the University of Illinois at Urbana-Champaign. I want to thank all my professors and fellow students for the learning experience. Most of the assignments were completed in R, a programming language commonly used in academia.

## Projects in this Repository

### MBA 561 - Introduction to Business Analytics

**1. Introduction to Business Analytics with R (intro_r_lubridate)**

This project serves as an introduction to the business analytics field, where I learned basic functions from the lubridate package. 

**2. Grocery Data Analysis (grocery_data_analyis)**

This project utilises grocery transactions to perform basic data preparation and inspect variables using R. In addition, data analysis using basic statistics and box plots was also used to analyse outliers.

**3. Grocery Data Analysis - Part 2 (grocery_data_analyis_p2)**

This project utilises grocery transactions to perform basic data preparation and inspect variables using R. Additionally, data analysis using a bar plot was employed to identify the most frequently and least frequently purchased items. I found through the bar plot that the top three most purchased items are entrees, kabobs, and sides. 


### MBA 563 - Data Toolkit
**1. ETL and EDA with R (ETL_EDA_UsingR)**

This project exammines the ETL and EDA functionalities of R using grocery data in MBA 561 to compare the capabilities of R with PowerBI and Alteryx, both used for data analytics and visualisation.

**2. Regression Analysis with R (02.Regression_with_R)**

This project examines bike rental data, utilising multiple regression techniques to investigate the seasonal effect on bike rental usage.

**3. Exploratory Data Analysis of NANSE Sales Data (NANSE_EDA)**

NANSE owns over 700 small-form convenience stores in Canada. This project made use of average sales data from each store location in the country, employing techniques such as correlation, boxplots, and correlation matrices. I found a positive correlation between revenue and store size. In other words, the larger the store, the higher the store's revenues for the company. This is likely due to the availability of products that can be bought in bigger stores. 

The box plot indicates that there were outliers, with some stores having significantly higher revenue than the average store. In terms of gross profit, stores in Ontario (ON) have the highest aggregate gross profit in Canada. The product correlation matrix shows that gum and psd951M product categories sell together the least while candy and take home potato products sell together the most.

### MBA 564A - Applying Data Analytics in Marketing
**1. Data Wrangling using R: Application to Netflix Data**

This project utilised data wrangling in R, leveraging Netflix data as detailed below. I was also able to apply subsetting, data analysis, and regression techniques, where I found that the time_since_release variable is statistically significant in determining sales.

**2. Lululemon Social Media Marketing Strategy Report**

This project analysed Twitter conversations about Lululemon by applying advanced text analytics and network analysis techniques. The scope included summarising public sentiment using sentiment analysis, uncovering major discussion topics with LDA topic modelling, and extracting key conversational patterns using n-gram analysis. To understand social influence, the project also conducted a network analysis of retweets to identify top influencers and quantify their impact on brand perception.

The analysis was performed using R, leveraging the provided datasets of tweets and retweets. Sentiment analysis assessed whether online discussions reflected positively or negatively on the brand. LDA topic modelling was used to reveal underlying themes and frequent discussion points. Network analysis mapped the retweet relationships to highlight users who played a central role in amplifying messages about the brand. 

The findings suggest that Lululemon may need to refine its pricing strategy, customer service, and social media marketing.

### MBA 564B - Applying Data Analytics in Accounting
**1. P-Card Internal Control Analysis and Apple’s MD&A Sentiment Analysis(pca_mda)**

*a. P-Card Internal Control Analysis*

This portion uses data on purchases made through purchase card (p-card) programs administered by the state of Oklahoma and its higher education institutions. We put ourselves in the shoes of auditors assigned to identify transactions that are not related to the operation and improvement of the state. We identified the most problematic transactions by creating a dictionary of problematic words (using a regular expression pattern) and filtering out those that were false positives. We also identified potential violations by filtering transactions that are worth more than $1,500 and contain problematic words. Based on our analysis, we found that the top two problematic purchases, totalling $21,161.80 and $16,018.47, are categorised under the general purchase category. We drilled down further and identified transactions that were especially problematic, potentially indicating that the p-card was used for personal reasons (e.g., Disney hotel bookings, supplements, and cosmetics). We recommended that the auditors ask questions related to the P-card policy, nature of the expenses, and exceptions.  

*b. Apple’s MD&A Sentiment Analysis*

This portion uses text from Apple's management discussion and analysis (MD&A) section, which contains an analysis of the company's performance, including risks (such as material weaknesses and significant deficiencies in the company's internal controls), compliance, and plans. In contrast, the press release reports Apple's earnings and contains forward-looking statements regarding the company's operations and strategy. We found that the MD&A text conveys a more negative sentiment, whereas the press release presents a more positive sentiment. This is likely due to the fact that additional disclosures are included to meet regulatory compliance requirements.
