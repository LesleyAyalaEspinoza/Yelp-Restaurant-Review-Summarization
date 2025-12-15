# Yelp Restaurant Review Summarization

## Background and Overview

This analysis converts unstructured restaurant reviews into clear, actionable insights by summarizing customer sentiment and recurring themes across multiple businesses. Instead of reviewing individual comments, stakeholders can quickly understand what customers value most and where improvements are needed.

Customer reviews contain valuable feedback but are difficult to analyze at scale. By grouping reviews into positive and negative sentiment and organizing them into categories such as food quality, service, ambiance, and convenience, this analysis provides a structured view of customer experience that supports faster and more informed decision-making.

## Data Structure 

This ERD shows how restaurant reviews are linked to businesses and how sentiment summaries are derived from customer feedback. Individual reviews are analyzed to extract recurring themes and sentiments, which are then organized into structured summaries for easier interpretation.

<img width="1173" height="754" alt="Screenshot 2025-12-14 at 3 26 31 PM" src="https://github.com/user-attachments/assets/b2a42e46-aa13-4a98-a8d7-01fa2514494a" />

## Overview of Findings
Below, I have attached screenshots of the output of my code. The output is the summary of the Yelp reviews.

<img width="809" height="542" alt="Screenshot 2025-12-14 at 7 19 18 PM" src="https://github.com/user-attachments/assets/7b7da0e4-ac72-4266-a65e-461561372adf" />
<img width="809" height="435" alt="Screenshot 2025-12-14 at 6 42 12 PM" src="https://github.com/user-attachments/assets/50917f93-8727-4861-abd4-43bbd2168e70" />

## Recomendations

- Reinforce high performing menu items and service behaviors that consistently generate positive feedback.
- Standardize food preparation and service processes to reduce isolated negative experiences.
- Use summarized customer themes to inform staff training, marketing strategies, and customer experience initiatives.
- Implement automated review summarization on an ongoing basis to monitor sentiment trends in near real time rather than relying on manual review.

## Tools & Technologies

- SQL (Databricks) for querying and data preparation
- Apache Spark for scalable data processing
- Python for workflow orchestration
- Google Gemini (LLM) for review summarization
- LangChain for prompt templating and structured output generation
