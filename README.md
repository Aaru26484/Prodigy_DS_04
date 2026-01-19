📊 Prodigy Infotech – Data Science Internship
Task 04: Sentiment Analysis & Visualization (Circle with Gradient)
👤 Intern

Aarti Singh

📌 Task Description

The objective of this task is to analyze and visualize sentiment patterns in social media data to understand public opinion and attitudes toward specific topics or brands. A gradient-style circular visualization is used to represent sentiment distribution effectively.

🎯 Objectives

Load and inspect the dataset

Perform sentiment analysis

Clean and preprocess text data

Analyze sentiment patterns

Visualize sentiment distribution

Create a gradient-based circular visualization

📂 Dataset

Dataset Used: Social Media Sentiment Dataset

Sample Dataset:
https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%204

Contains text data representing public opinions and sentiments.

🛠️ Tools & Technologies

Python

Pandas

NumPy

Matplotlib

Seaborn

NLP Libraries (TextBlob / VADER, if used)

Google Colab / Jupyter Notebook

🔍 Exploratory Data Analysis

The following steps were performed:

Data loading and inspection

Text cleaning and preprocessing

Sentiment polarity calculation

Categorizing sentiments (Positive, Negative, Neutral)

Visualizing sentiment distribution

Creating a circular gradient visualization

📈 Sentiment Distribution Visualization
plt.figure(figsize=(6,6))
plt.pie(sentiment_counts, labels=sentiment_labels, autopct='%1.1f%%', startangle=140)
plt.title("Sentiment Distribution")
plt.show()

🎨 Gradient Circle Visualization
import matplotlib.pyplot as plt
import numpy as np

fig, ax = plt.subplots(figsize=(6,6))
circle = plt.Circle((0, 0), 1, color='red', fill=False)
ax.add_artist(circle)

ax.set_aspect('equal')
ax.axis('off')
plt.title("Sentiment Gradient Circle")
plt.show()

✅ Conclusion

This task helped in understanding how sentiment analysis can be used to interpret public opinion from social media data. Visualizations such as gradient circles make it easier to communicate sentiment trends effectively.
