# Advanced A/B Testing for Digital Campaign Success

## Objective 
To evaluate the effectiveness of diverse digital marketing campaigns by comparing engagement and click-through rates across different segments using A/B testing.

## Exploratory Data Analysis (EDA)
### Key Findings from EDA:

![output](https://github.com/user-attachments/assets/2a3b5a00-134d-430a-bb06-9c58688a769d)
Age Distribution: The data showed a skew toward a younger audience, with most recipients falling within the 20-40 age range, aligning with our target demographic for digital marketing campaigns.


![output (1)](https://github.com/user-attachments/assets/9729202d-d6f5-499a-8774-769b56e0e123)
Campaign Channel Distribution: The campaign channels were imbalanced, with 'Email' being the most frequently used (50%), followed by 'Social Media' (30%), 'Paid Ads' (15%), and 'SEO' (5%). This imbalance reflects typical marketing strategies, which favor email and social media for digital outreach.


![output (2)](https://github.com/user-attachments/assets/ccf4d451-c20c-42e0-99f2-699f8a6bb647)
Engagement Rate by Campaign Channel: Social media campaigns generally had higher engagement rates compared to other channels. Email campaigns also showed moderate engagement, particularly among older recipients.


![output (3)](https://github.com/user-attachments/assets/bdb29e5b-3030-47d5-bd5b-55c38df02de0)
Click-Through Rate by Age: Younger recipients showed slightly higher click-through rates, especially for social media campaigns, indicating better engagement with content tailored to younger demographics.


![output (4)](https://github.com/user-attachments/assets/7ed5f8f9-2de1-4141-84c1-0a94defa1387)
Engagement Rate by Device Type: Recipients using mobile devices had higher engagement rates than those on desktops or tablets, suggesting that mobile optimization is crucial for digital marketing efforts.


![output (5)](https://github.com/user-attachments/assets/1f188721-1300-47c7-8ff3-0aafda6ebe42)
Regional Distribution: The majority of recipients were from North America, followed by Asia, Europe, and Australia, indicating our primary market focus.

## A/B Test Setup and Hypotheses
**Objective:** To assess whether there is a statistically significant difference in engagement rates and click-through rates between two randomly assigned groups (Group A and Group B) over a 12-month period.

**Metrics for Comparison:**

1) Engagement Rate

2) Click-Through Rate

**Hypotheses:**

Null Hypothesis (H0): There is no significant difference in engagement or click-through rates between Group A and Group B.
Alternative Hypothesis (H1): There is a significant difference in engagement or click-through rates between Group A and Group B.

## A/B Testing Procedure
**Random Assignment:** Recipients were randomly divided into two groups: Group A and Group B.

**Statistical Tests Conducted:**
T-Test: To compare the mean engagement and click-through rates between the two groups.

Mann-Whitney U Test: A non-parametric test to compare the distributions of engagement rates and click-through rates between the groups, since the metrics might not follow a normal distribution.

Effect Size (Cohen's d): To quantify the magnitude of differences between the groups.

## A/B Test Results
### 1)T-Test Results

Engagement Rate: p-value = 0.582

Click-Through Rate: p-value = 0.478

Interpretation: Since the p-values are greater than 0.05, we fail to reject the null hypothesis for both engagement rate and click-through rate. This means there is no statistically significant difference between Group A and Group B.

### 2)Mann-Whitney U Test Results

Engagement Rate: p-value = 0.582

Click-Through Rate: p-value = 0.478

Interpretation: The Mann-Whitney U test also indicates no significant difference between Group A and Group B in terms of engagement and click-through rates.

### 3)Effect Size (Cohen's d)

Engagement Rate: Cohen’s d = -0.0019

Click-Through Rate: Cohen’s d = -0.0028

Interpretation: The effect sizes are very close to zero, indicating negligible differences between the two groups. This suggests that the changes introduced in the test had almost no impact on engagement or click-through rates.


## Insights and Recommendations
### Insights

No Significant Impact: The A/B tests showed no statistically significant difference in engagement or click-through rates between Group A and Group B, suggesting that the variations introduced did not result in measurable changes.<br/>

Demographic Engagement: Despite the overall lack of difference, the EDA showed that younger audiences and mobile users tend to have higher engagement rates. This implies that content tailored for these demographics might yield better results.<br/>

Channel Imbalance: The dataset shows an imbalance in campaign channels, with a heavy reliance on email marketing. Diversifying efforts to other channels, such as social media and paid ads, might provide more insights into their unique impacts.

### Recommendations

Further Segmentation Analysis: Since the overall A/B test did not reveal significant differences, segment the data further (e.g., by age group, region, campaign channel) to uncover potential variations within subgroups.<br/>

Refine Campaign Strategies: Focus on optimizing campaigns for younger audiences and mobile users, as they exhibit higher engagement.<br/>

Run Targeted A/B Tests: Conduct A/B tests within specific channels (e.g., email vs. social media) or demographics to better understand what works for each segment.<br/>

Explore Advanced Methods: Implement Bayesian A/B testing for a more nuanced analysis of differences, particularly in future campaigns.<br/>

Review Test Variations: The lack of impact in the current A/B test suggests that the variations introduced between the groups were not substantial enough to drive changes. Consider testing more distinct variations, such as different content formats, messaging, or personalized offers.<br/>

### Limitations of the Analysis

Data Distribution: The engagement and click-through rates may not follow a normal distribution, which limits the use of parametric tests like the t-test. Non-parametric tests were used to address this, but their interpretation can be less straightforward.<br/>

Sample Imbalance: The distribution of campaign channels and demographics (e.g., age skewed toward younger recipients) might introduce bias, limiting the generalizability of the results.<br/>

Single-Test Context: The A/B test was conducted under a specific set of conditions (e.g., timeframe, content type). Results might vary if tested in a different context or with different variations.<br/>

Lack of Granular Segmentation: The overall A/B test did not account for differences in engagement across specific channels, regions, or other demographics. Further analysis is needed to identify potential subgroup variations.<br/>

### Future Work
In-depth Segmentation Analysis: Perform A/B tests on specific segments (e.g., age groups, campaign channels) to uncover any hidden differences.<br/>

Longitudinal Study: Monitor the engagement rates and click-through rates over an extended period to understand trends and the impact of seasonal or market changes.<br/>

Additional Metrics: Incorporate other metrics such as conversion rate, customer lifetime value, and return on investment (ROI) for a more comprehensive evaluation of campaign effectiveness.<br/>

Implement Bayesian Analysis: Use Bayesian A/B testing to gain more insights into the probability and uncertainty of the observed differences, providing a more nuanced decision-making framework.
