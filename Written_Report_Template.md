# Kickstarting with Excel

## Overview of Project

### Purpose
A client is launching a Kickstarter campaign in the category "theater" in Great Britain and wants to compare how different kickstarter campaigns fared in relation to their launch dates and their funding goals.

### About Kickstarter
Kickstarter is one of a number of crowdfunding platforms for gathering money from the public, which circumvents traditional avenues of investment. Project creators choose a deadline and a minimum funding goal. If the goal is not met by the deadline, no funds are collected.
Webpage: https://www.kickstarter.com/

### Analysis and Challenges
Analyzing the kickstarter projects based on their launch dates and funding goals will help the reader to take a decision on when to launch the project and how much to ask. 
Started working with kickastarter's raw data (csv file) from 2009 to 2017. I converted it to Excel format, cleaned the data and started running the analysis for projects in the "theater" category. 
Note: there are three main outcomes when a project is submitted in the platform:
- Succesful: a project was successfully funded before the deadline.
- Failed: the goal was not met by the deadline.
- Canceled: a project had to cancel the campaign before the deadline.

### Analysis of Outcomes Based on Launch Date
This analysis was made comparing the launch date of the projects in the platform. I wanted to see if launching the campaign in a specific month will have a higher rate of success.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/25446419/109434814-a7358280-79dc-11eb-91f5-f2c92ff11f2c.png)

### Analysis of Outcomes Based on Goals
This analysis was made comparing the funding goals of the projects. I wanted to see the success rate of the projects by dividing the funding goals in 12 categories and categorizing them into successful, failed and canceled projects.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/25446419/109434771-79503e00-79dc-11eb-91f2-ca5a5c969119.png)

### Challenges and Difficulties Encountered
In this case I found no challenge in the data. But the client may want to research more about the topic of the successfully funded theater projects

## Results
-  Conclusions of the Outcomes based on Launch Date
 - I recommend the client to launch the campaign in May (67% of success rate) or at least between February and September (average of 63% success rate).
 - I also reccomend not to launch the campaign between October and January because it has a 56% of success rate, December having the lowest success rate (49%).

- Conclusions about the Outcomes based on Goals
 - If the play needs low budget, I recommend to ask for a goal of less than $5,000 USD. If the play needs a lot of budget, I recommend to ask between $35,000 to $45,000 USD.
 - Both result above mentioned had an average of 70% success rate.

- What are some limitations of this dataset?
 - There is not a lot of information about the themes of the projects in the theatre category (it only includes plays, spaces and musicals). This information could let me create a better analysis comparing same theme projects with my client's project. 
 - It doesn't show any marketing information like marketing expenses vs funded goal or overall visits to the project vs actual backers, backers reached the campaign by organic or paid search.
 - It is missing number of perks (and amount per perk) offered by the project

- What are some other possible tables and/or graphs that we could create?
 - Add a filter to campaigns by countries.
 - Average donation of successful campaigns to analyze how much to ask per perk.
