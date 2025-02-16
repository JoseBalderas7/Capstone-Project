cel# Capstone Project Case Study 2: How Can a Wellness Technology Company Play It Smart?

## Introduction
Hello my name is Jose and I will be taking on Case Study #2 How Can a Wellness Technology Company Play It Smart? for my Capstone Project

## Scenario

I am a junior data analyst working within the marketing analyst team at Bellabeat, a high-tech manufacturer of health-focused products for women. Bellabeat is a successful small company, but they have the potential to become a larger player in the global smart device market. Urška Sršen, cofounder and Chief Creative Officer of Bellabeat, believes that analyzing smart device fitness data could help unlock new growth opportunities for the company. I have been asked to focus on one of Bellabeat’s products and analyze smart device data to gain insight into how consumers are using their smart devices. The insights I discover will then help guide marketing strategy for the company. I will present my analysis to the Bellabeat executive team along with my high-level recommendations for Bellabeat’s marketing strategy.

## Company Information

Urška Sršen and Sando Mur founded Bellabeat, a high-tech company that manufactures health-focused smart products. Sršen used her background as an artist to develop beautifully designed technology that informs and inspires women around the world. Collecting data on activity, sleep, stress, and reproductive health has allowed Bellabeat to empower women with knowledge about their own health and habits. Since it was founded in 2013, Bellabeat has grown rapidly and quickly positioned itself as a tech-driven wellness company for women

By 2016, Bellabeat had opened offices around the world and launched multiple products. Bellabeat products became available through a growing number of online retailers in addition to their own e-commerce channel on their website. The company has invested in traditional advertising media, such as radio, out-of-home billboards, print, and television, but focuses on digital marketing extensively. Bellabeat invests year-round in Google Search, maintaining active Facebook and Instagram pages, and consistently engages consumers on Twitter. Additionally, Bellabeat runs video ads on Youtube and display ads on the Google Display Network to support campaigns around key marketing dates. Sršen knows that an analysis of Bellabeat’s available consumer data would reveal more opportunities for growth. She has asked the marketing analytics team to focus on a Bellabeat product and analyze smart device usage data in order to gain insight into how people are already using their smart devices. Then, using this information, she would like high-level recommendations for how these trends can inform Bellabeat marketing strategy.

### Ask
Sršen asks you to analyze smart device usage data in order to gain insight into how consumers use non-Bellabeat smart
devices. She then wants you to select one Bellabeat product to apply these insights to in your presentation. These questions
will guide my analysis:

What are some trends in smart device usage?

How could these trends apply to Bellabeat customers?

How could these trends help influence Bellabeat marketing?

I will be producing a report with the following deliverables:
1. A clear summary of the business task
2. A description of all data sources used
3. Documentation of any cleaning or manipulation of data
4. A summary of your analysis
5. Supporting visualizations and key findings
6. Your top high-level content recommendations based on your analysis

My objective is to examine FitBit smart device user data to discover trends, patterns, and connections within health-related metrics. This will help pinpoint growth opportunities and develop marketing strategies and recommendations for the Marketing department.

Key stakeholders include Urška Sršen, Bellabeat's cofounder and Chief Creative Officer; Sando Mur, Bellabeat's cofounder and mathematician; and the Bellabeat marketing analytics team.

### Prepare

For this analysis, the FitBit Fitness Tracker Data was used. This dataset, available on Kaggle by Mobius under the Public Domain Creative Commons License, this includes detailed records from thirty Fitbit users who consented to share their data. It provides minute-by-minute information on physical activity, heart rate, and sleep patterns, along with data on daily activities and steps, offering valuable insights into user habits and behaviors.
The FitBit Fitness Tracker data was collected in 2016, which means it may not accurately reflect current trends.

Moreover, the relatively small sample size of 33 could introduce bias. A larger sample would provide a more comprehensive view of the population and improve the accuracy of the results. Additionally, the absence of demographic details is a drawback. Given that Bellabeat focuses on women and menstruating individuals, having such data would have enhanced the robustness of the recommendations.

## Process 


I used Excel to clean and structure the datasets, and Tableau to generate visualizations from the processed data.
The dataset did not specify a unit of measurement for distance, so I assumed it was recorded in miles, given Fitbit's American origin. During the review, I identified 33 User IDs, while the dataset description mentioned only 30. Three of these IDs had fewer than 19 days of recorded activity, compared to an average of 29.9 days for the other users over the 31-day period. To maintain the integrity of the original data, I created a new file named procActiData.xlsx and removed the three outliers (2347167796, 4057192912, and 8253242879) to better align with the dataset description and enhance the quality of the analysis. I also verified that the data types for each column were consistent with their intended purpose.

## Analyze 

Throughout the dataset’s timeframe, three holidays were noted: Earth Day, Cinco de Mayo, and Mother's Day. On Earth Day, steps dropped by 0.15% compared to the average for Fridays, but there was a significant rise in Very Active minutes by 22.75% and Moderately Active minutes by 8.23%.

Cinco de Mayo saw a notable increase in activity, with steps up by 17.11%, Very Active minutes increasing by 12.76%, and Moderately Active minutes rising by 32.52% compared to the average for Thursdays. Conversely, on Mother's Day, steps rose by 2.47% and Moderately Active minutes increased by 16.67% compared to the average for Sundays. However, Very Active minutes saw a decline of 14.45%.

## Share 

During holidays, activity levels often rise, suggesting that social events encourage more movement. The Department of Health and Human Services recommends a minimum of 150 minutes of Moderate Activity or 75 minutes of Vigorous Activity per week. In this dataset, the typical user recorded 149.9 minutes of Very Active time and 94.4 minutes of Moderately Active time each week. This level of activity meets the recommended standards, indicating that users generally maintain a healthy level of physical exercise.

![capstonestudy2](https://github.com/user-attachments/assets/10759a6a-b550-446f-8da0-372039958a33)

## Act


The current Bellabeat audience is already active and compliant with health guidelines, so there might be value in reaching out to those who aren’t meeting these recommendations. Bellabeat’s unique product designs, such as the Leaf and Time, offer an alternative to conventional fitness trackers like Fitbit, which could appeal to people concerned about body image or social stigma by presenting these products as stylish, covert health monitors.

Furthermore, products like the Bellabeat Spring could be targeted more intensively toward the existing active user base, as these individuals are likely more interested in tracking their hydration levels. This strategy could cater effectively to the needs of a physically fit demographic.






