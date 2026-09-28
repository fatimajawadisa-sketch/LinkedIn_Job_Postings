# Linkedin job postings analysis(2023-2024) #

## Overview ##
this project analyzes the linkedin job postings dataset (124,000)postings to answer three research questions aimed helping job seekers-especially recent graduates make data driven decisions instead of guessing.


## The problem statement: ##
Between 2023_2024,the 124k job advertisements were posted on LinkedIn in the United States; 
69% required an intermediate level of experience, while only 31% were suitable for recent graduates.
this disparity results in  job seekers spending time applying for positions for which they do not qualify.


Data source:(postings.csv.zip)

## The 7 research questions ##

### Q1: what are the most in demand jobs in the market: ###
the code counts the repetition of each job title in the data, then charts the top 15 job titles in a horizontal bar chart.

#### importance: ####
it gives job seekers a clear visual map of the most in demand positions.

### Q2: which jobs accept beginners: ###
the code filters the data to include only entry-level and Internship job postings, then identifies the most frequently repeated job titles.

#### importance: ####
it saves time and effort for new graduates and increases their chances of acceptance.

### Q3: which city should  choose based on my specialization: ###
the code searches for a specific specialization e.g(software engineer) and ranks cities based on the number of available opportunities for that specialization.

#### importance: ####
it addresses the geographic distribution issue for anyone willing to relocate by pinpointing which city has the highest demand for their specialization.

### Q4: Which companies hire the largest number of entry-level employees: ###
We filter the data to include only "Entry-level/Internship" ads, then count which company posted the highest number of them.

#### importance: ####
The recent graduate is provided with a specific list of companies to target for research and follow-up, rather than applying indiscriminately to hundreds of companies.
### Q5: on which day of the week are the highest number of jobs posted: ###
We convert the publication date into the day of the week and count how many advertisements were published on each day.
 
#### importance: ####
It is beneficial for job seekers to know the best time to follow up on the latest opportunities.

### Q6: How many days does the job posting remain active before it expires: ###
We calculate the difference in days between the publication date and the expiration date for each advertisement.

#### importance: ####
It gives the job seeker an idea of ​​the time available to apply before the advertisement expires.

### Q7: What is the expected salary for each experience level (entry-level, mid-level, manager, executive...): ###
We calculate the median annual salary for each experience level (entry-level, mid-level, manager, executive).

#### importance: ####
A job seeker provides a realistic salary range—based on their level of experience—to negotiate from, rather than relying on guesswork.



## Requirements ##
import pandas as pd
import matplotlib.pyplot as plt

## Recommendation ##

Target beginner-friendly jobs:Titles like Retail Sales Associate, Receptionist,  have many entry-level openings.
Apply early: Most job postings stay active for only 30 days.
Check LinkedIn on Thursday and Friday: About 67% of jobs are posted on these two days.

## Next Step ##
Analyze job descriptions: Extract required skills from the descripting text to show beginners what to learn for each title. 


