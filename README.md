# NLP-Sentiment-Analysis
Sentiment Analysis in amazon product reviews using NLP techniques 

Sentiment analysis of Amazon mobile phone reviews, often employing Random Forest or SVM classifiers, typically reveals high positive sentiment (roughly 69%) regarding performance and features. Analyzing customer reviews (e.g., in CSV formats) allows for identifying strengths like display or battery, while negative sentiment often highlights issues like delivery or software bugs. 

## Key Aspects of Sentiment Analysis on Phone Reviews
### Methodology: 
Reviews are preprocessed (cleaning, tokenization, stop word removal) and converted into numerical representations (Bag-of-Words, n-grams, TF-IDF).

### Classifiers: 
Supervised machine learning algorithms like Random Forest (often yielding the highest accuracy), SVM, and Naive Bayes are used to classify reviews as positive, negative, or neutral.

### Aspect-Based Approach: 
Rather than overall sentiment, analysis can focus on specific phone features (camera, battery, price, build).

### Review Indicators: 
Numerical ratings (1-5 stars) in datasets are frequently mapped to positive/negative sentiment to train models. 

## Typical Findings
### Positive Sentiment: 
Generally associated with high star ratings (4-5), focusing on build quality, camera quality, and value for money.

### Negative Sentiment: 
Usually associated with low ratings (1-2), focusing on battery drain, overheating, or defects. 

## Conclusion
This analysis helps determine the success factors of a phone model and assists in identifying key improvement areas.
