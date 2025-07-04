# 🏀 NBA Shot Selection Analysis - Kobe Bryant (PRCP-1008)

This project analyzes Kobe Bryant’s historical shot data to understand shot success factors and build a predictive model that can estimate whether a shot will be made. The project involves data cleaning, exploratory analysis, feature engineering, and multiple classification models evaluated for accuracy and F1-score.

## 📌 Objectives

- Analyze NBA shot data for Kobe Bryant.
- Identify patterns in shot location, timing, and context.
- Build a classification model to predict shot success.
- Compare model performance to find the most accurate predictor.
- Deliver actionable insights for basketball strategy.

## 📊 Dataset

- **Source**: NBA shot logs from Kobe Bryant’s 20-year career.
- **Target**: `shot_made_flag` (1 = made, 0 = missed)
- **Features**: Location (x, y, lat, lon), shot distance, time remaining, period, shot type, opponent, game context, etc.

## 🧠 Models Evaluated

- Logistic Regression
- Decision Tree ✅
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

## 📈 Best Model

- ✅ **Decision Tree**  
- Accuracy: ~76%  
- F1-score: High, balanced across classes  
- Easy to interpret for strategic decisions

## 🔍 Key Insights

- Shot distance, game period, and shot zone significantly affect shot success.
- Performance varies depending on opponent and game situation.
- Mid-range and close-range shots had higher success probabilities.

## ⚠️ Challenges Faced

- **Missing values**: Handled using appropriate filtering strategies.
- **Imbalanced classes**: Addressed during model evaluation with F1-score.
- **Feature encoding**: Handled categorical features (e.g., action type, opponent) with label encoding.
- **Model tuning**: Required experimentation to avoid overfitting and underfitting.

## 🛠️ Tools Used

- Python, Pandas, NumPy
- Scikit-learn (ML models, metrics)
- Matplotlib, Seaborn (visualization)

## 👤 Author

**Tyagesh Parmar**  
AI & Data Science Enthusiast  
[GitHub](https://github.com/TyageshParmar) | [LinkedIn](https://linkedin.com/in/tyageshparmar)
