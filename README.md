# Qatar Airways Review Sentiment Analysis

## Overview
This project focuses on analyzing customer reviews for Qatar Airways, leveraging Natural Language Processing (NLP) techniques to extract meaningful insights. The analysis includes:
- **Text Preprocessing**: Cleaning and standardizing review text.
- **Sentiment Analysis**: Identifying sentiment as positive, negative, or neutral.
- **Named Entity Recognition (NER)**: Recognizing key entities such as locations, dates, and more.
- **POS Tagging**: Tagging parts of speech for syntactic structure insights.
- **N-gram Analysis**: Finding common word pairs and phrases.
- **Data Visualization**: Interactive plots and word clouds to visualize review patterns.

## Data and Methodology
The dataset includes Qatar Airways customer reviews and is analyzed through the following steps:
1. **Data Preprocessing**: Clean and prepare text for analysis by removing unnecessary columns, handling missing values, and normalizing text.
2. **N-gram Analysis**: Tokenizes text and identifies frequent bigrams (word pairs) in reviews.
3. **Part-of-Speech Tagging (POS)**: Tags grammatical categories, analyzing sentence structure.
4. **Named Entity Recognition (NER)**: Extracts entities such as cities, names, and other identifiers.
5. **Sentiment Analysis**: Classifies reviews based on sentiment polarity.
6. **Visualizations**: Provides insights through bar plots, pie charts, and word clouds.

## Key Results
- **Frequent Phrases**: Common bigrams like "Qatar Airways," "Doha Airport," and "business class" indicate key themes in reviews.
- **Sentiment Trends**: A sentiment analysis highlights customer perceptions over time, with notable trends in positive and negative experiences.
- **Entities and POS Insights**: Identification of important entities (e.g., locations and time references) reveals travel patterns and common customer concerns.

## Visualizations
1. **Bar Charts and Word Clouds**: Top bigrams and entities are displayed for quick insights.
2. **POS Tagging Pie Chart**: Displays grammatical structure, showcasing detailed customer narratives.
3. **Sentiment Timeline**: Illustrates trends in customer sentiment over time.

## Getting Started
To run this analysis:
1. Clone the repository and load the `qatar_airways_reviews.csv` dataset.
2. Install the necessary libraries (Pandas, NLTK, SpaCy, Plotly, Seaborn).
3. Execute the Notebook provided for step-by-step analysis.

## Conclusion
This project provides valuable insights into customer feedback for Qatar Airways by combining NLP techniques with visual analysis, useful for understanding customer sentiment and identifying common themes in reviews.

---
