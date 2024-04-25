Git--- editor_options: markdown: wrap: 72 ---

# A sentiment analysis on different cities in Vietnam
## 

Group B - member: - Vu Nguyen - Tran Tue Nhi

## High-Level Goal

To create an interactive visualization of sentiment analysis across different cities in Vietnam based on headlines extracted from Reddit.

## Introduction

Our project aims to analyze and visualize the sentiments expressed in headlines pertaining to various cities in Vietnam, gathered via the Reddit API. This visualization will highlight regional sentiment trends and provide insights into local and regional perceptions on a range of issues. Understanding sentiment variations can help in identifying cities with more positive or negative perceptions, which can be critical for local governments, marketers, and policy-makers to address specific concerns or reinforce positive views.

The motivation behind this project is to utilize sentiment analysis as a tool to gauge public mood and opinion across different regions without conducting extensive surveys. Sentiment analysis allows for quick, automated interpretation of large volumes of text, making it an efficient method for understanding public sentiment. This project is particularly interesting because it combines geographical data visualization with natural language processing, offering a visually intuitive way of presenting sentiment data.

We will use the Reddit API to crawl headlines from city-specific subreddits or those containing city names as keywords. After collecting this data, we will employ the VADER sentiment analysis tool to classify these headlines into positive, negative, and neutral categories. This choice is driven by VADER’s proficiency in handling social media text, which often contains slang and abbreviations that traditional sentiment analysis tools might not process accurately.

## Weekly Plan:

Week 1 [Vu Nguyen]:

Tasks: Set up the Reddit API for data extraction. Focus on collecting headlines from subreddits related to Vietnamese cities.

Objective: To finalize the list of city-specific subreddits and start the data collection process.

Week 2 [Tue Nhi]:

Tasks: Begin preliminary data cleaning and setup the VADER analyzer to start sentiment analysis on the collected headlines.

Objective: To classify the collected headlines into sentiment categories and prepare the data for visualization.

Week 3 [Vu Nguyen]:

Tasks: Design and implement the choropleth map using R. This involves mapping sentiment scores to corresponding cities and creating the interactive map interface.

Objective: To have a working prototype of the map ready for initial testing and review.

Week 4 [Tue Nhi]:
Tasks: Refine the visualization based on feedback. Improve interactive features and ensure the map is user-friendly.
Objective: To finalize the interactive choropleth map and prepare for presentation.

Week 5 [Both Members]:

Tasks: Prepare the final presentation and document the project. Review the entire workflow and ensure all components are integrated seamlessly.

Objective: To effectively communicate the findings and demonstrate the utility of the visualization in understanding regional sentiments.
