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
There were several challenges encountered during this analysis that should be mentioned. One of the challenges was making sure the conditional statements for the COUNTIFS function was correct. Setting up the conditionals was not a problem but making sure the syntax was in order to pull from the correct places in the kickstarter sheet proved difficult at first. Overcoming this obstacle was as simple as ordering the conditionals in the COUNTIFS function in a way where the argument  changing for each row was in the same spot so the rest of the conditions remaining the same can be copied. From this point, the rest of the sheet was populated quickly including the other columns where you had to change a separate conditional. The take away here is that being organized can help save time and make things easier to understand. 
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

There are a couple conclusions that can be drawn here in terms of outcome based on launch date. The most obvious conclusion is that launching a kickstarter around May will have the highest chance of success. This is represented in the data by the large peak on the success line for that month. Conversely, launching a kickstarter around December will yield the lowest chance of success, shown by the dip in the success line for that month. Perhaps outside variables play into why the data is the way it is.

- What can you conclude about the Outcomes based on Goals?

In terms of outcomes based on goals, it seems as though a lower funding goal is the safe bet in hopes that the kickstarter is successful. As seen in the associated plot, there is the largest difference between success and failure with a goal of less than 1000 dollars. It may also be safe in the 1000 to 4999 range with a slightly lower chance of success. The data also shows a small window of higher success in the 35000 to 44999 range however, the kickstarter Louise wants to start plans for a goal of around 10000 dollars. Perhaps Louise can rework her plan to bring her goal down in order to ensure her success.  
- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
