# Kickstarting with Excel

## Overview of Project
A playwright has requested assistance in analysing fundraising trends to determine the best course of action to kickstart their theatre play production.

### Purpose
The purpose of the analysis was to assist a playwright who would like to fundraise $10,000 for their play. The playwright has asked for assistance in finding the best course of action based on past plays that initialized fundraising events. The goal was to assist the playwright on which factors will maximize their chances of having a successful fundraiser for their play *Fever*.

## Analysis and Challenges

A total of 4114 fundraising cases from various categories such as television, drama, documentary, theatre, amongst others were analyzed, although due to the nature of the project of the playwright, the focus was theatre. 

### Analysis of Outcomes Based on Launch Date

The first course of action was to create a `pivot table` to help narrow and visualize the outcomes of fundraising theatre projects based on launch date. This would help the playwright be aware of the best possible time to launch a fundraiser for their play. The pivot table below shows that spring-summer months, i.e May through July, were the times where most producers chose to start their fundraisers. The pivot table was used to produce a line graph named `Theatre Outcomes by Launch Date` to help better visualize the best time for launching. As shown on the graph below, summer months fundraisers had the highest possible chance of succeeding with May being the highest with a 67% chance of theatre fundraising projects succeeding. 

### Analysis of Outcomes Based on Goals

To further assist the playwright, the chances of success or failure was analyzed based on the goal amount of past play fundraisers. The following table and graph shows the percentage succeeded, percentage failed and percentage cancelled for a total of 1,047 plays depending on the asking amount for production. 


The `Outcome Based on Goal` graph shows that fundraisers less than $5,000 had over a 70% chance of succeeding. If the playwright would like an asking production price between $15,000 to $19,999, there is a 50-50 chance of succeeding or failing. As expected, the more the asking production price, the higher the chance of failure. The table and graph shows that an asking price range between $35,000 and $44,999 had a 67% chance of succeeding but a sample size of 9 fundraisers in this price range is too small to say how truly successful the fundraiser for the playwright client would be in comparison to the 750 projects that had asking prices below $5,000.

### Challenges and Difficulties Encountered

There were no challenges or difficulties when performing this particular analysis, however, if more analysis were to be done, it is possible that deciding which variables are the most important for the client would be difficult.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  1. Fundraisers launched in May have a higher chance of succeeding the goal
  2. December should be avoided as much as possible as a launch period due to the ~50% chance of failure

- What can you conclude about the Outcomes based on Goals?
  1. The lower the asking goal, the higher the chance of succeeding (~75%)

- What are some limitations of this dataset?
  1. The dataset is still relatively small.
  2. The country of launch would also have an effect on the chance of succeeding, failing or even cancelation

- What are some other possible tables and/or graphs that we could create?
  - Other tables (with an accompanying graph) include
    1. Play outcomes based on launch date
    2. Outcomes based on country of launch
    3. Percentage success based on goal
    4. Number of potential backers based on goal
    5. Average donation based on launch date (as a potential narrow down to outcome based on launch date)
