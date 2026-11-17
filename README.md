# ChatGPT Review Analysis using Python

## Project Overview
This project analyzes ChatGPT user reviews using Python and Natural Language Processing (NLP) to understand user sentiment, satisfaction patterns, and commonly discussed features.

## Objectives
- Analyze positive, negative, and neutral user sentiments.
- Calculate sentiment polarity and subjectivity.
- Compare numerical ratings with review sentiments.
- Identify frequently mentioned positive and negative keywords.
- Generate actionable business insights.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- TextBlob
- WordCloud
- Counter
- Google Colab

## Dataset
The original dataset contained 196,727 records and four columns: Review ID, Review, Ratings, and Review Date.

After removing 2,511 exact duplicate records, the cleaned dataset contained 194,216 records.

## Methodology
1. Data loading and exploration
2. Data cleaning and preprocessing
3. Sentiment polarity and subjectivity analysis
4. Exploratory Data Analysis (EDA)
5. Positive and negative keyword extraction
6. Data visualization
7. Business insights and recommendations

## Key Findings

| Metric | Result |
|---|---|
| Cleaned Reviews | 194,216 |
| Positive Sentiment | 76.32% |
| Neutral Sentiment | 19.53% |
| Negative Sentiment | 4.15% |
| Average Polarity | 0.447 |
| Average Subjectivity | 0.517 |

### Positive Feedback
Frequently mentioned words include good, best, helpful, amazing, and useful.

### Negative Feedback
Frequently mentioned words include wrong, bad, answer, and information.

### Rating Analysis
Most reviews received high ratings, but numerical ratings and text sentiment did not always agree.

## Business Recommendations
- Investigate complaints about incorrect or inaccurate responses.
- Examine recurring usability and feature-related concerns.
- Explore opportunities to improve learning and assistance features.
- Monitor sentiment and ratings to identify changing user experiences.

## Limitations
TextBlob uses lexicon-based sentiment analysis and may not accurately interpret sarcasm, mixed opinions, or non-English text. Keyword frequency alone does not establish the context of user feedback.

## Conclusion
This project demonstrates how Python and NLP techniques can transform unstructured customer reviews into meaningful insights that support product improvement and customer experience analysis.
