# Digital Marketing Campaign A/B Testing and Analysis
## Background and Overview
This project evaluates the effectiveness of diverse digital marketing campaigns by comparing engagement and click-through rates (CTR) across different audience segments using A/B testing. The objective was to determine whether specific variations in digital outreach had a statistically significant impact on these key metrics. This analysis leverages exploratory data analysis (EDA) and robust statistical testing (T-Test, Mann-Whitney U Test, and Cohen's d effect size) to derive actionable insights for optimizing future marketing strategies.

## Data Structure Overview
### The dataset includes:

***Campaign Channels:*** Email, Social Media, Paid Ads, SEO

***Audience Demographics:*** Age, region (North America, Asia, Europe, Australia)

***Engagement Metrics:*** Engagement rate, click-through rate (CTR)

***Device Types:*** Mobile, desktop, tablet

Key Data Points:

***Age Distribution:*** Skewed towards a younger audience (20-40 years).

***Channel Distribution:*** Heavy reliance on email (50%) and social media (30%), with lesser usage of paid ads (15%) and SEO (5%).

***Regional Focus:*** Majority of recipients from North America, followed by Asia and Europe.





### Insights and recommendations are provided on the following key areas:

Engagement rate trends by demographic (age, region, and device type)
Campaign channel distribution and performance
Targeted A/B testing strategies for specific audience segments


## 3. Executive Summary
### Overview of Findings:

***1) No Significant Differences in A/B Test:*** Statistical tests (T-Test and Mann-Whitney U) showed no significant difference in engagement or CTR between Group A and Group B.  
  
![output](https://github.com/user-attachments/assets/2a3b5a00-134d-430a-bb06-9c58688a769d)
***2) Younger Audiences & Mobile Users Lead in Engagement:*** Audiences aged 20-40 and mobile users showed consistently higher engagement rates, particularly in social media campaigns.


![output (1)](https://github.com/user-attachments/assets/9729202d-d6f5-499a-8774-769b56e0e123)
***3) Imbalanced Channel Distribution:*** Email campaigns dominate marketing efforts (50%), while channels like SEO (5%) are underutilized.



### Trends

![output (4)](https://github.com/user-attachments/assets/7ed5f8f9-2de1-4141-84c1-0a94defa1387)
***1) Mobile Dominance:*** Engagement rates were consistently higher on mobile devices, suggesting that optimizing digital campaigns for mobile is crucial.


![output (2)](https://github.com/user-attachments/assets/ccf4d451-c20c-42e0-99f2-699f8a6bb647)
***2) Campaign Channel Effectiveness:*** Social media campaigns exhibited the highest engagement rates, especially among younger recipients.


![output (5)](https://github.com/user-attachments/assets/1f188721-1300-47c7-8ff3-0aafda6ebe42)
***3) Regional Trends:*** North American recipients drove the majority of engagement, followed by Asia.


![output (3)](https://github.com/user-attachments/assets/bdb29e5b-3030-47d5-bd5b-55c38df02de0)
***4) Click-Through Rate by Age:*** Younger recipients (20-40) had slightly higher click-through rates, especially on social media, showing better engagement with content targeted at this demographic.






## Insights Deep Dive

The A/B test results revealed that there was no significant difference in engagement or click-through rates between Group A and Group B. This suggests that the variations introduced in the test were not impactful enough to influence these key metrics.

Despite the lack of overall differences, the exploratory data analysis (EDA) identified several key insights:

Younger demographics (20-40 years) consistently showed higher engagement, particularly in social media campaigns, where CTR increased by 5% over other age groups.

Mobile users had a 10% higher engagement rate compared to desktop or tablet users, indicating the need to prioritize mobile optimization.

Campaign channel distribution was skewed towards email, which accounted for 50% of the campaigns, but social media had the highest engagement rates, suggesting that diversifying towards social media and paid ads could boost overall campaign performance.

## Recommendations

***1. Further Segmentation Analysis:*** The lack of significant overall differences suggests the need for deeper segmentation. Run A/B tests within specific segments (e.g., age group, region, or campaign channel). For example, younger audiences and mobile users showed higher engagement, so conducting targeted tests for these groups could reveal more actionable insights.  
- ***Metric: Target a 5-10% increase in engagement for mobile users and younger demographics by focusing campaigns on social media channels.***
  
***2. Refine Campaign Strategies:*** Given the 10% higher engagement rate on mobile devices, prioritize mobile-optimized content. Design marketing strategies tailored for mobile users, particularly through social media.  
- ***Metric: Increase overall mobile engagement rates by 5% through better mobile content optimization.***
  
***3. Run Channel-Specific A/B Tests:*** Since the current A/B test did not reveal significant differences, consider running separate tests for email vs. social media, or testing different content formats (e.g., videos, GIFs) within the same channel to determine what resonates best.  
- ***Metric: Aim to increase CTR by 3-5% across underperforming channels like SEO and Paid Ads.***
  
***4. Diversify Marketing Channels:*** The heavy reliance on email campaigns (50% of total campaigns) suggests the need for channel diversification. Allocate more resources to underutilized channels like Paid Ads and SEO, which could provide new opportunities for engagement.  
- ***Metric: Increase social media campaign share from 30% to 40% while reducing reliance on email by 10%.***
  
***5. Explore Advanced A/B Testing Techniques:*** The lack of impact in the current A/B test suggests that more subtle changes (e.g., content personalization, messaging) should be tested using Bayesian A/B testing, which could provide more granular insights into audience behavior.  
- ***Metric: Detect smaller, statistically significant changes in engagement rates (1-2%) by running Bayesian A/B tests.***

## Limitations of the Analysis
***Data Distribution:*** Engagement and CTR might not follow a normal distribution, limiting the interpretation of parametric tests (like the T-Test). While non-parametric tests (Mann-Whitney U) were used, they offer less precise insights into the magnitude of differences.

***Sample Imbalance:*** The dataset was skewed towards younger audiences and heavily dependent on email campaigns, which could introduce bias and affect the generalizability of the results.

***Single-Test Context:*** The A/B test was conducted under specific conditions, and results may vary under different contexts (e.g., different timeframes or content types).

***Lack of Granular Segmentation:*** This analysis did not account for demographic or regional differences in engagement, which could mask important trends.


### Future Work
1. In-depth Segmentation Analysis: Perform further A/B tests on age groups, regions, and device types to identify variations that may not have appeared in the overall analysis.
   
2. Longitudinal Study: Monitor engagement rates over a longer period to assess the impact of market trends or seasonal changes on campaign effectiveness.
   
3. Advanced Metrics: Introduce other performance metrics, such as conversion rate, customer lifetime value (CLV), and return on investment (ROI), for a more comprehensive evaluation of campaign effectiveness.
  
4. Bayesian A/B Testing: Implement Bayesian methods to analyze differences between segments with more nuance, particularly in future campaigns.
