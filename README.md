# Fake-News-Prediction-and-Analyzing-Political-Sentiment

## INTRODUCTION:
This project aims to tackle the challenge of fake news detection and political sentiment analysis on Twitter. With the rise of misinformation, especially in political discourse, this system leverages advanced machine learning and deep learning techniques to classify tweets as real or fake and analyze public sentiment on political matters.

We developed a comprehensive pipeline using Naive Bayes for fake tweet detection and deep learning models (TensorFlow, Keras) for sentiment analysis. The system processes real-time Twitter data and provides actionable insights through visualizations, helping mitigate misinformation and enhance understanding of public opinion.

## SCOPE OF PROJECT:

### 1. Fake news detection: 
Classify tweets as real or fake using machine learning models.
### 2. Sentiment analysis: 
Categorize tweets into positive, negative, or neutral sentiment.
### 3. Real-time data processing: 
Handle large volumes of Twitter data using the Twitter API.
### 4. Interactive visualization: 
Provide dashboards showing trends in fake news and public sentiment on political topics.

## FEATURES: 

### 1. Fake News Detection: 
Identifies fake tweets using the Naive Bayes algorithm.
### 2. Sentiment Analysis: 
Classifies tweets into positive, negative, or neutral sentiment using deep learning.
### 3. Real-Time Processing: 
Continuously collects and processes live tweets through the Twitter API.
### 4. Data Visualization: 
Visualizes trends in fake vs. real tweets, and political sentiment through interactive dashboards.
### 5. Scalable Design: 
Capable of handling large datasets with high performance.

## INSTALLATION:
To run the project locally, follow these steps:

1.Clone the repository:
```python
git clone https://github.com/username/repo-name.git
cd repo-name
```
2.Install required packages:
```python
pip install -r requirements.txt
```
3.Set up Twitter API credentials:
Create a Twitter Developer account.
Set your API keys in a .env file:
```python
CONSUMER_KEY=your_consumer_key
CONSUMER_SECRET=your_consumer_secret
ACCESS_TOKEN=your_access_token
ACCESS_SECRET=your_access_secret
```
4.Run the application:
```python
python main.py
```
## USAGE:

After installation, you can collect tweets in real-time and perform fake news detection and sentiment analysis as follows:
1. Run the data collection module to gather tweets on political topics using:
```python
python collect_tweets.py
```
2. Preprocess and clean the collected data:
```python
python preprocess_data.py
```
3. Run fake news detection:
```python
python detect_fake_news.py
```
4. Perform sentiment analysis on the collected tweets:
```
python sentiment_analysis.py
```
5. Visualize results using interactive dashboards:
```python
python visualize.py
```

## SYSTEM ARCHITECTURE:
![image](https://github.com/user-attachments/assets/9fad3e6f-f188-4e93-ac0d-57749ac3f2b5)

## OUTPUT:
1. Fake Tweet Detection:
Accuracy of 85% using the Naive Bayes algorithm.
Bar chart showing fake vs. real tweet distribution.

3. Sentiment Analysis:
Sentiment trends categorized into positive, negative, and neutral classes.
Line graph displaying sentiment trends over time.

## RESULT:
The system achieved the following metrics in fake news detection:

Accuracy: 85%
Precision: 82%
Recall: 80%
F1-Score: 81%

The sentiment analysis provided insights into the political landscape, showing shifts in public sentiment towards various political topics. The interactive dashboards make it easy to understand these trends.

## REFERENCE:

### Website Link : 
Shu, Kai, et al. "A Data Mining Perspective on Fake News Detection." https://arxiv.org/pdf/1708.01967
Pak, Alexander, and Patrick Paroubek. "Twitter as a Corpus for Sentiment Analysis and Opinion Mining." https://www.sciencedirect.com/science/article/pii/S0957417413001973
Goyal, Palash, Sumit Pandey, and Karan Jain. "Deep Learning for Natural Language Processing." https://www.researchgate.net/publication/326000735_Deep_Learning_for_Natural_Language_Processing
Bird, Steven, Ewan Klein, and Edward Loper. "Natural Language Processing with Python." https://dl.acm.org/doi/book/10.5555/aai29320276

### Book Reference: 
Goyal, Palash, Sumit Pandey, and Karan Jain. Deep Learning for Natural Language Processing. Apress, 2018. ISBN-13: 978-1484235462. Available on ResearchGate
Liu, Bing. Sentiment Analysis: Mining Opinions, Sentiments, and Emotions. Cambridge University Press, 2015. ISBN-13: 978-1107017894. Available on Cambridge.org
