# ChatGPT-Reviews-Analysis-using-Python
📌 Project Overview

This project focuses on analyzing user reviews of ChatGPT to understand customer sentiment, identify common issues, and extract actionable insights from textual feedback. The objective is to transform unstructured review data into meaningful business insights using Natural Language Processing (NLP) and data visualization techniques.

The dataset consists of user reviews, ratings, and review dates. The analysis includes sentiment classification, keyword extraction, trend analysis, and Net Promoter Score (NPS) calculation.

🎯 Objectives

Analyze overall user sentiment (Positive, Neutral, Negative)

Identify what users appreciate the most

Detect common complaints and recurring problems

Study sentiment trends over time

Calculate Net Promoter Score (NPS) to measure user loyalty

🛠️ Technologies & Libraries Used

Python

Pandas (Data Cleaning & Manipulation)

TextBlob (Sentiment Analysis)

Scikit-learn (CountVectorizer for n-gram extraction)

Plotly (Interactive Data Visualization)

🔎 Project Workflow
1. Data Preprocessing

Loaded dataset using Pandas

Handled missing values in review text

Converted review dates into datetime format

Prepared dataset for sentiment analysis

2. Sentiment Analysis

Used TextBlob to compute sentiment polarity scores and classified reviews into:

Positive

Neutral

Negative

This provided an overall distribution of customer perception.

3. Positive Review Analysis

Extracted frequent 2-gram and 3-gram phrases

Identified recurring themes such as:

Ease of use

Helpfulness

AI capabilities

Educational support

4. Negative Review Analysis

Extracted common phrases from negative reviews

Identified key issues such as:

Incorrect answers

App performance problems

Feature malfunctions

Response quality concerns

5. Problem Categorization

Grouped negative feedback into broader problem categories:

Incorrect Answers

App Performance

User Interface

Features Not Working

Quality of Responses

This helped highlight major pain points affecting user experience.

6. Sentiment Trend Over Time

Aggregated monthly sentiment counts

Visualized changes in Positive, Neutral, and Negative reviews

Observed growth in positive sentiment during high adoption periods

7. Net Promoter Score (NPS)

Ratings were categorized as:

5 stars → Promoters

4 stars → Passives

≤3 stars → Detractors

Calculated NPS:

NPS = %Promoters − %Detractors

Final NPS Score: 64.35

An NPS above 50 is generally considered excellent, indicating strong customer loyalty.
