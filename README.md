# Falcon9-ai-analysis-capstone

This repository contains my final project for the **IBM Data Science Professional Certificate** on Coursera.  
The project focuses on analyzing **SpaceX Falcon 9 launch data** to predict the likelihood of a successful first-stage landing.


## Project Overview

The goal of this project is to use data science methods to determine what factors contribute to the success of SpaceX rocket launches.  
By exploring, visualizing, and modeling real SpaceX data, we gain insights into SpaceX’s launch success trends.


## Skills & Tools Used

- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Folium, Plotly  
- **Techniques:** Data Wrangling, Exploratory Data Analysis (EDA), Data Visualization, Machine Learning  
- **Environment:** Jupyter Notebook

## Key Steps

The project began with data collection, where SpaceX launch data was obtained using a public API and through web scraping from Wikipedia. After gathering the data, the data wrangling phase involved cleaning, formatting, and preparing the dataset by handling missing values, converting data types, and creating relevant features for analysis. Next, an extensive exploratory data analysis (EDA) was performed to uncover patterns and relationships between payload mass, launch sites, orbit types, and the success of Falcon 9 first-stage landings. Visualizations using Matplotlib, Seaborn, and Plotly provided meaningful insights into the factors influencing launch outcomes. An interactive dashboard was then developed using Plotly Dash to dynamically display success rates by site and payload. Finally, several machine learning models—including Logistic Regression, Support Vector Machine (SVM), Decision Tree, and K-Nearest Neighbors (KNN)—were trained and evaluated to predict the likelihood of a successful first-stage landing, with the Decision Tree model achieving the best accuracy.

