Git--- editor_options: markdown: wrap: 72 ---

# A sentiment analysis on different cities in Vietnam
## 

Group B - member: - Vu Nguyen - Tran Tue Nhi

## High-Level Goal

To create an interactive visualization of sentiment analysis across different cities in Vietnam based on headlines extracted from Reddit.

## Introduction & Motivation

Our project aims to analyze and visualize the sentiments expressed in headlines pertaining to various cities in Vietnam, gathered via the Reddit API. This visualization will highlight regional sentiment trends and provide insights into local and regional perceptions on a range of issues. Understanding sentiment variations can help in identifying cities with more positive or negative perceptions, which can be critical for local governments, marketers, and policy-makers to address specific concerns or reinforce positive views.

The motivation behind this project is to utilize sentiment analysis as a tool to gauge public mood and opinion across different regions without conducting extensive surveys. Sentiment analysis allows for quick, automated interpretation of large volumes of text, making it an efficient method for understanding public sentiment. This project is particularly interesting because it combines geographical data visualization with natural language processing, offering a visually intuitive way of presenting sentiment data.

## Approach method
We aim to effectively present the sentiment analysis results through a choropleth map designed in R. This map will visually display sentiment variations across Vietnamese cities using color gradients to indicate the intensity of sentiments. The hues will range from dark (representing more negative sentiments) to light (representing more positive sentiments), providing an intuitive view of emotional landscapes.

The choropleth map will be integrated into a broader, interactive dashboard. This dashboard will enable users to adjust time frames, allowing them to explore how sentiments across various cities have changed over time. This functionality is intended to be able extract even deeper understanding and knowledge by providing dynamic insights into regional emotional trends.

## Dataset

We will utilize the Reddit API to extract headlines from city-specific subreddits and those containing city names, incorporating a time-filter to track sentiment changes over different periods. Data will be classified using the VADER sentiment analysis tool, optimized for social media text, to sort into positive, negative, and neutral categories.

Possible column will be in the dataset:
- City: The city associated with the Reddit post.
- Timestamp: The date and time the post was made.
- Headline: The title of the Reddit post.
- Sentiment Score: Numeric value assigned by VADER indicating sentiment polarity.
Sentiment Category: Classified as positive, negative, or neutral.
- Subreddit: The subreddit from which the post was extracted.
- Count: Total number of comments on the post.

## Weekly Plan:

- Week 1 [Vu Nguyen]:
    - Tasks: Set up the Reddit API for data extraction. Focus on collecting headlines from subreddits related to Vetnamese cities.
    - Objective: To finalize the list of city-specific subreddits and start the data collection process.

- Week 2 [Tue Nhi]:
    - Tasks: Begin preliminary data cleaning and setup the VADER analyzer to start sentiment analysis on the collected headlines.
    - Objective: To classify the collected headlines into sentiment categories and prepare the data for visualization.

- Week 3 [Vu Nguyen]:
    - Tasks: Design and implement the choropleth map using R. This involves mapping sentiment scores to corresponding cities and creating the interactive map interface.
    - Objective: To have a working prototype of the map ready for initial testing and review.

- Week 4 [Tue Nhi]:
    - Tasks: Refine the visualization based on feedback. Improve interactive features and ensure the map is user-friendly.
    - Objective: To finalize the interactive choropleth map and prepare for presentation.

- Week 5 [Both Members]:
    - Tasks: Prepare the final presentation and document the project. Review the entire workflow and ensure all components are integrated seamlessly.
    - Objective: To effectively communicate the findings and demonstrate the utility of the visualization in understanding regional sentiments.

## Conclusion
Our project aims to create an interactive visualization of sentiment analysis across various cities in Vietnam, leveraging headlines extracted from Reddit. By employing a choropleth map and an interactive dashboard designed in R, we will visualize sentiment variations and allow users to dynamically explore these changes over time. This innovative tool will provide valuable insights for local governments, marketers, and policymakers, helping them understand and respond to public sentiment effectively. We are committed to executing our plan methodically, ensuring that each phase, from data collection to final presentation, is optimized to highlight the practical benefits of integrating sentiment analysis with geographic data visualization.