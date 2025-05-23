# Sentiment-Analysis

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : HARISH AADITYA SRIDHARAN

*INTERN ID* : CT1MTDL12

*DOMAIN* : DATA ANALYTICS

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTOSH

In the digital age, customers frequently express their opinions and experiences online, especially on social media platforms like Twitter. This wealth of textual data presents a unique opportunity for businesses to understand customer sentiment, address issues proactively, and tailor their services to meet expectations. One of the most practical applications of Natural Language Processing (NLP) in this domain is sentiment analysis—the process of determining whether a piece of text expresses a positive, negative, or neutral sentiment.

This project focuses on performing sentiment analysis using the Twitter US Airline Sentiment Dataset, which contains tweets from February 2015 directed at major U.S. airlines, including American, Delta, United, Southwest, US Airways, and Virgin America. Each tweet is labeled with a sentiment: positive, neutral, or negative. The primary objective of this project is to develop a machine learning model capable of accurately predicting the sentiment of a tweet based on its textual content.

Dataset link: https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment

The process begins with data loading and exploratory data analysis (EDA). This step involves understanding the distribution of sentiment classes, checking for imbalances, and observing general trends in the data. Visualizations like bar charts are used to showcase how users felt about each airline and the overall sentiment distribution. It is evident from this analysis that a large portion of the tweets are negative, which reflects public dissatisfaction with airline services and also introduces a class imbalance challenge for machine learning models.

Once the dataset is understood, the next crucial step is text preprocessing. Raw text data contains noise such as URLs, hashtags, user mentions, punctuations, and special characters. These elements do not contribute meaningfully to sentiment classification and are removed. Tokenization is performed to split the text into words, and stopwords—common words like "the", "is", and "and" that do not carry significant meaning—are also removed. All text is converted to lowercase to ensure uniformity. The resulting cleaned text serves as the input for the machine learning model.

To convert textual data into a format that can be used by machine learning algorithms, the text is transformed into numerical vectors using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization. This method represents each document (tweet) by the importance of its words, capturing the frequency of a term while also considering its rarity across the corpus.

With the data vectorized, it is split into training and testing sets. A Logistic Regression model—a popular and interpretable classification algorithm—is trained on the training set. The model learns to associate specific patterns and keywords in the tweet text with sentiment labels. After training, the model is evaluated on the test set using metrics such as accuracy, precision, recall, and F1-score. A confusion matrix is plotted to visualize the model’s performance in distinguishing between the three sentiment classes.

Finally, insights are extracted by analyzing the most informative words for each sentiment class using statistical methods like the chi-square test. This step provides interpretability to the model, revealing which words are most strongly associated with positive, negative, or neutral tweets.

In conclusion, this project demonstrates the full pipeline of a sentiment analysis task—from raw tweet data to an interpretable classification model—using traditional machine learning and NLP techniques. It highlights the importance of text preprocessing, class balancing, and feature engineering in building effective sentiment classifiers. Such models can be highly valuable for customer feedback analysis, brand monitoring, and service improvement initiatives in various industries, particularly for airlines aiming to enhance customer satisfaction through social media insights.

#OUTPUT

![Image](https://github.com/user-attachments/assets/05ebd28a-bba2-4287-b301-964db5152ab6)
![Image](https://github.com/user-attachments/assets/9cebc166-f75e-436f-b2e8-06f68caa601c)
![Image](https://github.com/user-attachments/assets/25d38698-e6cc-49a3-8f71-966e87eecfb6)
