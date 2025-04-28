# **Predicting Business Success Using Yelp Data**
---
# Team Members:
- **Jasmin Pena** [jnpena](https://github.com/jnpena)
- **Jennifer Nguyen** [Jenblr](https://github.com/Jenblr)
- **Adefemi Abimbola** [Asabimbo](https://github.com/Asabimbo)
- **Ali Muhammad Lalani** [alimuhammad-lalani](https://github.com/alimuhammad-lalani)
- **Farzam Afzal** [pyrrhicology](https://github.com/pyrrhicology)
---
#  Files:
- **Yelp_Dataset.ipynb** - Created to help members know how to import the dataset and load it correctly. Also created code to clean up the dataset by removing certain columns from specific datasets (e.g. business and user datasets). This file is used since importing the actual cleaned datasets to GitHub is not possible, considering each dataset is considerably large. 
- **Structured_Data2.ipynb** - Focuses on data cleaning, feature engineering, and normalization of Yelp dataset variables. This notebook processes and transforms raw business, review, user, and check-in data into structured, machine-learning-ready formats.
- **Predictive_Modeling.ipynb** - Created to implement baseline models, with the goal to predict business star rating using simple features by implementing linear regression and decision tree. 
- **Sentiment_Analysis.ipynb** - Implements advanced NLP techniques to analyze Yelp business reviews. It extracts insights about customer sentiment and identifies key topics in review content. This comprehensive analysis helps understand the factors that drive customer satisfaction across different business categories, providing actionable insights that can be used to predict business success potential.
    - **sentiment_distribution.png** - Histogram with a KDE (Kernel Density Estimation) line overlay. The x-axis represents sentiment scores ranging from 0 to 1, where 0 represents negative sentiment and 1 represents positive sentiment. The y-axis shows the count of reviews.
    - **topic_sentiment.png** - Bar chart, where each bar represents one of the 10 topics (labeled 0-9) identified by the topic modeling algorithm. The y-axis shows the average sentiment score for each topic, ranging from 0 to just above 0.9. 

