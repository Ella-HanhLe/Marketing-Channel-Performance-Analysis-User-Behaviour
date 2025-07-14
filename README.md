# Marketing-Channel-Performance-Analysis-User-Behaviour
1. Background

   This project analyzes user interaction data from a digital banking campaign to evaluate engagement effectiveness and identify opportunities for improvement. The analysis aims to support marketing and product teams in optimizing acquisition channels and enhancing user retention.

2. Dataset Description 
  
    We work with two raw datasets:
   
   - User data: 
     - Fields: User_ID, Age, Gender, Account_Type, Signup_Date, Channels
     - Description: Contains customer demographic and acquisition channel information.
     
   - Engagement_Logs
     - Fields: User_ID, Action_Date, Action_Type, Duration_Sec
     - Description: Logs user activity, including type and duration of actions over time.
3. Objectives
   
   - Identify high-performing acquisition channels
   - Measure 7-day user retention
   - Understand engagement behavior by age and gender
   - Provide data-driven recommendations for future campaign optimization
4. Tools Used
   
   - Microsoft Excel
   - Functions: VLOOKUP, IF, SUMIFS, DATEDIF
   - Pivot Tables
   - Data Visualization: Pie Charts, Bar Charts, Line Charts
5. What I Did
   
   - Cleaned and transformed raw data for analysis
   - Created calculated columns for age grouping and retention_ 7 days
   - Linked datasets via User_ID to analyze behavior patterns
   - Built pivot tables to segment data by acquisition channel and demographic groups
   - Designed visualizations to communicate engagement trends
   - Derived actionable insights and compiled them into a report
6. Key Insights
   
   - Referral Program contributed to 23% of new users and achieved a 7-day retention rate of 22.7%, comparable to that of           Zalo Ads and Facebook Ads.
   - Younger users (18–25) showed higher login frequency but lower average session duration compared to users aged 36+.
   - Female users were more consistent in daily engagement actions than male users across all age groups.
   - Email channel had the lowest retention performance, suggesting the need for more personalized or timely messaging.
7. Recommendations
   - Digital Campaign Effectiveness
     - Focus more on the Referral Program, as it brings in the most users and keeps them engaged well.
     - Keep running Zalo Ads and Facebook Ads, since users from these channels also stay active.
     - Consider reducing budget for Google Search, as it brings fewer users and they tend to drop off quickly
   - User Engagement
     
     We should align our comfort campaign with the timing and behavior of each target segment. It would be better if we launch a comfort-focused campaign targeting two key age groups:
     - For users aged 45 and above, who typically spend more time in the app, the focus should be on providing dedicated support and fostering loyalty through simple, trustworthy experiences.
     - For females aged 25–44, we should boost engagement by offering timely promotions through relevant channels, tailored to their expectations and built on their existing trust in our services.
   - User Action type
     - Since Fund Transfers lead in frequency, this feature should remain a top priority for performance, security, and UX optimization.
     - High login frequency implies users check the app regularly — a great opportunity for personalized in-app promotions or nudges.
