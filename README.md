# Beats by Dre Consumer Insights Analysis

## Project Overview

This project leverages data analytics and AI to uncover actionable insights from customer reviews of the Beats Pill Bluetooth speaker. The goal is to understand customer perceptions, identify key product strengths and weaknesses, and develop strategic recommendations for product improvement and targeted marketing.

## Data & Methodology

* **Data Source:** Amazon customer reviews for the Beats Pill and its competitors.
* **Data Collection:**  Utilized the Oxylabs API to scrape the Amazon reviews.
* **Data Cleaning and Preprocessing:** Cleaned the data and processed text reviews using Pandas and NLTK.
* **Sentiment Analysis:**  Performed sentiment analysis using TextBlob (rule-based) and a fine-tuned RoBERTa model (deep learning) from **Hugging Face**.
* **AI-Powered Insights:**  Leveraged Google Gemini AI to analyze reviews and extract key insights, including customer segmentation and product improvement recommendations.
* **Comparative Analysis:**  Compared sentiment scores and features across different Bluetooth speaker brands to understand the competitive landscape.

## Key Findings

* **Software Stability is Crucial:**  Recurring software issues (random shutdowns, Siri problems, connectivity) are a major pain point for Beats Pill users.
* **Apple Users Crave Control:**  A significant drawback is the lack of a dedicated iOS app with EQ customization and other features.
* **Sound Quality is a Mixed Bag:**  While the powerful bass is a strength, some users find it overly dominant and desire more balanced audio.

## Recommendations

* **Prioritize Software Quality:**  Address software bugs and improve reliability through rigorous testing and timely updates.
* **Develop a Dedicated iOS App:**  Create a feature-rich app with EQ controls, firmware updates, and other customization options.
* **Refine Sound Profile:**  Explore options for a more balanced sound profile or provide user-adjustable EQ settings.
* **Targeted Marketing:**  Tailor marketing messages to specific customer segments, highlighting the Pill's strengths to the right audience.
