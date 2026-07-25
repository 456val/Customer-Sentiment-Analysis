# British Airways Passenger Sentiment Analysis

## Executive Summary

Understanding customer sentiment is essential for improving airline service quality and customer satisfaction. This project applies Natural Language Processing (NLP) techniques to analyze passenger reviews collected from British Airways customers.

The project combines web scraping, text preprocessing, sentiment analysis, topic modeling, and exploratory data analysis to uncover the major factors influencing passenger experiences. The findings highlight how operational issues such as delays, cancellations, customer service, and communication shape customer sentiment.

---

## Project Overview

Passenger reviews contain valuable information about customer experiences, but manually analyzing thousands of reviews is inefficient. This project automates the analysis of customer feedback by collecting reviews from the web and applying Natural Language Processing techniques to identify customer sentiment and recurring themes.

The project follows an end-to-end data analysis workflow, beginning with data collection and ending with actionable business insights.

---

## Business Problem

British Airways receives thousands of customer reviews describing different travel experiences. These reviews contain valuable insights into customer satisfaction, operational performance, and service quality.

Because customer feedback is unstructured text, extracting meaningful information manually is time-consuming and difficult.

This project aims to transform passenger reviews into actionable insights that can support customer experience improvement and operational decision-making.

---

## Project Objectives

The objectives of this project are to:

- Collect British Airways passenger reviews from a public review website.
- Clean and preprocess unstructured review text.
- Perform sentiment analysis using Natural Language Processing.
- Classify passenger reviews into positive, neutral, and negative sentiments.
- Identify common topics discussed by passengers.
- Analyze customer opinions on different service aspects.
- Explore factors contributing to customer satisfaction and dissatisfaction.
- Generate business insights from customer feedback.

---

## Data Collection

Passenger reviews were collected by scraping publicly available British Airways reviews using **BeautifulSoup**.

The collected data includes customer reviews and associated information that was subsequently cleaned and prepared for analysis.

---

## Data Preprocessing

Before analysis, the review text was cleaned and standardized using several Natural Language Processing techniques.

The preprocessing pipeline included:

- Removing punctuation
- Removing special characters
- Converting text to lowercase
- Tokenization
- Stop-word removal
- Lemmatization
- Text normalization

These preprocessing steps improve text quality and prepare the dataset for sentiment analysis and topic modeling.

---

## Project Workflow

```text
Passenger Reviews
        │
        ▼
Web Scraping
(BeautifulSoup)
        │
        ▼
Data Cleaning
        │
        ▼
Text Preprocessing
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Sentiment Analysis
(TextBlob)
        │
        ▼
Topic Modeling
(LDA)
        │
        ▼
Aspect-Based Sentiment Analysis
        │
        ▼
Visualization
        │
        ▼
Business Insights
```

---

## Exploratory Data Analysis

Exploratory Data Analysis (EDA) was performed to understand the overall characteristics of passenger reviews before applying Natural Language Processing techniques.

The analysis explored:

- Sentiment score distribution
- Review length
- Word frequency
- Customer review patterns
- Delay and cancellation mentions
- Service-related discussions

---

## Sentiment Analysis

Sentiment analysis was performed using **TextBlob** to calculate sentiment polarity for each passenger review.

Reviews were classified into:

- Positive
- Neutral
- Negative

The sentiment scores were further analyzed to understand the emotional intensity of customer feedback.

---

## Sentiment Distribution

Most passenger reviews are concentrated around neutral sentiment values, producing a bell-shaped distribution.

### Key Finding

British Airways generally delivers a consistent customer experience, with most passengers expressing moderate rather than extreme opinions.

---

## Review Length Analysis

The relationship between review length and sentiment was examined.

### Key Finding

Moderately positive and moderately negative reviews tend to contain the most detailed feedback, while strongly emotional reviews are generally shorter and more direct.

---

## Word Frequency Analysis

Frequently occurring words were analyzed separately for positive and negative reviews.

### Positive Reviews

Common themes include:

- Flight
- Staff
- Service
- Seat
- Time
- Good
- London

Positive reviews frequently mention:

- Professional staff
- Comfortable seating
- Good service
- Punctual flights

### Negative Reviews

Common themes include:

- Delay
- Hour
- Check-in
- Plane
- Heathrow
- Service
- Business Class

Negative reviews commonly focus on:

- Flight delays
- Long waiting times
- Poor communication
- Check-in issues
- Seating discomfort

---

## Word Cloud Analysis

Word clouds were generated to visualize the most frequently occurring words in positive and negative passenger reviews.

The visualizations provide a quick overview of the topics most frequently discussed by customers.

---

## Topic Modeling

Latent Dirichlet Allocation (LDA) was applied to discover hidden topics within passenger reviews.

Topic modeling helps identify recurring themes without manually reading every review.

Examples of identified discussion areas include:

- Flight delays
- Customer service
- Staff professionalism
- Airport experience
- Seating comfort
- Flight operations

---

## Aspect-Based Sentiment Analysis

The project also analyzes customer sentiment across specific aspects of the travel experience.

The aspects examined include:

- Customer Service
- Boarding
- Check-in
- Flight Experience

This provides a more detailed understanding of customer opinions beyond overall sentiment.

---

## Delay and Cancellation Analysis

Passenger reviews mentioning delays and cancellations were analyzed separately to understand how disruptions affect customer sentiment.

The analysis also examined common operational causes mentioned by passengers, including:

- Crew
- Weather
- Technical issues
- Mechanical issues
- Maintenance

---

## Key Findings

The analysis reveals several important insights:

- Most passenger reviews express neutral or moderately positive sentiment.
- Detailed customer feedback is more common in moderately emotional reviews.
- Professional staff and quality service contribute positively to customer satisfaction.
- Flight delays and poor communication are major drivers of negative sentiment.
- Customers are generally more understanding of uncontrollable disruptions, such as weather-related delays, when communication is timely and transparent.
- Topic modeling identifies operational reliability and customer service as recurring themes across passenger reviews.

---

## Business Insights

The project demonstrates that operational disruptions alone do not necessarily lead to customer dissatisfaction.

Instead, passenger sentiment is strongly influenced by:

- Service recovery
- Communication quality
- Staff professionalism
- Operational reliability

Improving these areas has the potential to enhance the overall customer experience.

---

## Technologies Used

- Python
- Pandas
- NumPy
- BeautifulSoup
- NLTK
- TextBlob
- Scikit-learn
- Matplotlib
- Seaborn
- WordCloud

---

## Repository Structure

```text
British-Airways-Passenger-Sentiment-Analysis/
│
├── data/
├── notebooks/
├── images/
├── README.md
├── requirements.txt
└── british_airways.ipynb
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/British-Airways-Passenger-Sentiment-Analysis.git
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## How to Run

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
british_airways.ipynb
```

Run all notebook cells sequentially.

---

## Future Improvements

Potential enhancements include:

- Train a machine learning sentiment classification model.
- Compare TextBlob with VADER and transformer-based sentiment models.
- Deploy the analysis using Streamlit.
- Build an interactive Power BI dashboard.
- Perform Named Entity Recognition (NER).
- Analyze sentiment trends over time.

---

## Skills Demonstrated

- Web Scraping
- Data Collection
- Data Cleaning
- Natural Language Processing
- Text Preprocessing
- Sentiment Analysis
- Topic Modeling
- Exploratory Data Analysis
- Aspect-Based Sentiment Analysis
- Data Visualization
- Business Intelligence
- Business Storytelling

---

## Author

**Valerie Kelechukwu**

Data Analyst

Python • SQL • Power BI • Machine Learning • Natural Language Processing
