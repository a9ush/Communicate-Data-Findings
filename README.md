# Communicate-Data-Findings
Udacity's Data Analyst Nanodegree - Project 5



### Dataset

Bay Wheels  is bike sharing system in the San Francisco. The dataset  consists of monthly individual trip data from year 2017 in CSV format covering the greater San Francisco Bay area.

### Data wrangling process:
fix multiple fields that are not in the correct dtype, i.e. start_time, end_time should be datetime type, user_type 
add new columns for trip duration in minute, trip start date in yyyy-mm-dd format, trip start hour of the day, day of week and month.
add a new column calculating riders' age from 'member_birth_year'
cast member_birth_year' and 'member_age' to integer instead of float type
cast 'start_dayofweek' to category dtype
cast 'start_month' to category dtype for easy plotting
filter out outlier trip records where the duration was very long


### Files
- readme.md - This Markdown file contains sections that you should fill out as you select your dataset, complete your exploration, and plan your explanatory analysis. 

- exploration_template.ipynb - This Jupyter Notebook contains section templates to help you organize your exploration, starting from loading in the data, working through univariate visualizations, and ending with bivariate and multivariate exploration. 

- slide_deck_template.ipynb - This Jupyter Notebook contains starter cells to help you organize your slide deck deliverable. These cells provide an example of how the slide deck should be organized, including pre-set slideshow settings.


