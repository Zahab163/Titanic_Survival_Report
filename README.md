# Titanic_Survival_Report

# 🛳️ Titanic Survival Report

This project dives into the historical Titanic dataset to uncover the patterns behind passenger survival. Through data cleaning, visualization, and machine learning, it builds a predictive model and tells a compelling story of tragedy, resilience, and insight.

## 🎯 Objective

To analyze the Titanic dataset and identify key factors influencing survival using Python, data visualization, and machine learning. The goal is to present findings in a way that is both educational and emotionally resonant.

## 📂 Project Contents

- `Titanic_Survival_Report.ipynb`: Main analysis notebook
- `titanic.csv`: Dataset used (Kaggle Titanic dataset)
- `titanic_survival_model.joblib`: Saved logistic regression model
- `images/`: Folder for visualizations (optional)

## 🧪 Key Analyses

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Survival rate comparisons by gender, age, class, and family size
- Logistic Regression model with ~80% accuracy
- Model saved using `joblib` for future use

## 🛠️ Tools & Libraries

- Python (pandas, numpy, matplotlib, seaborn, scikit-learn)
- joblib (for model persistence)
- Google Colab (for execution)
- Streamlit (optional for deployment)

## 📈 Results Summary

Five machine learning models were trained and evaluated to predict passenger survival:

| Model                     | Accuracy (%) |
|--------------------------|--------------|
| Logistic Regression      | 80.46        |
| Random Forest Classifier | 81.93        |
| Gradient Boosting        | 82.02        |
| Decision Tree Classifier | 78.65        |
| K-Nearest Neighbors      | 77.98        |

### Embarkation Port vs Survival

Survival rates varied significantly based on embarkation port:

| Embarkation Port | Survival Rate (%) |
|------------------|-------------------|
| Cherbourg (C)     | ~55.36            |
| Queenstown (Q)    | ~38.46            |
| Southampton (S)   | ~33.70            |

- **Cherbourg** passengers had the highest survival rate, possibly due to higher proportion of first-class travelers.
- **Southampton**, despite being the main departure point, had the lowest survival rate.


- **Gender**: Females had a survival rate of ≈74.20%, while males had ≈18.89%
- **Class**: First-class passengers had the highest survival rate at ≈62.96%
- **Family Size**: Passengers with small families (1–3 members) had better chances
- **Model Saved**: Logistic Regression model saved using `joblib` for deployment
- 
## 💡 Learnings

- Importance of feature selection and preprocessing
- How historical data can be transformed into predictive insights
- Power of storytelling in data science

## 🚀 Future Enhancements


- Deploy as an interactive Streamlit app
- Include psychological or historical context
- Create a voice-over or animated video version

## 👩‍💻 Author

**Zahabia Ahmed**  
AI & Data Science Enthusiast | Educator | Motivational Content Creator  
📍 Karachi, Pakistan  
🎓 SMIT | Udacity | HP LIFE   
🔗 [LinkedIn] | [YouTube Channel](  | [GitHub Profile]
