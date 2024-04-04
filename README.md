# Medicare Claims Data Analysis for Injectable Anesthesia Drugs

This project focuses on analyzing Medicare claims data to gain insights into the injectable anesthesia market and develop strategies to optimize cannibalization and market share for a new drug variant called Midoride, while addressing challenges posed by a competitor's product, Fentirate.

## Project Overview

The project aims to address the following business problems:

- Cannibalization hurdle: Midoride, a new variant, was launched to absorb the declining sales of the leading brand Ketotrom, but it failed to cannibalize the market effectively.
- Competitive surge: The main competitor, Fentirate, is rapidly gaining market share, impacting the expected market share for Midoride.
- Territorial decline: Midoride's market penetration is showing a widespread decline across several key territories.

## Data Preparation

The Medicare claims data underwent a series of cleaning and preprocessing steps using Python. The following libraries were utilized:

- **pandas**: For data manipulation and analysis
- **numpy**: For numerical operations
- **re**: For regular expression operations

The data cleaning process involved:

1. **Handling Missing Values**: Identifying and addressing missing values in the dataset using appropriate techniques such as dropping rows or columns, or imputing values based on domain knowledge and statistical methods.

2. **Data Type Conversion**: Converting data types of relevant columns to ensure consistency and compatibility for analysis.

3. **Duplicate Removal**: Detecting and removing duplicate entries from the dataset to avoid data redundancy.

4. **Outlier Detection and Treatment**: Identifying and handling outliers in the data using statistical techniques like interquartile range (IQR) or domain-specific knowledge.

5. **Feature Engineering**: Creating new features or transforming existing ones to better represent the data and enable more meaningful analysis.

6. **Data Normalization**: Scaling or normalizing numerical features to ensure they are on a similar scale, improving the performance of certain algorithms.

7. **Regular Expression Operations**: Utilizing regular expressions to clean and standardize text data, such as provider names, drug names, or diagnosis codes.

After the data cleaning and preprocessing steps, the cleaned dataset was used for further analysis and modeling.

## Data Analysis

The data analysis covers the following aspects:

1. **Market Dominance**: Comparison of claim counts among injectable anesthesia brands, including Ketotrom, Fentirate, and Midoride, over three years.
2. **Product Penetration**: Annual analysis of healthcare professionals (HCPs) engaging in claim writing across product lines.
3. **Patient Reach**: Annual breakdown of product-specific patient count trends.
4. **Average Claim Cost**: Comparison of average claim costs for each brand.
5. **Provider Performance**: Analysis of claims and patient engagement metrics per HCP annually.
6. **Territorial Performance**: Identification of Midoride's bottom 5 performing territories by year-over-year claim percentage change.
7. **Comparative Analysis**: Comparison of Midoride and Fentirate's performance in target territories.
8. **Patient Conditions**: Unveiling the top 5 patient conditions driving the highest claim counts.
9. **HCP Specialties**: Breakdown of HCPs across key specialties prescribing anesthesia claims.
10. **Age Group Analysis**: Patient distribution and claim count percentage across age segments.
11. **Brand Loyalty and Expansion**: New HCP acquisition versus retention analysis for each brand.

## Recommendations

Based on the data analysis, the following recommendations are provided:

- **HCP Engagement Strategies** for the sales team, including performance-based incentives, strengthening Midoride in declining regions, allocating additional resources in Fentirate-challenged territories, revisiting training, formulary wins, and leveraging the success of Ketotrom's HCP engagement.
- **HCP Engagement Strategies** for the marketing team, such as strengthening relationships with HCPs, organizing seminars and webinars, creating peer-to-peer forums, establishing feedback channels, and using targeted ads and direct mail.
- **Patient Engagement Strategies** for the marketing team, including leveraging digital platforms, partnering with health and wellness websites, and providing patient assistance programs.

## Data Exploration Opportunities

The project also identifies opportunities for further data exploration, including:

- Detailed information on pricing, insurance coverage, and reimbursement levels for each drug.
- Surveys or studies on physician and patient preferences, reasons for drug selection, and satisfaction with the treatment.
- Sales deployment demographics for each territory.

Additionally, potential analyses are suggested, such as an affordability index, preference mapping, and physician segmentation.

## Getting Started

To explore the project further, access the provided files, including the data analysis and recommendations. The data cleaning and preprocessing scripts are available in the `data_cleaning` directory.
