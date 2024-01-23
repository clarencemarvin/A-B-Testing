# A/B-Testing
This repository contains R code for preprocessing and analyzing A/B testing data from two groups: a control group and a test group. The objective is to compare key performance indicators (KPIs) between the two groups, specifically Click-Through Rate (CTR) and Conversion Rate (CR). Additionally, we provide visualizations to understand the impact of different metrics on the website performance.
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
2. Pie chart comparing the mean CR between the control and test groups.
3. Scatter plots showing relationships between different metrics, with linear regression lines fitted to the data.

## The Purpose of A/B Testing Project

The purpose of this A/B testing analysis code is to provide marketers, data analysts, and decision-makers with clear insights into the performance of two different marketing campaign strategies: the control group (using existing marketing tactics) and the test group (where new strategies are applied). A/B testing is a powerful tool used in various industries to compare two versions of a product, advertisement, web page, or other marketing assets to determine which one performs better in terms of user engagement, conversion rates, and other key metrics.

In the real world, A/B testing guides companies in making data-driven decisions, optimizing user experience, and increasing the effectiveness of marketing efforts. For example, an e-commerce business may use this analysis to determine which website layout leads to more purchases, or a mobile app developer may identify which app interface yields higher user retention. By applying the insights gained from this analysis, businesses can improve their services, tailor their content to better match user preferences, and ultimately increase their return on investment (ROI).

This code facilitates the statistical analysis and visualization of A/B testing data, enabling a straightforward comparison of the outcomes from each group. By automating the analysis process, it saves time and reduces the potential for human error, allowing for a more efficient and accurate assessment of campaign performance.
