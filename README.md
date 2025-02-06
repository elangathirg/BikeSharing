# BikeSharing
CASE STUDY FOR REGRESSION ANALYSIS - BY UPGRAD
## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

Objective: Develop a robust multiple linear regression model to accurately predict the demand for shared bikes, using provided independent variables.
Purpose: This model will empower management to understand Demand drivers like identifying the key factors that influence bike-sharing demand.
Also provide the management a suggestion on how demand fluctuates in response to variations in these key features.
Provide actionable insights crucial for strategic decision-making and optimizing resource allocation, particularly when entering new markets.

Target: A reliable, predictive model that enables data-driven decision-making, improving demand forecasting, resource management, and overall business performance.

Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Conclusions

Model Performance: R-squared: 0.801 → The model explains 80.1% of the variance in bike rentals (cnt), which is quite strong.

Season (+508.16, p=0.000) → Bike rentals increase in seasons likely summer and fall.
Year (+2047.06, p=0.000) → Rentals increased significantly in 2019 compared to 2018. So the trend indicates the positive inclination for the service in the future.
Holiday (-518.47, p=0.010) → Fewer rentals on holidays and Weekday (+69.19, p=0.000) → Higher rentals on weekdays. So the conclusion is users adopt Bike sharing for office commute.
Weather Situation (-610.46, p=0.000) → Worse weather conditions lead to significantly lower rentals.
Feeling Temperature (+72.20, p=0.023) → Higher perceived temperature increases rentals.

Total Count of Bike Rentals given by below equation of these independent variables:
cnt = 0.232 * yr + 0.058 * workingday + 0.575 * temp + 0.082 * summer + 0.139 * winter + 0.079 * mist + 0.303 * lightsnow + 0.103 * Sep + 0.065 * Sat + 0.011

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Python==3.12.4
json==2.0.9
pandas==2.2.2
platform==1.0.8
numpy==1.26.4
seaborn==0.13.2
statsmodels.api==0.14.2
statsmodels==0.14.2


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
This project was envisioned, assigned and assisted  by Upgrad and completed by Elangathir Gunasekaran (Email: elangathirg@gmail.com)
The Upgrade team structured this wonderful exercise, equipped was with good educational content and held in person assistance to clarify doubts 

## Contact
Created by [@Elangathir Gunasekaran] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
