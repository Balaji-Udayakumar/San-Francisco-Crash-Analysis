# Accident Metadata for Enhanced Analysis

## Introduction
According to the Centers for Disease Control and Prevention (CDC), road traffic crashes are a leading cause of death in the United States for people ages 1-54. In San Francisco, there are over 30,000 collisions annually or over 80 per day, and these collisions have claimed nearly 4,000 lives in the last 18 years. The costs to society are staggering, with medical costs of $4.6 Billion and property damage of $2.8 Billion, not to mention the lost productivity impacting the economy.

## Project Overview
The Accident Analysis Avengers team aims to analyze two datasets that contain data from all crashes resulting in injury in San Francisco, California from 2005 to 2023. The mission of the project is to provide valuable information related to public safety, create predictive models to reduce the risk of collisions, and ultimately help the U.S. government make more informed decisions.

The desired outcomes of this project are to reduce the loss and risk of life due to avoidable collisions, minimize the health and economic impact on society, and guide infrastructure improvements and public policy decisions.

## Datasets
We were working with two datasets:

1. **Traffic Crashes Dataset (2005-2023)**: This dataset contains 56,010 incident records with over 3.3 million data points, including information on unique crash IDs, location, date and time, collision severity, weather, lighting, and road conditions.

2. **Parties Involved Dataset**: This dataset contains 118,087 detailed victim records with over 9.4 million data points, covering vehicle makes, models, manufacturing year, safety equipment in use during the collision, injuries sustained, and actions prior to the collision (text descriptions).

The connection between these two datasets allows Weto correspond fatality and injury outcomes to vehicle types and relate detailed party behaviors to incident locations and conditions.

## Key Questions of Interest
We aimed to answer the following three main questions:

1. Are there any geographic hotspots or any other patterns in collisions?
2. How do vehicle brands, their safety equipment, and their year of manufacturing affect collisions?
3. What is the best time of the year for the San Francisco Government to do construction so that the collision occurring on a particular road is of least severity?

## Data Cleansing
We performed key data cleansing tasks, including:

- Removing duplicates
- Dropping unnecessary columns
- Renaming columns for clarity
- Handling missing values
- Transforming DateTime column
- Ensuring consistency in categories

These actions increased the accuracy and reliability of the analysis, supported better visualizations and modeling, revealed early insights into data issues, and identified data collection gaps.

## Analysis and Findings

### Question 1: Are there any geographic hotspots or any other patterns in collisions?
The team's geographic analysis revealed a clustering of collisions in the downtown/central areas of San Francisco. This could be due to factors such as urban density, traffic volume, congestion, tourism, and pedestrian involvement, as well as infrastructure challenges. These findings underscore the need for safety improvements in high-risk areas and inform future urban planning and traffic management decisions.

### Question 2: How do vehicle brands, their safety equipment, and their year of manufacturing affect collisions?
The analysis showed a peak in collisions involving vehicles manufactured in the early 2000s. This could be attributed to the high volume of 2000s vehicles on the road, an aging vehicle fleet, lack of technological advancements, poor maintenance, and risky driver behavior. These findings may prompt policymakers and regulatory bodies to reevaluate safety standards for vehicles, and lead to public awareness campaigns about the regular maintenance of 2000s vehicles, as well as potential changes in insurance rates.

### Question 3: What is the best time of the year for the San Francisco Government to do construction so that the collision occurring on a particular road is of least severity?
The team's modeling approach revealed that factors such as the month, time of day, weather, and road surface conditions can significantly impact the severity of collisions. For example, the model showed that collisions on "NAPLES ST" and "EXCELSIOR AVE" are less severe during the months of January and December, compared to March, when the road surface is more likely to be slippery. This information can help the San Francisco government determine the best time to conduct road construction and maintenance to minimize the impact on collision severity.

## Recommendations and Conclusion
Based on the key findings, We have the following recommendations:

- The government can improve infrastructure and traffic systems to prevent collisions.
- Manufacturers can enhance safety standards and technologies in vehicles.
- Buyers can reference the safety record when purchasing vehicles.
- Reliance on technology (e.g., electric vehicles) is limited, and human behavior is critical in addressing the issue.
- The government can address infrastructure issues to reduce the number and severity of crashes.
- Collaboration is needed across organizations and individuals for a safer future.

In conclusion, the Accident Analysis Avengers team has provided valuable insights and recommendations to help reduce the loss and risk of life due to avoidable collisions, minimize the health and economic impact on society, and guide infrastructure improvements and public policy decisions.

## References
1. Centers for Disease Control and Prevention (CDC) - https://www.cdc.gov/
2. San Francisco Collision Data - https://data.sfgov.org/Public-Safety/Traffic-Collisions/zvj3-rsjt
