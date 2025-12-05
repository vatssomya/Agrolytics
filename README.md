# 🌾 Agrolytics - Smart Crop Recommendation & Yield Prediction System

Agrolytics is a powerful AI-driven web application designed to assist farmers, researchers, and agronomists in making *data-backed agricultural decisions*. Leveraging **machine learning**, **feature engineering**, and **data preprocessing pipelines**, this tool helps recommend the most suitable crops and predicts yield based on real-time environmental data.

---

This project is built as a capstone project for the course "Fundamentals Of Data Science" 2025

## 🚀 Features

- 🌱 *Crop Recommendation* based on soil nutrients (NPK), temperature, humidity, rainfall, etc.
- 📈 *Yield Prediction* using machine learning regression models.
- 🔍 *Clean Data Pipeline*: Feature engineering, normalization, encoding.
- 🧠 Multiple ML models evaluated with accuracy comparison.
- 📊 User-friendly web interface built with Flask.

---

## 🧪 Tech Stack

- *Languages*: Python, HTML, CSS
- *Libraries*: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, Flask
- *Tools*: Google Colab, VS Code
- *ML Models*: Random Forest, KNN, Decision Tree, Logistic Regression (for classification), and Linear Regression (for yield prediction)

---

## 🛠 How it Works

1. *User Inputs*:
   - Soil nutrients: Nitrogen, Phosphorus, Potassium (NPK)
   - Temperature, Humidity, pH, Rainfall, State & Season

2. *Data Preprocessing*:
   - Handling null values, encoding categorical features, normalization.

3. *Feature Engineering*:
   - Label encoding, one-hot encoding, splitting for season-wise data.

4. *Model Training*:
   - Training and tuning various ML models to find the best fit.

5. *Prediction*:
   - Recommended crop and expected yield for given conditions.

---

## 🧠 Machine Learning Magic

- Cleaned & preprocessed a large dataset from [Agri India Open Datasets].
- Performed *correlation analysis* to understand feature impact.
- Used *train-test splits, KFold cross-validation*, and **grid search** for tuning.

---

## 🔗 Useful Links

- 📂 [GitHub Repository](https://github.com/vatssomya/Agrolytics)
- 📊 [Data Preprocessing on Google Colab](https://colab.research.google.com/drive/1z1NVxEJHbIJGAu0yAzXf7A6S5vUDzqoD?usp=sharing)

---

## 📥 Download the Models

To run the **Yield Prediction** and **Crop Recommendation** features, you will need to download the pre-trained machine learning models and place them in the same directory as your project.

- 📂 [Download final_model_yield.sav (Yield Prediction)](https://drive.google.com/file/d/1lG1TkrWJH60k68rsM_iEZrvEStv9Fnmy/view?usp=drive_link)
- 📂 [Download final_model_recommendation.sav (Crop Recommendation)](https://drive.google.com/file/d/18zL8hXCb-NvpfwljKIcYIZAIUkDxwMPf/view?usp=drive_link)
- Crop Yield = https://www.kaggle.com/datasets/patelris/crop-yield-prediction-dataset?select=yield_df.csv
- Crop Recommendation - https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset

Please ensure both `.sav` files are placed in the **same directory** as your project for everything to work correctly.

---

## 🤝 Contributing

Wanna contribute or add new crops/models? Fork this repo and start building! PRs are welcome 💚

---

## ✨ Author

*Somya Vats*  
*Tanisha Kathpal*
