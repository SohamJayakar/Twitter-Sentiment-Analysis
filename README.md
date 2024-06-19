# Twitter Sentiment Analysis

## Overview
**Twitter Sentiment Analysis** is a machine learning project aimed at classifying the sentiment of tweets as positive, negative, or neutral. This project leverages natural language processing techniques to analyze and interpret the sentiment expressed in tweets.

## Introduction
Social media platforms like Twitter are rich sources of textual data where people express their opinions on various topics. Analyzing these opinions can provide valuable insights for businesses, researchers, and policymakers. This project focuses on building a sentiment analysis model to classify tweets into positive or negative categories.

## Dataset
The dataset used for this project can be downloaded from the following link:

[Download Dataset](https://drive.google.com/file/d/1W3I5EHey995yJ0Q7jAQ8_vlLJJc4vgQU/view?usp=drive_link)

## Installation
To run this project, you need to have Python 3.8 or higher installed. Follow the steps below to set up the project environment:

**Clone the repository:**
```bash
git clone https://github.com/SohamJayakar/Twitter-Sentiment-Analysis.git
cd twitter-sentiment-analysis
```

**Create a virtual environment:**
```bash
python -m venv venv
source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
```

**Install the dependencies:**
```bash
pip install -r requirements.txt
```

## Results
The model achieved the following performance on the test dataset:

**Naive Bayes:** Accuracy: 79%

**SVM:** Accuracy: 84%

**Logistic Regression:** Accuracy: 83%

The confusion matrices and classification reports are provided to illustrate the performance of each model in detail.
