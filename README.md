# AI/ML Project: Twitter Sentiment Analysis 🐤

<p align="center"><img src="https://user-images.githubusercontent.com/54996245/144761314-6ad29602-668e-4acd-83b1-d3c9f7be0cf9.jpg" style="width: 1000px;"/></p>

### Description:

Twitter is an online Social Media Platform where people share their their though as tweets. It is observed that some people misuse it to tweet hateful content. Twitter is trying to tackle this problem and we shall help it by creating a strong NLP based-classifier model to distinguish the negative tweets & block such tweets. Can you build a strong classifier model to predict the same?

Each row contains the text of a tweet and a sentiment label. In the training set you are provided with a word or phrase drawn from the tweet (selected_text) that encapsulates the provided sentiment.

Make sure, when parsing the CSV, to remove the beginning / ending quotes from the text field, to ensure that you don't include them in your training.

You're attempting to predict the word or phrase from the tweet that exemplifies the provided sentiment. The word or phrase should include all characters within that span (i.e. including commas, spaces, etc.)

#### Columns:
1. textID - unique ID for each piece of text 
2. text - the text of the tweet 
3. sentiment - the general sentiment of the tweet 

#### Acknowledgement:
The dataset is download from Kaggle Competetions:\
https://www.kaggle.com/c/tweet-sentiment-extraction/data?select=train.csv

### Objective:
- Understand the Dataset & cleanup (if required).
- Build classification models to predict the twitter sentiments.
- Compare the evaluation metrics of vaious classification algorithms.

### The Project is divided into the following steps:
1. Data Exploration
2. Data Preprocessing
3. Exploratory Data Analysis
4. Predictive Modeling
5. Project Outcomes & Conclusions

### Some Visuals of the Project:

**1. Target Variable Distribution**

<p align="left"><img src="https://user-images.githubusercontent.com/54996245/144761331-b27fd8e6-51d9-4544-b406-010e0c835385.png" /></p>

**2. Sequence Length Distribution**

![image](https://user-images.githubusercontent.com/54996245/144761334-234cc23e-9f5a-4fd4-bf1d-e0cacc872354.png)

**3. Most frequent Positive & Negative Words Wordcloud**

![image](https://user-images.githubusercontent.com/54996245/144761343-1e354ef0-44d6-4ef7-9108-4cc69dd963e6.png)

**4. ROC Plots**

![image](https://user-images.githubusercontent.com/54996245/144761349-d7e651ba-ac4b-4974-8d7a-dc1f8c64b008.png)

**7. ML Algorithm's Scores**
![image](https://user-images.githubusercontent.com/54996245/144761355-0e97e813-b249-4edd-8c98-d30bc9c7ebd6.png)
![image](https://user-images.githubusercontent.com/54996245/144761360-bebd59d1-07f6-4b20-a63c-ad6117d9f934.png)

### Here are some of the key outcomes of the project:
- The Dataset was large enough totally around 27481 samples & preprocessing was done to clean the samples. 
- The positive, neutral & negative reviews were somewhat equally distributed.
- Visualising the distribution of data & their relationships, helped us to get some insights on the sparse matrix distribution.
- Testing multiple algorithms with default hyperparamters gave us some understanding for various models performance on this specific dataset.
- Random Forest Classifier performed the best on the current dataset with the highest F1-score. It's performance could be further improved by fintuning the hyperparmeters.
- Yet it is wise to also consider simpler models like Logisitic Regression as it is more generalisable & computationally less expensive.
