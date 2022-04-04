# Market Research to open a small robot-run cafe in LA area
## Project description
We’ve decided to open a small robot-run cafe in Los Angeles. The project is promising but expensive, so we (and our partners) have decided to try to attract investors. They’re interested in the current market conditions—will you be able to maintain your success when the novelty of robot waiters wears off?
As an analytics guru, our partners have asked to prepare some market research. We have open-source data on restaurants in LA.

## Table of contents
- Data Description
- Technology Used
- Steps to follow 
- Goal

## 1. Data Description

- rest_data table:

- object_name — establishment name
- chain — chain establishment (TRUE/FALSE)
- object_type — establishment type
- address — address
- number — number of seats

## 2. Technology Used
Python
Jupyter Notebook
Pandas
Numpy
Matplotlib
Seaborn
Plotly

## 3. Steps to follow
#### Step 1. Download the data and prepare it for analysis
Download the data on restaurants in LA. Make sure that the data type for each column is correct and that there are no missing values or duplicates. Process them if necessary.
File path: /datasets/rest_data_us.csv. Download dataset
#### Step 2. Data analysis
- Investigate the proportions of the various types of establishments. Plot a graph.
- Investigate the proportions of chain and nonchain establishments. Plot a graph.
- Which type of establishment is typically a chain?
- What characterizes chains: many establishments with a small number of seats or a few establishments with a lot of seats?
- Determine the average number of seats for each type of restaurant. On average, which type of restaurant has the greatest number of seats? Plot graphs.
- Put the data on street names from the address column in a separate column.
- Plot a graph of the top ten streets by the number of restaurants.
- Find the number of streets that only have one restaurant.
For streets with a lot of restaurants, look at the distribution of the number of seats. What trends can you see?
- Draw an overall conclusion and provide recommendations on restaurant type and the number of seats. Comment on the possibility of developing a chain.
-
#### Step 3. Preparing a presentation

Make a presentation of your research to share with investors. You can use any tool you’d like to create it, but you must convert your presentation to PDF format for assessment. Include a link to the presentation in a markdown cell in the following format:
Presentation: <link to cloud storage> 
## 4. Goal
- utilize open-source data on restaurants in LA
- analyze on food establishments to recommend on restaurant type and the number of seats and the possibility of developing a chain


