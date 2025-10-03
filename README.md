# 🧱 Paver Block Strength Prediction (Machine Learning)

## 📌 Brief One Line Summary  
A machine learning project to predict the **compressive strength of paver blocks** based on material composition and manufacturing parameters using multiple regression models.

---

## 📝 Overview  
This project presents an end-to-end ML workflow to estimate paver block strength. It helps manufacturers and quality-control teams **reduce costs and speed up testing** by moving from experimental tests to data-driven predictions.

---

## ❓ Problem Statement  
Construction and manufacturing companies need a reliable, cost-effective way to estimate the compressive strength of paver blocks before testing. This project provides a predictive model to support material design and quality control.

---

## 📂 Dataset  
The dataset contains several physical and chemical properties of paver blocks, such as:  

- Cement content  
- Aggregates & admixture proportions  
- Water-cement ratio  
- Curing time and other features  

**Target Variable:** Compressive strength of the paver block.

---

## 🛠️ Tools and Technologies  
- **Python** for scripting & analysis  
- **Pandas / NumPy** for data manipulation  
- **Matplotlib / Seaborn** for visualisation  
- **Scikit-learn** for preprocessing & models  
- **XGBoost** for gradient boosting regression  

---

## 🔍 Methods  
1. Renamed and standardised column names.  
2. Checked shape, null values, duplicates and descriptive statistics.  
3. Explored correlations using heatmaps (**red = positive, blue = negative**).  
4. Analysed distributions and Q–Q plots to understand feature behaviour.  
5. Scaled features with **StandardScaler**.  
6. Split data into train/test sets.  
7. Trained multiple regression models and evaluated them using **MSE** and **R² Score**.  

---

## 🧠 Models Implemented  
- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- XGBoost Regressor  
- Support Vector Regressor (SVR)  

Lower MSE and higher R² indicate a better model.

---

## 🏆 Best Model Selection  
The model with the **lowest MSE** and **highest R² Score** on the test set was chosen as the final predictor for deployment.

---

## 📊 Visualisations  
- Correlation Heatmap to highlight key features  
- Distribution plots before & after scaling  
- Residual plots and Predicted vs Actual scatterplots  

These plots make it easier for engineers and decision-makers to interpret the model’s performance.

---

## 📈 Results & Conclusion  
This predictive modelling pipeline enables faster and cheaper quality control, data-driven optimisation of material mix designs, and predictive insights for production teams.

---

## 🔮 Future Work  
- Deploy the best model as an API for real-time prediction.  
- Expand the dataset with additional manufacturing parameters.  
- Integrate model explainability (SHAP, feature importance).  

---

## 👤 Author & Contact  
**Hrithik Nayak** 

Machine Learning Engineer | Data Analyst | 
[LinkedIn Profile](https://www.linkedin.com/in/hrithik-nayak-a370942aa/)  |
[Email](hrithiknayak777@gmal.com)  

---

