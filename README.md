# Cyclistic-Case-Study

## Background

This case study is the capstone project for the Google Data Analytics Certificate offered by Coursera. This particular project is focused on applying the data analysis process to make a data-driven decision in the context of designing a marketing strategy. Cyclistic is a fictional bike-share company and the marketing team is looking to develop a strategy to convert casual riders into annual members. The team wants to first understand how casual members and annual members use Cyclistic bikes differently. In order to do so, historical bike trip data from September 2020 to August 2021 is used to identify trends to better understand users and develop useful insights for marketing tactics. 

See the R Markdown for this project [here](https://github.com/kent-ts3/Cyclistic-Case-Study/blob/main/cyclistic_case_study_R_v2.Rmd).

## Key Findings
**1) Number of casual rides increase during weekends and member rides stay consistent throughout the week.**

**2) On weekends, number of casual riders is the highest in the middle of the day, peaking at 2PM. On weekdays, number of casual riders is highest in the late afternoon and evening, peaking at 5PM.**

**3) Ridership for both casual and annual members increase during spring, then peaks in summer, and decreases during fall and winter months.**

**4) Streeter Dr & Grand Ave station has the most trips by casual riders. Clark St & Elm St station has the most trips started by members.**

## Conclusion
The historical trip data shows that casual riders and members use the bikes differently. Casual riders tend to take trips during weekends and most frequently visit the Streeter Dr & Grand Ave station. Ride patterns of members appear to follow that of a commute to work with more activity during weekday mornings and the late afternoon. Overall, these insights provide a general overview of how riders use the bikes, however, there are limitations to this data. A potential next step could involve surveying riders to get a better understanding of rider psychology to create better targeted marketing campaigns.

### Recommendations
**1) Launch targeted marketing campaign around the beginning of spring and throughout summer when there is a higher volume of casual riders.**

**2) Show targeted ads during weekends and at the peak times from 11AM to  4PM when casual riders are more likely to use the bikes.**

**3) Display more ads at the following stations where the most casual riders start their trips:**
* Streeter Dr & Grand Ave
* Millennium Park
* Michigan Ave & Oak St

## About the programming and analysis
* Data wrangling and cleaning using R
* R packages used: tidyverse, lubridate, ggplot2, scales, leaflet
* Visuals created using R

### Data
* Historical trip data is provided by Motivate International Inc. under the following license: https://www.divvybikes.com/data-license-agreement
* The public data is made available [here](https://divvy-tripdata.s3.amazonaws.com/index.html).
