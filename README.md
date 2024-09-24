#Redmi Treadmill Customer Analysis 
This document provides a concise analysis of the Redmi treadmill customer data set you provided. The analysis includes descriptive statistics, visualizations, and insights about customer demographics, product preferences, and usage patterns.

Data Acquisition and Exploration

The data was imported using pandas and explored using various functions like describe(), value_counts(), and boxplots.
Customer Demographics

There are three treadmill products offered by AeroFit: KP281, KP481, and KP781.
The dataset contains information about 180 customers, including:
Age
Gender
Education
Marital Status
Usage (frequency per week)
Fitness level (self-reported rating)
Income
Miles run
Most customers are between 24 and 33 years old.
The average customer uses the treadmill 3-4 days per week.
The average fitness rating is 3 (between average and good).
The average income is around $54,000 per year.
More customers are male (58%) than female (42%).
More customers are married/partnered (59%) than single (41%).
Product Preferences

KP281 is the most popular treadmill model (44%).
KP481 is the second most popular model (33%).
KP781 is the least popular model (22%).
Insights from Visualizations

Several visualizations were created using seaborn to explore relationships between variables:
Countplots revealed usage patterns, gender distribution, and product preferences.
Boxplots showed variations in age and usage across product types and fitness levels.
KDE plots (kernel density estimation) depicted income distribution and usage patterns by gender and marital status.
Scatter plots and jointplots explored relationships between age, gender, and fitness levels.
Partnered customers tend to use the treadmill more frequently than single customers.
Male customers generally have higher reported fitness levels than female customers.
Income distribution shows a spike between $40,000 and $80,000 per year.
Customers with higher education (16-18 years) tend to prefer the KP781 model.
Key Findings

KP281 is the most popular treadmill, followed by KP481 and KP781.
Partnered customers and males tend to use the treadmill more frequently.
Male customers generally report higher fitness levels than females.
There might be a connection between education level and preferred treadmill model.
Recommendations

Consider targeted marketing campaigns based on customer demographics (e.g., age, gender, marital status) and usage patterns.
Investigate the reasons behind the lower usage rates among single females and explore strategies to address them.
Research the motivations behind the preference for KP781 among customers with higher education.
Limitations

This analysis is based on a limited dataset (180 customers).
The data relies on self-reported information, which may not be entirely accurate.
Future Analysis

Conduct further analysis on factors influencing product preference, such as price, features, and marketing efforts.
Explore the relationship between fitness level and usage patterns.

