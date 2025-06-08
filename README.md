# Netflix Project - User Behavior Analysis
![BrandAssets_Logos_01-Wordmark](https://github.com/user-attachments/assets/b7dea815-4fd7-4fe4-81b4-65cf637db819)

## Project Overview
This project analyzes Netflix user data from Kaggle to understand user behavior, preferences, and engagement metrics. The insights help inform the marketing strategies, imporove user retention, and guide content recommendations.

**Dataset:** Kaggle Netflix Data: https://www.kaggle.com/datasets/chul24/data-neflix/data

## Key Objectives
- Identify the highest number of subscribtions by country and plan type.
- Analyze genre preferences by gender and country.
- Understand the relationship between monthly income and subscription plans.
- Examine user retention and renewal patterns.
  
## Key Business Questions
1. Which country has the highest number of subscriptions by method?
2. Which genre is most watched by gender? Which genre is most popular by country? 
3. Does monthly income affect the choice of subscription method and plan? What percentage of users renew their subscriptions after their initial plan duration ends?
4. What is the retention rate based on join and last payment dates? Is there a seasonal trend in user join dates or subscription renewals?

## Key Findings

### 1. Top Countries by Subscription Method
- The top 10 countries with the highest Netflix subscriptions are : Spain, United Satetes, Canada, Brazil, United Kingdom, France, Italy, Australia, Mexico, and Germany.
- **Plan Preferences:**
- - **Spain:** Standard and Premium dominate.
  - **United States:** Even distribution across all plans.
  - **Canada, Brazil, Italy, Germany:** Mostly Basic plans.
  - **France:** Mostly Premium plans.
  - **UK & Mexico:** Mostly Standard plans.
 
**Recommendation:**
-Encourage Premium adoptin in Basic, standard heavy markets with exclusive shows or local partnerships that might attract more subscribers.

## 2. Genre Popularity by Gender and Country
- **By Gender:**
- Women prefer Comedy (15%), then Horror, Drama, Action & Adventure, and others.
- Men prefer Horror (20%) and Action & Adventure (19%).
- **By Country:**
- US & Spain favor Horror.
- Canada favors Action & Adventure
- Brazil favors Horror genres as well.
 
## 3. Montly Income vs. Subscription Plan
- No significant income difference in plan choice between men and women.
- **Average Montly Income:**
- Basic: Male - $404,6000 | Female - $390,200
- Premium: Male - $308,700 | Female - $304,300
- Standard: Male - $293,000 | Female - $287,300

**Recommendation:**
  - Consider tailored pricing or premoim features, but income doesnt strongly impact plan choice.
 
## 4. Retention & Renewal Insights
- **Renewal Rate:** 99.51% - high retention, indicating strong loyalty.
- **Retention Periods:**
    - 181-365 days: 74.56% retention.
    - >365 days: 25% retention.
    - >91-180 days: Only 0.68% retention.

**Seasonal Trends:**
- User join rates peak mid-year (June), with a slight decline toward year-end.

**Days Since Join:**
- Most users are retained between 

  
  

My questions are based on getting to know subscribers, such as the highest number of subscribers based on their country of residence. I was also curious to identify viewing patterns based on gender preferences.
Not to mention if income affects the subscription plans and methods. Lastly retention rate by measuring how well does or doesn't retain its users over time.
Which I thought would be a great insight for a marketing team, content recommendations, and improving retention.

## Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- Tableau (for interactive dashboards)
- Jupyter Notebook

## Tableu Public Dashboard: 
Tableau Public Dashboard 1: https://public.tableau.com/app/profile/dinara.ibotova/viz/NetflixProject-AnalysisofMonthlyIncomebySubscriptionMethodandGender/Dashboard1?publish=yes
Tableau Public Dashboard 2: https://public.tableau.com/app/profile/dinara.ibotova/viz/NetflixProject-NetflixDashboard2outof2/Dashboard2?publish=yes

## Next Steps
- Explore marketing campaigns to drive Premium plan adoption in slect countries.
- Keep doing user genre insights for personalized content recommendations.
  
## Conclusion
In this project I have demonstrated the value of analyzing user behavior to drive strategic decision in marketing, content, and retention. By understanding user preferences and engagement patters, Netflix can better service its diverse audiences.

## References
- [Kaggle Data] (https://www.kaggle.com/datasets/chul24/data-neflix/data)
