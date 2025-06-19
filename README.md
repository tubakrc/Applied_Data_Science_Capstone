# Applied_Data_Science_Capstone

# 🚀 SpaceX Falcon 9 First Stage Landing Prediction

This project analyzes historical SpaceX Falcon 9 launch data to uncover key insights and build machine learning models that predict the success of first-stage rocket landings. The analysis includes exploratory data analysis (EDA), data visualization, geospatial mapping, interactive dashboards, and predictive classification modeling.

---

## 📌 Table of Contents

- [Project Motivation](#Project-Motivation)
- [Data Sources](#Data-Sources)
- [Tech Stack](#Tech-Stack)
- [Key Features](#Key-Features)
- [Usage](#Usage)
- [Results](#Results)
- [Conclusion](#Conclusion)

---

## 📈 Project Motivation

SpaceX aims to reduce launch costs by reusing Falcon 9's first stage. This project helps:

- Understand patterns influencing successful landings.
- Visualize historical launch data interactively.
- Predict landing success using ML models.
- Assist aerospace stakeholders with strategic decisions.

---

## 🌐 Data Sources

- 🛰️ **SpaceX API** – Launch metadata
- 🌍 **Wikipedia Web Scraping** – Historical Falcon 9 launches
- 📦 **CSV Files** – Cleaned and processed datasets

---

## 🛠️ Tech Stack

- **Languages**: Python 3.7+
- **Data Analysis**: Pandas, NumPy, SQL
- **Visualization**: Matplotlib, Seaborn, Plotly, Folium
- **Dashboard**: Plotly Dash
- **Web Scraping**: BeautifulSoup
- **Machine Learning**: Scikit-Learn (SVM, Logistic Regression, KNN, Decision Tree)

## ✨ Key Features
🗺️ Interactive Folium map with markers, distances, and proximities

📊 Customizable Plotly Dash dashboard for site/payload analysis

🔍 SQL-based data exploration

🤖 Classification models with accuracy comparison and confusion matrix

📈 Data visualization with trends and orbit-based outcomes

## ▶️ Usage
Explore the notebooks for full exploratory data analysis

Run the spacex-dash-app.py to use the interactive dashboard

View interactive maps in visuals

Review ML performance of the models in SpaceX_Machine Learning Prediction.ipynb

## 📊 Results
All classification models (Logistic Regression, SVM, KNN, Decision Tree) achieved:

Test Accuracy: 83.3%

Confusion Matrix: TP: 12, FP: 3, FN: 0, TN: 3

These results suggest clear patterns in the data and reliable prediction capabilities.

## 📌 Conclusion
This project highlights how data-driven insights and machine learning can help aerospace companies like SpaceX understand and improve the outcomes of complex missions such as rocket landings. It also demonstrates how interactive visualizations and spatial analysis can complement traditional ML workflows.
