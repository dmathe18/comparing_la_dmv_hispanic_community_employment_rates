# comparing_la_dmv_hispanic_community_employment_rates
This repository contains original data, Excel analyses, and data visualizations of employment data from the Los Angeles and DMV areas for individuals of hispanic decent.

# Comparative Analysis of Employment Outcomes for Individuals of Hispanic Descent in Los Angeles and the DMV Area

## Background
With the U.S. hispanic population [on track to grow 86%](https://www.brookings.edu/blog/the-avenue/2018/03/14/the-us-will-become-minority-white-in-2045-census-projects/) in the next four decades, the impetus for data-driven analyses of employment outcomes among the Hispanic population has never been greater. As job opportunities in many of the fastest-growing industries increasingly require more than a high school diploma, comparative analyses of employment statistics among U.S. minority populations will become increasingly important and relevant to policymakers seeking to understand and address the underlying causes of [contemporary social issues](https://www.shrm.org/hr-today/public-policy/hr-public-policy-issues/Documents/15-0746%20CHCI_Research_Report_FNL.pdf) such as the skills gap, barriers to educational attainment, and discriminatory hiring practices that disproportionately impact communities of color.

Local, state, and federal leaders across the nation voice their support of policies, programs, and community-level initiatives seeking to build an economy that prioritizes those that have been left or kept behind, in theory. Subscribing to agendas that seek to [ensure education access, social mobility, and political voice](https://dornsife.usc.edu/assets/sites/1411/docs/USC_ERI_no-going-back_policy_report.pdf) for minority groups, these leaders strive to frame equity into policy and endorse various policies and programs that channel funds to bolster Latinx community resources. However, how can we assess the extent to which leaders are upholding their promises? What are some ways we can interpret the raw data on employment statistics to get a better sense of how our communities are performing in terms of offering employment opportunities to the Hispanic population? To begin exploring answers to these questions, we'll take a look at open data from [The Opportunity Atlas](https://www.opportunityatlas.org) containing statistics on employment rates for individuals of hispanic descent in cities and counties in the Los Angeles and Washington, D.C., Maryland, and Virginia (DMV) areas.


## Business Question

_**How do employment outcomes for individuals of hispanic ancestry in the Los Angeles County area compare with those of their counterparts residing in the DMV area?**_

## Data Question - Open Data

We'l use open data from the following source: 

1. **The Opportunity Atlas**: The Opportunity Atlas is an online, open-source social mobility database compiled by researchers at the Census Bureau and Opportunity Insights (a research and policy group based at Harvard University). The Opportunity Atlas contains anonymous data following 20 million Americans from childhood to their mid-thirties and allows users to filter search results based on geographical location, outcomes, and demographic groups. We will use two datasets from this study:
   1. [Employment Rate Data for Hispanic Individuals in the Greater Los Angeles Area](https://github.com/dmathe18/comparing_la_dmv_hispanic_community_employment_rates/blob/main/LA_original_data.xlsx
): this dataset contains over 2,500 observations with information on employment rate data for more than 350 cities, counties, and subsidiary localities in the greater Los Angeles area. 
   2. [Employment Rate Data for Hispanic Individuals in the DMV Area](https://github.com/dmathe18/comparing_la_dmv_hispanic_community_employment_rates/blob/main/DMV_original_data.xlsx): this dataset contains over 120 observations with information on employment rate data for more than 100 cities, counties, and subsidiary localities in the DMV area. 
   
## Data Question - Analysis

We’ll use Microsoft Excel to answer:

* **What did the local employment environment look like in the DMV and Los Angeles County areas in the years covered in the dataset?** Obtaining a birds-eye view of the employment landscape for the Hispanic community using Excel Pivot Tables and labeled histograms.
* **Which geographic location appears to display the greater spread (variance) in employment outcomes for Hispanic individuals?** Analyzing the visualizations for statistical insights such as variance, range, skew, kurtosis, etc.
* **Which region, if either, offers  better employment prospects for individuals of Hispanic ancestry?** Quantitative comparative analysis of the employment rate distributions for both geographical regions.

## Data Answer

The images below were obtained using a combination of the Excel Pivot Tables and histogram chart features:

![alt text](https://github.com/dmathe18/comparing_la_dmv_hispanic_community_employment_rates/blob/main/DMV_histogram.png)

#### What did the local employment environment look like in the DMV and Los Angeles County areas in the years covered in the dataset?

![](.gitbook/assets/university-tier-counts.png)

Here we can see that two-year public and private higher education institutions make up most of the volume of colleges in the US, followed by "selective private" and "selective public" schools. As we might expect, there are very few "Ivy Plus" schools \(highly selective and highly ranked\), "other elite" schools \(including Johns Hopkins\), and "highly selective" public and private schools \(perhaps less than one per state\). This gives us an idea of the type of quantitative impact that education or admissions reform might have based on what type of institutions the reform focuses on.

#### Which geographic location appears to display the greater spread (variance) in employment outcomes for Hispanic individuals?

![](.gitbook/assets/final-chart.png)

Here we see almost an opposite type of distribution--the highly selective private schools have the highest sticker price, and the two-year not-for-profit institutions have the lowest sticker price. We should also note that the sticker price also does not necessarily reflect the price that students need to pay to attend the institution, however, it can give us insight into the type of students who attend those schools and who don't receive financial aid. Additionally, highly selective public schools have a significantly lower sticker price than their peer institutions, so this may indicate that students could get a better "bang for their buck" here if the student outcomes are similar to peer institutions. 

#### Which region, if either, offers  better employment prospects for individuals of Hispanic ancestry?

![](.gitbook/assets/parent_income_dist_by_tier.png)

We can also look at the average income distribution at the different higher education tiers where Q1 indicates families in the lowest income quintile and Q5 indicates families in the highest income quintile. We can see that the income distribution starts to even out when we look at nonselective four-year colleges and that elite and other highly selective institutions are predominantly filled with students from the highest income quintile.

