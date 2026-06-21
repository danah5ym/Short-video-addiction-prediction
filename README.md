# Short-Video Addiction Prediction

> Predicting short-form video addiction using machine learning.

## 📊 Project Overview

This project analyzes user behavior patterns to classify individuals into **addiction levels** based on their short-form video consumption habits (TikTok, Reels, Shorts). Using survey data, we build machine learning models to identify at-risk users and those already addicted.

**Goal:** Predict whether a user is `Not Addicted`, `At Risk`, or `Addicted` based on their usage patterns.

## 🛠️ Technologies Used

- **Python** (pandas, numpy)
- **Data Visualization**: matplotlib, seaborn
- **Machine Learning**: scikit-learn (Logistic Regression, SVM, Random Forest)
- **Deployment**: Streamlit

## 📁 Dataset

- **Source**: Online survey data on short-form video usage
- **Features**: 11 behavioral indicators including:
  - Daily hours spent watching
  - App opening frequency
  - Sleep impact
  - Ability to stop watching
  - Stress/boredom escape use
  - Gender, age group
- **Target**: 0 = Not Addicted, 1 = At Risk, 2 = Addicted

## 📈 Results

| Model | Test Accuracy |
| :--- | :--- |
| Logistic Regression | **95.35%** |
| SVM | **95.35%** |
| Random Forest | 90.70% |

✅ **Best Model**: SVM was selected as the final model due to its balanced performance and strong generalization.

## 🔍 Key Insights

- **App opening frequency** is the strongest predictor of addiction
- Users who open apps "constantly" are most likely to be addicted
- Females showed higher addiction tendency than males
- Age group 18-24 had the highest addiction rate
- Users spending 3+ hours daily on short-form videos are at high risk

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/danah5ym/short-video-addiction-prediction.git
cd short-video-addiction-prediction