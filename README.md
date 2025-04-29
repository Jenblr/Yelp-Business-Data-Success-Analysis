# **Predicting Business Success Using Yelp Data**
### GITHUB: https://github.com/Jenblr/Yelp-Business-Data-Success-Analysis
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
- **Structured_Data1.ipynb** - Focuses on data cleaning, feature engineering, and normalization of Yelp dataset variables. This notebook processes and transforms raw business, review, user, and check-in data into structured, machine-learning-ready formats.
- **Predictive_Modeling1.ipynb** - Created to implement baseline models, with the goal to predict business star rating using simple features by implementing linear regression and decision tree. 
- **Predictive_Modeling2.ipynb** - Created to implement Sentiment Analysis and Topic Modeling for Yelp Business Success
- **Sentiment_Analysis.ipynb** - Implements advanced NLP techniques to analyze Yelp business reviews. It extracts insights about customer sentiment and identifies key topics in review content. This comprehensive analysis helps understand the factors that drive customer satisfaction across different business categories, providing actionable insights that can be used to predict business success potential.
- **Visualizations/** - Folder containing graphs
    - **sentiment_distribution.png** - Histogram with a KDE (Kernel Density Estimation) line overlay. The x-axis represents sentiment scores ranging from 0 to 1, where 0 represents negative sentiment and 1 represents positive sentiment. The y-axis shows the count of reviews.
    - **topic_sentiment.png** - Bar chart, where each bar represents one of the 10 topics (labeled 0-9) identified by the topic modeling algorithm. The y-axis shows the average sentiment score for each topic, ranging from 0 to just above 0.9. 
    - **feature_importance.png** - Horizontal bar chart displaying the importance scores of various features used in a tree-based model.The chart ranks features from most important (top) to least important (bottom), with the x-axis representing the importance score.
---
#  Datasets:
- **yelp_academic_dataset_business.json** - Contains business data including location data, attributes, and categories.
- **yelp_academic_dataset_checkin.json** - Checkins on a business.
- **yelp_academic_dataset_review.json** - Contains full review text data including the user_id that wrote the review and the business_id the
review is written for.
- **yelp_academic_dataset_tip.json** - Tips written by a user on a business. Tips are shorter than reviews and tend to convey quick
suggestions.
- **yelp_academic_dataset_user.json** - User data including the user's friend mapping and all the metadata associated with the user.
- **CSVs/** - Folder containing some csv files (e.g. sample of the dataset, sentiment data,etc.)
