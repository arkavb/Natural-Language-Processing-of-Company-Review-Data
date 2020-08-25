# Natural-Language-Processing-of-Company-Review-Data
In this project we will be classifying reviews given by the employers for the employee or the company as positive or negative reviews. The dataset contains 67,529 rows and 15 columns. The dataset has information primarily regarding the company, position, date, pros and cons. This project can help a company analyze the ratio of employees that are satisfied or not satisfied with their work environment. This can help in future improvements and help give a better experience to the future employees. Using the word cloud for positive and negative sentiment, they can better understand which problems are more precarious than the others and focus on them rather than those that don’t need immediate attention. This can also be leveraged by rival companies to understand the problems of the competition to avoid those themselves. The positive views can also be used extensively to understand why the competition may be prospering and can be incorporated into a company’s work culture for a holistic work experience. Using sentiment analysis on reviews of any kind can help in understanding the deep-seated issues with a product or a workplace and can also be used to optimize on all the things that are going right and strive towards excellence.

Steps:

Data collection: the first step of sentiment analysis consists of collecting data from user generated content contained in blogs, forums, social networks and text analytics and natural language processing are used to extract and classify. In our case it is collected from Kaggle.

Text preparation: consists of cleaning the extracted data before analysis. We will be using techniques such as bag of words and lemmatization.

Feature Extraction: the extracted sentences of the reviews and opinions are examined. Use word embedding (count vectorizer, tf-idf transformation, Word2Vec) to transform reviews into numerical representations.

Machine learning classifier: Fit numerical representations of reviews to machine learning algorithms. We will be using Naïve Bayes, Logistic Regression, Random Forest and LSTM.

Sentiment classification: Subjective sentences are classified in positive, negative, good or bad.

Presentation of output: the main objective of sentiment analysis is to convert unstructured text into meaningful
