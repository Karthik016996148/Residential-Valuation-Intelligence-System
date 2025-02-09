# Residential Valuation Intelligence System (RVIS)

## Overview

Residential Valuation Intelligence System (RVIS) is a machine learning-based predictive model designed to estimate house prices accurately. The system leverages advanced regression models, including Elastic Net, Random Forest, XGBoost, and Gradient Boosting, to improve valuation accuracy and market transparency. 

The project involves data collection from **Zillow** via **RapidAPI**, extensive data preprocessing, feature engineering, model training, and deployment. The final system aims to provide real estate stakeholders—such as buyers, sellers, and investors—with actionable insights for property valuation.

---

## Features

- **Data Collection**: Scrapes real estate data from Zillow using web scraping and APIs.
- **Data Preprocessing**: Cleans, transforms, and processes data for high-quality predictions.
- **Feature Engineering**: Extracts key features such as price per square foot, lot area, and property age.
- **Machine Learning Models**: Implements multiple regression techniques, including:
  - Elastic Net
  - Random Forest
  - XGBoost
  - Gradient Boosting
- **Model Evaluation**: Uses Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared metrics for accuracy assessment.
- **Deployment**: Provides a user-friendly interface for querying house price estimates.

---

## Dataset

- **Source**: Zillow real estate listings via RapidAPI
- **Format**: JSON (converted to CSV for processing)
- **Size**: ~41,929 records, 48 attributes
- **Key Features**:
  - Property attributes (bedrooms, bathrooms, home type, living area)
  - Geographic location (latitude, longitude, zip code, city, state)
  - Market indicators (days on Zillow, price trends)

---

### Prerequisites

Ensure you have the following installed:

- Python 3.8+
- Jupyter Notebook
- Required Python libraries:
