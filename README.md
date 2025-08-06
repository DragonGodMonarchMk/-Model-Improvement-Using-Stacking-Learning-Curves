# -Model-Improvement-Using-Stacking-Learning-Curves
Enhancing regression model performance on the Online News Popularity dataset using stacking, learning curves, and comparative analysis of base learners.
# 📈 Model Improvement Using Stacking & Learning Curves

This project demonstrates how to improve predictive model performance using **stacking ensemble techniques** and **learning curve analysis**. The dataset used is the **Online News Popularity dataset**, which includes various features about online articles and their corresponding popularity in terms of shares.

## 🚀 Highlights

- Implements **multiple regression algorithms** including:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
  - Gradient Boosting
- Uses **stacking** to combine model strengths for better accuracy
- Plots **learning curves** to evaluate model performance with varying training sizes
- Visualizes error and performance metrics

## 🧠 Dataset Overview

- **Name**: [Online News Popularity Dataset](https://archive.ics.uci.edu/ml/datasets/online+news+popularity)
- **Features**:
  - Article metadata (e.g., word count, keywords, days of the week)
  - Social signals (e.g., number of shares)
  - Natural language statistics (e.g., average positive/negative polarity)
- **Target Variable**: `shares` (number of times an article was shared online)

## 📊 Models Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- Stacking Regressor (combination of the above)

## 📉 Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

Also includes:
- Learning curves for performance diagnostics
- Comparative analysis of models before and after stacking

## 📁 Project Structure

project/
│
├── model-improvement-using-stacking-learning-curves.ipynb
├── OnlineNewsPopularity.csv
├── requirements.txt (optional)
└── README.md
## 💻 How to Run

1. Clone the repository:
   ```bash
      ```bash
   git clone https://github.com/your-username/news-popularity-model-stacking.git
   cd news-popularity-model-stackingpip
   install -r requirements.txt
   jupyter notebook model-improvement-using-stacking-learning-curves.ipynb
pip install pandas numpy matplotlib seaborn scikit-learn


   git clone https://github.com/your-username/news-popularity-model-stacking.git
   cd news-popularity-model-stacking
