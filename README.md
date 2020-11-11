# Women in the Workforce Data Science Design Document
An exploration of female experiences in the workforce :fireworks:

## Table of Contents
1. Introduction

2. Problem Statement: Data Science Scope
    - Key User Stories
 
3. Data

4. Analytic Methodologies
    - Model 1

5. Training and Tuning

6. Testing
      
    






## 1. Introduction
This project is aiming to explore and analyze the experiences of women in the workforce, whether that be during interviews, in the workplace, participation, wage gaps, leave policies, or other factors. 


## 2. Problem Statement: Data Science Scope
This project is geared toward reaching users of all genders that are looking for insight into the current state of female participation in the workforce, in order to raise awareness of deficits in certain areas and specify the areas in which females are underrepresented, discriminated, or have difficulty succeeding in. This will not only be a benefit to the current female workforce, but also for the incoming generation of female employees and employers to be able to understand their position in the workforce. 

  - **Key User Stories**: Specifically, this project will be of use to a plethora of users, some of which being
    - Job recruiters who are looking for recurring hiring patterns when it comes to gender discrimination or what the process generally looks like for women who are entering the workforce, which industries or locations to focus their efforts
    - Women who are entering the workforce looking for the distribution of male versus female employees in their states/counties, which industries they would be the most likely to suceed in, how likely they are to suceed in management positions
    - Political informants who want to understand federal or state policies are affecting gender disparities in certain industries or locations, whether that is through wage gaps, discrimination, etc.
    - HR departments that are looking to understand the average gender distributions in their industry to use when considering promotions, benefits
    - Curriculum developers in high school who want to know which industries are lacking in female representation in order to provide specialized classes, such as in STEM


## 3. Datasets
1. https://www.kaggle.com/nicholasmarangi/job-patterns-for-minorities-and-women-usa?select=CountByNac4.csv
   - **Job Patterns For Minorities And Women USA**
   - Count of positions in the private sector based on location and industry '11-'18
   - Counts employees for each very specific industry and places them into buckets based on their race, gender, etc.
   - 268 columns
   
2. https://www.kaggle.com/jonavery/incomes-by-career-and-gender
   - **U.S. Incomes by Occupation and Gender**
   - Analyze gender gap and differences in industry's incomes
   
3. https://www.oecd.org/gender/data/
   - **OECD Gender Data Portal**
   

For later use

4. https://www.nltk.org/
   - **Natural Language Toolkit**
   - fairly simple and easy to use open source API to work with human language data
   - possibly using TF-IDF
   
5. https://developers.facebook.com/docs/graph-api
   - Use Graph API to scrape comments from posts on Facebook, run sentiment analysis on comments from female or male posts
   - Probably easier to do this with Twitter posts and comments
   - Is it possible to do this for LinkedIn?
   

## 4. Analytic Methodologies
**State Information**
- Total number of females in each industry (all positions) per state
- Total number of males in each industry (all positions) per state
  - Compare distribution of females vs. males
- Race distribution of females vs. males for each state (all positions)

**Industry Information**
- Total number of females in each industry (all states)
- Total number of females in each industry (all states)
  - Compare distribution of females vs. males
- Race distribution of females in each industry (all states)

**Position Information**
- Total number of females in each position for most common industries (all states)
- Total number of males in each position for most common industries (all states)
  - Compare distribution of males and females

Race Information
“”

Trend lines of female participation in workforce from 2011 - 2018
Should the other categories be separated by year for the totals


 

