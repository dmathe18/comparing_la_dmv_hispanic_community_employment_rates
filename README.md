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
* **Which region, if either, offers  better employment prospects for individuals of Hispanic ancestry?** Quantitative comparative analysis of the employment rate distributions for both geographical regions.s

## Data Answer

The images below were obtained using a combination of the Excel Pivot Tables and histogram chart features:

![alt text](https://github.com/dmathe18/comparing_la_dmv_hispanic_community_employment_rates/blob/main/DMV_employment_histogram.png)

![alt text](https://github.com/dmathe18/comparing_la_dmv_hispanic_community_employment_rates/blob/main/LA_employment_histogram.png)

#### What did the local employment environment look like in the DMV and Los Angeles County areas in the years covered in the dataset?

The histograms linked above indicate that employment rates were concentrated around the (.7516, .7896) and (.7896, .8276) bands for the DMV region. In other words, most cities/counties/localities had employment rates for hispanic individuals that fell within this range. The histogram with Los Angeles's employment rates appears to tell a similar story, with most data points falling within the .7543, .7683) and (.7683, .7823) ranges. Taking an aerial view of the data, it appears that both data sets offer similar means, although the LA dataset appears to display considerably more variation, as discussed below.


#### Which geographic location appears to display the greater spread (variance) in employment outcomes for Hispanic individuals?

As briefly mentioned above, the LA distrubution appears to offer a much wider range of potential values. The lowest data point falls below .4 while the highest falls in a band with a lower bound of .95. Also worth noting is the normality of the distribution and apparent lack of skew in either direction. Kurtosis (tail thickness) appears to be highest in the DMV distribution. 

#### Which region, if either, offers  better employment prospects for individuals of Hispanic ancestry?

Based on the graphs and subsequent analysis, the LA county area appears to offer slightly better employment prospects for individuals of hispanic descent. This is because the mean employment rate is higher,and because there is a higher concentration of values around the mean, despite the distribution having the greater overall range.

## Data Interpretation
The data appears to suggest that LA county offers better employment prospects for individuals of hispanic descent. The analysis should be qualified by the fact that a variety of confounding variables may be impacting the findings, and employment rates alone do not categorically define the quality of employment or say anything about income, quality of life, happiness, etc. I think in-depth statistical and graphical analyses of important social and economic outcomes are and will become increasingly important, and provide a useful metric of comparison by which to analyze progress, performance, and effectiveness of a variety of political policies and governmental initialtives.

This analysis was of particular importance to me and my career path in that involved a granular analysis of employment statistics in two major regions- Southern California and the DMV region- which allowed me to gain a different perspective on the process of analysis and forecasting common among researchers in Economics. The analysis dovetailed with a similar ongoing project I am working on for a class called Macroeconomic Strategies in focusing on analyzing past trends to shed light on future outcomes. I definetly feel more certain in my ability to efficiently and effectively analyze large data sets from sources including the St. Louis Federal Reserve and the Bureau of labor statistics using Excel. 

## Step-by-step Instructions for Excel Data Analysis

1. Access The Opportunity Atlas Database
2. Filter search results according to region of interest and population demographics
3. Download files to computer - files saved as CSV
4. Transfer data to Excel
5. Use table feature in the insert tab to create tables with data
6. Click Pivot Tables and create Pivot Tables on a separate sheet in workbook
7. Drag and drop names to rows field and employment rates to values field
8. Change value field settings from sum of values to average of values
9. Create histogram using integrated histogram feature
10. Label chart axes, titles, formats, etc.
