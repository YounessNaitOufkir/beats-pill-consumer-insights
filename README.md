# Beats by Dre Consumer Insights Analysis

![Beats Pill](Beats_Pill.png)

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

## Technologies & Tools Used

[![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=flat&logo=numpy&logoColor=white)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=flat&logo=Matplotlib&logoColor=white)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-%23017193.svg?style=flat&logo=Seaborn&logoColor=white)](https://seaborn.pydata.org/)
[![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=flat&logo=plotly&logoColor=white)](https://plotly.com/python/)
[![TextBlob](https://img.shields.io/badge/TextBlob-000000?style=flat&logo=TextBlob&logoColor=white)](https://textblob.readthedocs.io/en/dev/)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-blue?style=flat&logo=huggingface&logoColor=white)](https://huggingface.co/)
[![Google Gemini](https://img.shields.io/badge/Google%20Gemini-4285F4?style=flat&logo=google-cloud&logoColor=white)](https://developers.generativeai.google/)
[![Oxylabs](https://img.shields.io/badge/Oxylabs-FF69B4?style=flat&logo=Oxylabs&logoColor=white)](https://oxylabs.io/)
