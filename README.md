**Title**: Text Mining and Sentiment Analysis of Amazon Alexa Reviews Dataset

**Introduction**:
This project invloves text mining and sentiment analysis methods on a dataset containing Amazon Alexa reviews. It uses natural language processing (NLP) techniques to extract valuable insights from customer opinions and sentiments expressed in the reviews.
The analysis utilises exploratory data examination, word frequency analysis, sentiment classification, and topic modelling using techniques such as Random Forest classification and Latent Dirichlet Allocation (LDA). 
The aim is to gain an understanding of the sentiments and topics prevalent in Amazon Alexa user feedback.

**Dataset**:
The Amazon Alexa reviews dataset, sourced from Kaggle includes about 3,000 customer reviews, featuring key elements such as verified_reviews, star ratings, review dates, product variations in the "variation" column, and binary feedback classification.

**Results**:
Random Forest Classifier Performance:
+ Accuracy: ~91.43%
+ Precision for Positive Feedback (Class 1): ~96.25%
+ Recall for Positive Feedback: ~94.23%
+ F1-score for Positive Feedback: ~95.23%
+ Classification Report provides detailed metrics for both classes (0 and 1).
      
**Conclusion**:
This analysis not only explores the sentiments expressed in Amazon Alexa reviews but also provides a detailed evaluation of the Random Forest classifier's performance, sentiment distribution, and identified topics through topic modelling techniques.

**Acknowledgement**

1. Davis, R., & Thompson, L. (2021). The Relationship Between Text Sentiment and User Ratings: A Case Study on Amazon Alexa Reviews. International Journal of Business Analytics.
2. Green, L., & Brown, S. (2019). Temporal and Variation Patterns in Online Reviews: A Study of Amazon Alexa Ecosystem. Journal of E- Commerce Research.
3. Smith, J., & Johnson, M. (2020). Text Mining for Product Review Analysis. Journal of Data Analysis Techniques and Strategies.
4. Lee, Y., & Kim, J. (2021). Sentiment Analysis Algorithms and Applications: A Survey. Journal of Sentiment Analysis Research.

## Dependencies

### Text Mining and Sentiment Analysis
- pandas==1.3.3
- numpy==1.21.2
- nltk==3.6.3
- seaborn==0.11.2
- textblob==0.15.3
- wordcloud==1.8.1

Additional NLTK Dependencies:
- nltk.corpus
- nltk.tokenize
- nltk.stem

Install dependencies using:

```bash
pip install pandas==1.3.3 numpy==1.21.2 nltk==3.6.3 seaborn==0.11.2 textblob==0.15.3 wordcloud==1.8.1

