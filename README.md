# AmazonReviews-SentimentAnalysis-TopicModelling
Analyzing Amazon Reviews using Sentiment Analysis &amp; Topic Modelling 
The folder contains Datasets, Python_Code and Detailed Report.

# Problem Statement:  
Businesses often want to understand what people are talking about their laptop products and how they can improve to achieve better customer satisfaction, ultimately translating to more business (sales, revenue, transactions, etc.).  Here, using text analysis techniques, we aim to extract what people are talking about products on Amazon, provide summary to the laptop brands and give specific actionable insights into improving audience experience / expectations.


# Approach: 
Collect Amazon Reviews (Web data scraping) and apply sentiment analysis techniques to find avg audience sentiment towards a particular laptop brand. Secondly, apply topic modelling techniques to extract the topic of reviews (example battery life, display, picture quality, etc.). Combining these two would allow brands to identify which aspects of their product are being liked (positive sentiments) and which aspects need improvements (negative sentiments)


# Machine Learning Techniques Used: 
a. Word Embeddings:  word2vec using gensim library combined with pre-trained word2vec models
b. Sentiment Analysis: Logistic Regression and Recurrent Neural Networks. In this case, RNN are more reliable and hence, preferred technique
c. Topic Modelling: Count Vectorization to convert words to vectors, Latent Dirichlet Allocation using 'nltk' library to find dominant topic of each comment


# Results & Conclusion:
For firms looking to analyze reviews, Sentiment analysis alone does not give a deeper picture. It tells about the overall distribution of sentiments. However, what is the context or topic of the review is not known. Hence, we implemented a combination of sentiment analysis techniques and topic modeling. We were able to achieve topic extraction from reviews, word2vec embeddings and sentiment analysis using logistic regression and RNN. Neural networks are better than Logistic regression techniques for text analysis and we would recommend the firm to use deep learning techniques to predict the sentiments. We would also recommend the firm to focus on negative sentiment topics to improve.





