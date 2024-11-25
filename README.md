**Sentiment Analysis of Amazon Product Reviews**
This project aimed to perform sentiment analysis on customer reviews to determine whether the sentiment expressed was positive or negative. 
This information can be valuable for businesses to understand customer opinions about their products or services.


**Features Implemented:**


**Data Preprocessing:**

Loading data from a CSV file.

Handling missing values by dropping rows with nulls.

Selecting relevant columns ('ProductId', 'Text').


**Sentiment Analysis:**

Calculating VADER sentiment scores.

Assigning sentiment labels (Positive, Negative, Neutral) based on compound scores.

Encoding sentiment labels to numerical values (0 for Negative, 1 for Positive).

**Data Visualization:**


Creating a bar chart to visualize the distribution of positive and negative reviews.

Generating bag-of-words visualizations for positive and negative sentiment using bar charts to display the most frequent words.


**Model Building:**

Splitting the data into training and testing sets.

Feature extraction using TF-IDF (Term Frequency-Inverse Document Frequency).

Training multiple machine learning models (Logistic Regression, Naive Bayes, Random Forest).

Evaluating model performance using accuracy scores.

