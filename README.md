# Yelp-Restaurant-Review-Summarization

## Project Background

This repository demonstrates how to extract and summarize customer sentiment from restaurant reviews using SQL, Python, and large language models. The analysis focuses on identifying positive and negative customer experiences from star ratings and written feedback, and on transforming unstructured review text into structured, actionable insights. By leveraging LangChain and Google Gemini within a Databricks environment, this workflow produces categorized summaries that highlight key themes such as food quality, service, ambiance, and pricing. The goal is to make large volumes of customer feedback easier to interpret for both businesses and consumers.

## Objective 

- Analyze restaurant reviews to understand customer sentiment
- Classify reviews as positive and negative using star ratings
- Summarize recurring themes within customer feedback
- Convert unstructured text into structured, readable outputs.

## Data Structure 

This ERD shows how restaurant reviews are linked to businesses and how sentiment summaries are derived from customer feedback. Individual reviews are analyzed to extract recurring themes and sentiments, which are then organized into structured summaries for easier interpretation.

<img width="1173" height="754" alt="Screenshot 2025-12-14 at 3 26 31 PM" src="https://github.com/user-attachments/assets/b2a42e46-aa13-4a98-a8d7-01fa2514494a" />


## Data Description

- Source: Yelp Restaurant Reviews
- Key  frields:
  - business_id
  - stars
  - text (review content)
- Data filtered to include restaurant-related categories only
- Reviews with fewer than 2 stars are excluded to focus on meaningful negative experiences

## Methodology





## Recomendations

