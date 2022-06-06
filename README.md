# Kickstarting with Excel

## Overview of Project
This project takes a deep dive into crowdfunding data to uncover trends in the theater industry to help Louise launch her own successful kickstarter campaign for her new play "Fever".    
### Purpose
The purpose of this analysis is to use the power of Excel and pivot tables to provide a better understanding of what makes a successfully funded campaign for a play in the theater industry. 
## Analysis and Challenges
https://github.com/Bropell/kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx 

Although there were many parameters to look at, this project specifically focuses on the outcomes of related kickstarters based on launch date and the funding goals. In one case, a pivot table is used to analyze outcomes and trends of theater kickstarters over the span of a year. For the other parameter, a new data table was populated and analyzed using a counting method in Excel with conditionals.  
### Analysis of Outcomes Based on Launch Date
This portion of the analysis was meant to find trends in theater kickstarters through the use of a pivot table. After filtering by parent category, which for this case was theater, row labels were filled with months of the year while the column labels were separated by the campaign status (successful, failed or canceled). The pivot table was then used to make a plot of theater outcomes based on the launch date. This plot shows the trends for successful, failed and canceled theater kickstarters over the course of a year which provides an excellent visualization of the data.
![alt text](https://github.com/Bropell/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)
### Analysis of Outcomes Based on Goals
This portion of the analysis was meant to find the outcomes based off a certain goal amount as a percentage. A new worksheet was created with different goal amounts in ranges. Using the COUNTIFS() function, several columns were populated with values for number successful, number failed and number canceled. These values were added together to find the total projects for a particular goal range and each outcome was determined as a percentage of the total projects. A plot was generated from the calculated percentages to provide a visual representation of the goal ranges with a higher percentage of successful campaigns and conversely, those with a higher percentage of failure.
![alt text](https://github.com/Bropell/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)     
### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
