# 💧 Pump Guardian: Waterpoint Status Predictor

**I built a machine learning model to predict the operational status of water pumps in rural Tanzania, using real-world data and Google Colaboratory.**

## 🧠 Project Overview

This project was developed as part of the [**"Pump it Up: Data Mining the Water Table"**](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/) competition on DrivenData. The goal was to classify each water pump into one of three categories:

- **Functional**
- **Non-functional**
- **Functional needs repair**

The dataset includes over 50 variables — such as geographic location, water quality, extraction type, and installer details — and comes with real-world challenges like:
- Missing values
- High-cardinality categorical features
- Imbalanced class distribution

## 🚀 My Goals

- Build and fine-tune a robust multi-class classification model
- Handle missing data and complex categorical variables
- Perform data cleaning, preprocessing, and feature engineering
- Deliver explainable, reliable predictions

## 🧰 Tools & Technologies

I worked entirely in **Google Colaboratory**, using the following tools and libraries:

- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn`, `XGBoost`, `LightGBM`
- `category_encoders`, `imbalanced-learn`
- Grid search, cross-validation, and evaluation metrics

## 📁 Dataset

All data was provided by the competition organizers and is available here:

- 🔗 [Competition overview](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/)
- 🔗 [Download the dataset](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/data/)
- 🔗 [Variable descriptions](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/page/25/)

Files used:
- `train.csv` – Features for training
- `train_labels.csv` – Target variable
- `test.csv` – Data for prediction
- `SubmissionFormat.csv` – Required submission format

> ⚠️ I followed the competition rules strictly and did **not** use any external data sources.

## 📈 Submission Details

Submissions must include:
- `id` (pump ID)
- `status_group` (predicted class)

Evaluated using the **macro F1-score**.
- 🔗 [Submit predictions](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/submissions/)

## 📌 Highlights

- Hands-on application of machine learning to a real-world classification problem
- Clear documentation and code structure, built for reproducibility
- Fully developed and tested in Google Colab

---

👨‍🔬 _"Solving real-world problems drop by drop — one prediction at a time."_


