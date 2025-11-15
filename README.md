# 🚀 Applied Data Science Capstone Project  
### Predicting Falcon 9 First-Stage Landing Success

SpaceX has transformed the aerospace industry by dramatically reducing launch costs—offering Falcon 9 missions at **$62M** compared to competitors’ **$165M+**.  
A major part of this cost advantage comes from **reusing the first stage** of the rocket.

This capstone project focuses on **predicting the landing success** of Falcon 9’s first stage using data science and machine learning techniques. Accurate predictions help estimate launch costs and provide valuable insights to companies bidding against SpaceX.

---

## 📌 Objectives

This project is organized into multiple modules, each contributing to a complete end-to-end data science workflow.

---

## 1. 🔄 Request to the SpaceX API & Data Wrangling

- **Data Collection:** Retrieved historical launch data via GET requests to the SpaceX API.  
- **Data Cleaning:** Cleaned and standardized the raw data, addressing missing values and inconsistencies.

---

## 2. 🌐 Web Scraping Falcon 9 Launch Records

- **BeautifulSoup Scraper:** Extracted Falcon 9 launch records from Wikipedia.  
- **Data Parsing:** Converted scraped HTML tables into Pandas DataFrames.

---

## 3. 📊 Exploratory Data Analysis (EDA) & Training Labels

- **EDA:** Conducted exploratory analysis using Matplotlib and Seaborn.  
- **Training Labels:** Created and encoded the target variable for machine learning.

---

## 4. 🗄️ Database Integration (Db2)

- **Data Loading:** Stored processed data into an IBM Db2 database.  
- **SQL Analytics:** Ran SQL queries to generate insights and answer data questions.

---

## 5. 🧩 Feature Engineering & Visualization

- **Feature Engineering:** Built additional features to increase model performance.  
- **Geospatial Visualization:** Used **Folium** to create interactive maps of launch sites and success rates.

---

## 6. 📈 Interactive Visual Analytics with Plotly Dash

- **Dash App Development:** Built an interactive dashboard using Plotly Dash.  
- **User Controls:** Added dropdowns, sliders, pie charts, and scatter plots for real-time data exploration.

---

## 7. 🤖 Machine Learning Models & Hyperparameter Tuning

- **Preprocessing:** Standardized features and split the data into train/test sets.  
- **Model Tuning:** Applied GridSearchCV on:
  - Support Vector Machines  
  - Decision Trees  
  - Logistic Regression  
- **Evaluation:** Selected the best-performing model based on test accuracy.

---

## 🏆 Results

| Model | Test Accuracy |
|-------|----------------|
| **Decision Tree Classifier** | **0.9444** ⭐ Best |
| SVM | 0.8333 |
| K-Nearest Neighbors | 0.8333 |

The **Decision Tree Classifier** achieved the highest accuracy, making it the strongest model for predicting first-stage landing outcomes.

---

## 🧭 Conclusion

This project covers the full lifecycle of a data science solution—from data acquisition and cleaning, to visualization, dashboarding, and machine learning.

Predicting first-stage landing success provides key insights into **launch cost estimation** and **competitive bid strategy** for the aerospace industry.

---

## 📁 Repository Structure

```
.
├── data/            # Datasets and data-processing resources
├── notebooks/       # Jupyter notebooks documenting each module
├── scripts/         # Scripts for ETL, visualization, and modeling
├── dash_app/        # Plotly Dash interactive dashboard
└── README.md        # Project overview and detailed documentation

```
---

## 🙏 Acknowledgments

- **IBM** — For providing the course and materials  
- **Coursera** — For the platform hosting the program  

---
