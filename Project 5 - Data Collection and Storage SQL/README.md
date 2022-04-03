# Analyze the passenger preferences and the impact of external factors on rides
## Project description
You work as an analyst for Zuber, a new ride-sharing company that's launching in Chicago. Your task is to find patterns in the available information. Your job is to understand passenger preferences and the impact of external factors on rides.
Working with a database, you'll analyze data from competitors and test a hypothesis about the impact of weather on ride frequency.
Description of the data

## Table of contents
- 1. Data Description
- 2. Technology Used
- 3. Steps to follow
- 4. Goal

## 1. Data Description
## The dataset contains the following fields:
— Name
— Platform
— Year_of_Release
— Genre
— NA_sales (North American sales in USD million)
— EU_sales (sales in Europe in USD million)
— JP_sales (sales in Japan in USD million)
— Other_sales (sales in other countries in USD million)
— Critic_Score (maximum of 100)
— User_Score (maximum of 10)
— Rating (ESRB)
Data for 2016 may be incomplete.

## 2. Technology Used
Python
Jupyter Notebook
Pandas
Numpy
Matplotlib
Seaborn
Plotly

## 3. Steps to follow
#### Step 1. Open the data file and have a look at the general information.
File path: /datasets/games.csv . Download dataset
#### Step 2.  Prepare the data
 - Replace the column names (make them lowercase).
 - Convert the data to the required types.
 - Describe the columns where the data types have been changed and why.
 - If necessary, decide how to deal with missing values:
        - Explain why you filled in the missing values as you did or why you decided to leave them blank.
        - Why do you think the values are missing? Give possible reasons.
        - Pay attention to the abbreviation TBD (to be determined). Specify how you intend to handle such cases.
 - Calculate the total sales (the sum of sales in all regions) for each game and put these values in a separate column.

#### Step 3 Analyze the data
 - Look at how many games were released in different years. Is the data for every period significant?
 - Look at how sales varied from platform to platform. Choose the platforms with the greatest total sales and build a distribution based on data for each year. Find platforms that used to be popular but now have zero sales. How long does it generally take for new platforms to appear and old ones to fade?
 - Determine what period you should take data for. To do so, look at your answers to the previous questions. The data should allow you to build a prognosis for 2017.
 - Work only with the data that you've decided is relevant. Disregard the data for previous years.
 - Which platforms are leading in sales? Which ones are growing or shrinking? Select several potentially profitable platforms.
 - Build a box plot for the global sales of all games, broken down by platform. Are the differences in sales significant? What about average sales on various platforms? Describe your findings.
 - Take a look at how user and professional reviews affect sales for one popular platform (you choose). Build a scatter plot and calculate the correlation between reviews and sales. Draw conclusions.
 - Keeping your conclusions in mind, compare the sales of the same games on other platforms.
 - Take a look at the general distribution of games by genre. What can we say about the most profitable genres? Can you generalize about genres with high and low sales?
#### Step 4 Create a user profile for each region
For each region (NA, EU, JP), determine:
 - The top five platforms. Describe variations in their market shares from region to region.
 - The top five genres. Explain the difference.
 - Do ESRB ratings affect sales in individual regions?
#### Step 5 Test the following hypotheses:
 — Average user ratings of the Xbox One and PC platforms are the same.
 — Average user ratings for the Action and Sports genres are different.
Set the alpha threshold value yourself.
Explain:
 — How do you formulate the null and alternative hypotheses
 — What significance level you choose to test the hypotheses, and why
 #### Step 6 Write a general conclusion
# 4. Goal
 - analysis of online video game data
 - identify patterns that determine whether a game succeeds or not
 - spot potential big winners and plan advertising campaigns

