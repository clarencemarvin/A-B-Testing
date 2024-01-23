# A/B-Testing
This repository contains R code for preprocessing and analyzing A/B testing data from two groups: a control group and a test group. The objective is to compare key performance indicators (KPIs) between the two groups, specifically Click-Through Rate (CTR) and Conversion Rate (CR). Additionally, I provide visualizations to understand the impact of different metrics on the website performance. A/B testing is an iterative process. The insights gained from this round of testing should inform the design of subsequent experiments. The ultimate goal is to achieve an optimized balance of high user engagement with strong conversion rates, ensuring that clicks lead to revenue. A/B testing is not a one-time event but a continuous improvement tool that can help refine marketing strategies over time.

The analysis will process two CSV files as input:
- `control_group.csv` for the control group data.
- `test_group.csv` for the test group data.

The preprocessing steps include:
- Renaming columns for consistency.
- Checking for missing values and imputing them with mean values.
- Merging control and test data and sorting by date.
- Calculating CTR and CR for both datasets.

The following visualizations are generated:
1. Pie chart comparing the mean CTR between the control and test groups.
<img width="388" alt="Screenshot 2024-01-23 at 2 11 26 PM" src="https://github.com/clarencemarvin/A-B-Testing/assets/124359735/ad647d95-8ef4-4462-8539-d00601b6efe9">

2. Pie chart comparing the mean CR between the control and test groups.
<img width="401" alt="Screenshot 2024-01-23 at 2 11 15 PM" src="https://github.com/clarencemarvin/A-B-Testing/assets/124359735/0bcd831d-329b-4ef5-899d-85f9e916695b">

3. Scatter plots showing relationships between different metrics, with linear regression lines fitted to the data.
<img width="700" alt="Screenshot 2024-01-23 at 2 11 43 PM" src="https://github.com/clarencemarvin/A-B-Testing/assets/124359735/5384b38d-ee75-4f20-b781-b265ea66a53f">

<img width="704" alt="Screenshot 2024-01-23 at 2 11 58 PM" src="https://github.com/clarencemarvin/A-B-Testing/assets/124359735/a658cae3-c325-4729-b0ed-d5343c9b149f">

<img width="701" alt="Screenshot 2024-01-23 at 2 12 10 PM" src="https://github.com/clarencemarvin/A-B-Testing/assets/124359735/1bdc5406-c992-49ae-b0f8-128703efe7a7">


## The Purpose of A/B Testing Project

The purpose of this A/B testing analysis code is to provide marketers, data analysts, and decision-makers with clear insights into the performance of two different marketing campaign strategies: the control group (using existing marketing tactics) and the test group (where new strategies are applied). A/B testing is a powerful tool used in various industries to compare two versions of a product, advertisement, web page, or other marketing assets to determine which one performs better in terms of user engagement, conversion rates, and other key metrics.

In the real world, A/B testing guides companies in making data-driven decisions, optimizing user experience, and increasing the effectiveness of marketing efforts. For example, an e-commerce business may use this analysis to determine which website layout leads to more purchases, or a mobile app developer may identify which app interface yields higher user retention. By applying the insights gained from this analysis, businesses can improve their services, tailor their content to better match user preferences, and ultimately increase their return on investment (ROI).

This code facilitates the statistical analysis and visualization of A/B testing data, enabling a straightforward comparison of the outcomes from each group. By automating the analysis process, it saves time and reduces the potential for human error, allowing for a more efficient and accurate assessment of campaign performance.

## Conclusion
The A/B testing analysis conducted on the control and test campaign data provides valuable insights into user engagement and conversion efficiency. The key findings are as follows:

1. Click-Through Rate (CTR): The test campaign (lightblue) has a higher average CTR of 10.24% compared to the control campaign's (lightcoral) 5.09%. This suggests that the marketing strategy employed in the test campaign is more effective at encouraging users to click on the ads or links provided. A higher CTR can indicate more compelling ad copy, better targeting, or more engaging visuals.

2. Conversion Rate (CR): Interestingly, despite the test campaign's higher CTR, the control campaign (lightcoral) has a superior CR of 11.42%, while the test campaign (lightblue) has a CR of 9.23%. This indicates that while fewer users are clicking through the control campaign's ads, a larger proportion of those who do are completing purchases. This could suggest that the control campaign's audience is more aligned with the product or offering or that the user experience post-click is more optimized for conversion in the control campaign.

3. Scatter Plots: The scatter plots show that the relationships between 'Content Viewed' and 'Website Clicks', 'Added to Cart' and 'Content Viewed', and 'Purchases' and 'Added to Cart' are not linearly separable. This implies that there isn't a straightforward linear correlation between these variables in both campaigns. Such a finding suggests complex interactions between the variables that may require deeper analysis, possibly through multivariate testing or advanced statistical modeling.
