# Google-PlayStore-EDA
Exploratory Data Analysis on Google Play Store Apps Dataset
# 📱 Google Play Store — Exploratory Data Analysis

## 📌 Business Problem
A mobile app development company wants to understand what factors 
determine an app's success on the Google Play Store to improve 
future app launches and increase downloads.

## 📂 Dataset
- Source: [Kaggle — Google Play Store Apps](https://www.kaggle.com/datasets/lava18/google-play-store-apps)
- Size: ~10,000 apps, 13 columns
- Snapshot: 2018

## 🔍 Analytical Questions
1. Which app categories have the highest total installs?
2. Do free apps outperform paid apps in installs and ratings?
3. Does a higher rating lead to more installs?
4. How do app size and content rating influence user adoption?
5. What features characterize the top 10% of high-performing apps?

## 🛠️ Tools Used
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Google Colab

## 📊 Key Findings
- FAMILY, GAME and TOOLS dominate with 37.79% of all apps
- 92.2% of apps are free — freemium dominates the market
- Paid apps rate statistically higher (4.28 vs 4.19, p < 0.05)
- App size has negligible impact on ratings (slope ≈ 0)
- Installs and Reviews are strongly correlated (r = 0.96 log-transformed)

## 📌 Actionable Recommendations
1. Target underleveraged categories like Medical and Business
2. Go freemium but invest heavily in quality
3. Optimize performance not size — especially for Indian markets

## 🔬 Further Scope
- Sentiment Analysis on user reviews
- Time Series Analysis on update frequency
- ML Models — Install Prediction, Rating Prediction, Success Classifier
