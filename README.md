# Netflix User Behavior Analysis - Streaming Media & Subscription Analytics
![BrandAssets_Logos_01-Wordmark](https://github.com/user-attachments/assets/b7dea815-4fd7-4fe4-81b4-65cf637db819)

Subscription Patterns, Content Preferences & Retention Insights

Analyzed Netflix user data to understand what keeps subscribers engaged, what content they watch, and how different demographics choose subscription plans. Found some surprising patterns in genre preferences and incredibly high retention rates.

**Dataset:** Kaggle Netflix Data: https://www.kaggle.com/datasets/chul24/data-neflix/data

## Key Objectives
**Subscription Behavior:**
• Which countries have the most subscribers and what plans do they choose?
• Does income actually affect which plan people pick?

**Content Preferences:**
• What genres do men vs women prefer?
• Are there regional differences in content taste?

**User Retention:**
• How many people actually renew their subscriptions?
• What's the typical retention period?
• Any seasonal patterns in sign-ups or renewals?

## Key Findings
**Subscription Plans by Country**
Top 10 countries: Spain, United States, Canada, Brazil, UK, France, Italy, Australia, Mexico, Germany

- **Plan Preferences vary a lot:**
- - **Spain:** Standard and Premium plans dominate
  - **United States:** Pretty even split across all plans
  - **Canada, Brazil, Italy, Germany:** Mostly Basic plans
  - **France:** Heavy Premium adoption
  - **UK & Mexico:** Standard plans most popular

**What this means:** Premium uptake varies drastically by region. Some countries are willing to pay more while others stick to basics.

## Genre Preferences
**By Gender:**
• Women: Comedy (15%), then Horror, Drama, Action & Adventure
• Men: Horror (20%) and Action & Adventure (19%)

**By Country:**
• US & Spain: Horror fans
• Canada: Action & Adventure
• Brazil: Also big on Horror

**Income vs Plan Choice:**
Surprisingly, income doesn't strongly predict which plan people choose.

**Average monthly income by plan:**
• Basic: Men $404K | Women $390K
• Premium: Men $309K | Women $304K
• Standard: Men $293K | Women $287K

The differences aren't huge - plan choice seems driven more by perceived value than pure income level.

## Retention Metrics (The Good News)
**Renewal Rate: 99.51%** - Netflix has crazy high retention

**Retention by time period:**
• 181-365 days: 74.56% still subscribed
• 365+ days: 25% long-term subscribers
• 91-180 days: Only 0.68% (low early churn)

**Join patterns:**
• Peak sign-ups in June (mid-year)
• Slight decline toward year-end
• Most users stay between 250-400 days after joining

## Technical Details
**Data Source:** [Kaggle Data] (https://www.kaggle.com/datasets/chul24/data-neflix/data)

**Analysis Approach:**
• Data cleaning and preprocessing with pandas
• Statistical analysis of subscription patterns
• Genre preference segmentation by demographics
• Retention rate calculations and trend analysis
• Multiple visualization approaches (Python plots, Tableau, Power BI)

**Tools:**
• Python (pandas, matplotlib, seaborn)
• Jupyter Notebook
• Tableau Public
• Power BI

## Business Recommendations
1. **Regional Premium Push:** Countries favoring Basic plans (Canada, Brazil, Italy, Germany) could be targets for Premium upselling through exclusive local content or partnerships
2. **Gender-Specific Content Marketing:**
  • Promote Comedy content to women
  • Highlight Horror and Action to men
  • But these are just trends, we have to make sure these stereotypes is not overdone
3. **Regional Content Strategy:** We need to double down on Horror in US/Spain/Brazil, Action content in Canada
4. **Income Insight:** Since income doesn't strongly predict plan choice, we need to focus marketing on value and features rather than price sensitivity
5. **Maintain High Retention:** Whatever Netflix is doing to keep it up since we have 99.51% renewal rate which is very high.

## Current Limitations
• Dataset may not capture recent subscription model changes (with ads tier)
• Income data seems unusually high, might be a data quality issue worth investigating
• No info on actual viewing hours or content completion rates
• Limited to specific time period

## Next Steps
• Analyze whether Premium subscribers actually use Premium features (4K, multiple screens)
• Look at content completion rates by genre and demographic
• Study the small group (0.68%) who churn early to understand why
• Test targeted campaigns for Premium adoption in Basic-heavy markets

**Power BI Dashboard**
- PDF: https://github.com/Dinarauz/Netflix-Project-Analysis/blob/main/visualizations/Netflix.pdf

(link is private: https://app.powerbi.com/groups/me/reports/a04cd3cd-c542-45ce-881b-1a6def9db7f5/c46c1bbaaca4c8c8b135?experience=power-bi)

## Tableu Public Dashboard: 
Tableau Public Dashboard 1: https://public.tableau.com/app/profile/dinara.ibotova/viz/NetflixProject-AnalysisofMonthlyIncomebySubscriptionMethodandGender/Dashboard1?publish=yes
Tableau Public Dashboard 2: https://public.tableau.com/app/profile/dinara.ibotova/viz/NetflixProject-NetflixDashboard2outof2/Dashboard2?publish=yes

