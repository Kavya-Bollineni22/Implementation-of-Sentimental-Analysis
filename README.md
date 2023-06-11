# Implementation-of-Sentimental-Analysis
Sentiment analysis is used to detect or recognize the sentiment which is contained in the text. This analysis helps us to get the reference of our text which means we can understand that the content is positive, negative, or neutral.
Sentiment analysis, also referred to as opinion mining, is an approach to natural language processing (NLP) that identifies the emotional tone behind a body of text. This is a popular way for organizations to determine and categorize opinions about a product, service or idea. Sentiment Analysis is a use case of Natural Language Processing (NLP) and comes under the category of text classification. To put it simply, Sentiment Analysis involves classifying a text into various sentiments, such as positive or negative, Happy, Sad or Neutral, etc.
## Program:
```
import nltk
from nltk.sentiment import SentimentIntensityAnalyzer

nltk.download('vader_lexicon')

sia = SentimentIntensityAnalyzer()

text = "I love this movie! It's amazing."
scores = sia.polarity_scores(text)

print("Positive score:", scores['pos'])
print("Negative score:", scores['neg'])
print("Neutral score:", scores['neu'])
print("Compound score:", scores['compound'])
```

## Output:
![image](https://github.com/Kavya-Bollineni22/Implementation-of-Sentimental-Analysis/assets/75235813/527915d6-baa3-4c8a-8f27-af06e11e3c9c)


