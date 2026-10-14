Unveiling the Android App Market (Google Play Store Analysis)

Overview

This repository contains a comprehensive exploratory data analysis (EDA) of the Google Play Store ecosystem. Using Python, pandas, seaborn, matplotlib, and plotly, this project cleans real-world app data, explores category saturation, analyzes pricing models, investigates app sizes versus installs, and derives user sentiment trends from app ratings.

Project Objectives & Feature Checklist

[x] Load the Play Store apps dataset (googleplaystore.csv)

[x] Data cleaning: handle nulls, remove duplicates, fix incorrect data types (e.g., converting "Installs" and "Price" strings to numeric values, cleaning app "Size" into megabytes)

[x] Category analysis: bar chart of app distribution across categories; identify most saturated categories

[x] Ratings analysis: distribution of app ratings and average rating by category

[x] Size and installs analysis: scatter plot of app size vs. installs and correlation analysis

[x] Pricing analysis: paid vs. free app distribution, price ranges for paid apps, and revenue estimates by category

[x] Sentiment analysis: classify apps into positive/neutral/negative sentiment categories derived from user ratings

[x] Sentiment by category: analyze which app categories possess the highest positive or negative user sentiment

[x] Interactive visualization: built using Plotly for interactive exploration

[x] Conclusion: 3 actionable, data-driven insights for app developers

Tech Stack

Language: Python 3.x

Data Manipulation & Analysis: pandas, numpy

Static Visualization: matplotlib, seaborn

Interactive Visualization: plotly
