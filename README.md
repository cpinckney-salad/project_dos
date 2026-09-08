
# Ventura-university-explorer

This dashboard compares 5 Ventura County area universities across financial outcomes, academic metrics and professor quality which combines federal education data with sources faculty ratings to give students an all-in-one view of their options.


<img width="789" height="842" alt="Screenshot 2026-09-08 at 8 58 05 AM" src="https://github.com/user-attachments/assets/68ffa41e-b65a-4169-b2d4-49b11f352006" />

<img width="789" height="754" alt="Screenshot 2026-09-08 at 9 03 12 AM" src="https://github.com/user-attachments/assets/d975efa7-8051-4f0f-8263-d96a250d1c74" />

<img width="789" height="754" alt="Screenshot 2026-09-08 at 10 17 15 AM" src="https://github.com/user-attachments/assets/022cd18f-0acc-4f3d-86b3-f776694ef21e" />

<img width="789" height="808" alt="Screenshot 2026-09-08 at 10 17 33 AM" src="https://github.com/user-attachments/assets/9ac275bc-6d0f-4910-af5d-9d39ed012e59" />



## Why I Built This
I made this project to bring the most important factors I considered when choosing a university into one place, including financial, academic, location and student outcome data. I wanted to make it easier to compare universities without having to search through multiple websites and sources to find the information I was looking for.

## How Its Made
I scraped data 5 schools in or near Ventura County, Cal Lutheran, CSUN, CSUCI, Pepperdine and UCSB. I collected faculty ratings for almost every teacher review at each school (500+ each school) and pulled form the U.S Department of Education's Collegscorecard (CSC) API to obtain detailed stats about each school like costs, graduation rates, debt and so much more. The final dataset included The scraped RMP data set, the CSC data set and additional engineered variables. Visually, I used several sources for inspiration, like data-to-viz.com help me decide how to portray each comparison and the Streamlit gallery for the overall aesthetic of the app. Learning how to apply CSS custom properties really opened my eyes on what I could create on Streamlit.



## Features
- Interactive Map
- Tuition comparison
- Graduation rates
- Retention rates
- Student debt
- 10 year earnings
- ROI comparison
- Professor ratings
-  Class difficulty ratings

## Data Sources
- College Scorecard API- U.S Department of Education
- RateMyProfessor Dataset- Crowdsources faculty ratings
