# 🌍 Climate Change Impact Assessment and Prediction System for Nepal

**Omdena Batch II Capstone Project**  
*By Nisma Paudel*  

---

### Project Overview  
This project provides a system to monitor, analyze, and predict climate change impacts in Nepal, focusing on vulnerable regions and agriculture. It includes climate change data analysis, agricultural impact prediction, and NLP-based sentiment analysis.

---

### 🚀 Getting Started

#### Prerequisites  
- Python (3.x recommended)
- pip (package manager)

#### Setup Instructions

1. Clone the Repository:
   ```bash
   git clone https://github.com/Omdena-NIC-Nepal/capstone-project-nisma01paudel

2. Install Dependencies:
- Ensure Python is installed, then run:

```markdown
pip install -r requirements.txt
```

3. Run the Dashboard:
- Launch the Streamlit app with the following command:

   ```markdown
    streamlit run app.py
   ```


## 📌 Project Features

### 🌟 Features and Descriptions:

- **🌡️ Climate Analysis**  
  - Visualize climate data, including temperature trends, precipitation patterns, and extreme weather events.
  - Analyze regional climate variations and their potential impact on different geographical areas in Nepal.

- **🌾 Agriculture Analysis**  
  - Explore the relationship between climate change and agricultural productivity, including crop yields and soil health.
  - Predict the impact of climate change on farming and access to resources like irrigation and fertilizers.

- **📝 NLP Analysis**  
  - Perform sentiment analysis on climate-related text such as reports, news articles, or research papers.
  - Analyze public perception of climate change based on the tone and content of relevant text.

- **📊 Data Visualization**  
  - Interactive charts and graphs for analyzing and comparing climate and agricultural data.
  - Tools for performing exploratory data analysis (EDA) and displaying insights.

- **🛠️ Feature Engineering**  
  - Preprocessing and transformation of raw data into meaningful features ready for model training.
  - Data normalization, handling missing values, and alignment of time-series data.

- **📉 Model Training & Evaluation**  
  - Train machine learning models (classification and regression) to predict climate and agricultural impacts.
  - Evaluate models using metrics like accuracy, RMSE, and F1-score.

- **🔮 Prediction**  
  - Generate forecasts related to climate impacts, including agriculture-related predictions like crop yields and other environmental factors.

- **🌍 Interactive Dashboard**  
  - Accessible and interactive dashboard to explore different aspects of climate and agriculture analysis.
  - User-friendly interface for data exploration, model training, and predictions.

---

This section succinctly describes the features and functionality of your project. You can include this under the relevant section in your `README.md` file.

## 🖥️ Folder Structure

Here is the organization of the project files and directories:

```plaintext
CAPSTONE-PROJECT/
├── .github/                          # GitHub configurations and workflows
├── data/
│   ├── agricultural_data/
│   │   ├── agriculture-and-rural-development_npl.csv
│   ├── climate_data/
│   │   ├── Climate Normal for 20 Different Stations in Nepal1980-2010.csv
│   │   ├── climate_data_nepal_district_wise_monthly.csv
│   │   ├── filled_precipitation_data_very_final.csv
│   ├── engineered_climate_data.csv
│   
├── pages/
│   ├── climate_analysis/
│   │   ├── climate_overview.py
│   │   ├── climate_eda.py
│   │   ├── climate_feature_engineering.py
│   │   ├── climate_model_training.py
│   │   └── climate_prediction.py
│   ├── agriculture_analysis/
│   │   ├── agri_overview.py
│   │   ├── agri_eda.py
│   │   ├── agri_feature_engineering.py
│   │   ├── agri_model_training.py
│   │   └── agri_prediction.py
│

├── scripts/
│   ├── data_utils.py
│   ├── model_train.py
│   ├── model_prediction.py
│   └── visualization.py
│
├── tabs/
│   ├── about_page.py
│   ├── overview_page.py
│   ├── eda_page.py
│   ├── feat_engineering_page.py
│   ├── modeltrain_page.py
│   ├── prediction_page.py
│   └── NLP.py 
│
├── app.py
├── eda.ipynb
├── requirements.txt
└── README.md

# Project documentation
```

---

## 📌 Usage Guide

### Project Workflow:
Use the right-side tabs to switch sections in the dashboard. The suggested workflow is:

1. **Overview**
2. **Exploratory Data Analysis (EDA)**
3. **Feature Engineering**
4. **Model Training**
5. **Prediction**
6. **NLP**

---

## 📈 Data Collection & Preprocessing

he project uses:

- **Climate Data**: Historical weather and temperature records.
- **Agricultural Data**: Data on crop yields and impacts of climate on farming.


Data preprocessing steps include:
- Cleaning and normalizing the data.
- Handling missing values.
- Temporal alignment for time-series analysis.
- Creating spatially aligned datasets for geographic analysis.

---

## 🧠 Machine Learning Model Development

The system uses the following machine learning techniques:
- **Classification Models**: Random Forest, SVM, Gradient Boosting for climate zone prediction and extreme event forecasting.
- **Regression Models**: Linear Regression, Ridge/Lasso, Gradient Boosting for impact assessment.
- **Sentiment Analysis** using NLP to track public perception of climate change.

---

## 🚀 Model Evaluation & Validation

We evaluate the models based on:
- **Cross-validation** for robust model validation.
- **Accuracy, RMSE, MAE, and F1-scores** for classification and regression models.
- **Sensitivity analysis** for key model parameters.
- **Model performance across different geographical regions**.

---

## 🌍 Deployment & Integration

The dashboard is deployed using **Streamlit** for interactive visualizations. It is hosted on cloud infrastructure with the following features:
- Cloud hosting for continuous availability.
- Automated data pipeline for regular updates.
- API integration for cross-platform compatibility.

---

## 📝 Author

- [Nisma Paudel](https://www.linkedin.com/in/paudelnisma/)  
- [GitHub Repository](https://github.com/Omdena-NIC-Nepal/capstone-project-nisma01paudel)  

---

For any questions or improvements, please reach out or open an issue in the repository.

---
