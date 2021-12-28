# TAE-Competition
## About the Project
This was a 1-week long competition held as part of 40.016: The Analytics Edge course in SUTD. Students were tasked to form groups of size 3-4 and develop the most accurate algorithm (using R programming language) capable of predicting the sentiment of a tweet related to weather. These tweets can be of negative, neutral or positive sentiment. We were also provided 22,500 labeled tweets and 7,500 unlabeled tweets which make up the training and test csvs respectively.

## Overall Approach
We would be exploring different possibilities of data pre-processing to achieve an optimally processed training dataset to develop our algorithms. After which, we would adopt the various machine learning models taught in class and conduct additional research for potentially more accurate models to utilize.

## Data Pre-Processing
We experimented several ways to optimize our approach to processing the training data. Eventually, we found the optimal data pre-processing approach which comprised of 3 key areas: Expand Training Set, TF-IDF & N-Grams.

## Algorithm Performance
Best Performing model was Model 1 which utilized k-fold cross-validation to tune a Logistic Regression Model. This achieved an overall accuracy of 0.9056. The other, lower performance algorithms are attached for your viewing.
