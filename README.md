# Solar_rradiance_Prediction
#Solar Irradiance Prediction


# 🔆 Solar Irradiance Prediction Using Weather Data

An intelligent machine learning model that predicts solar irradiance based on weather parameters such as temperature, humidity, wind speed, and atmospheric pressure. This project aims to support solar energy planning by providing accurate energy output forecasts.

---

## 📚 Overview

Accurate solar irradiance prediction is crucial for optimizing solar panel performance and planning sustainable energy systems. This project applies machine learning techniques—**XGBoost** and a **Neural Network**—to forecast solar irradiance using historical weather data.

---

## ✅ Key Features

- 📊 Comprehensive Exploratory Data Analysis (EDA)
- 🧼 Data cleaning, normalization, and feature selection
- 📌 Feature importance analysis using correlation and domain logic
- ⚙️ Regression models using:
  - **XGBoost Regressor**
  - **Neural Network (Keras/TensorFlow)**
- 📈 Model evaluation using R² Score and RMSE
- 📉 Visualizations of predictions vs. actual irradiance

---

## 🧰 Tech Stack

| Category      | Tools/Libraries                             |
|---------------|---------------------------------------------|
| Language      | Python                                      |
| Data Handling | Pandas, NumPy                               |
| Visualization | Matplotlib, Seaborn                         |
| ML Models     | Scikit-learn, XGBoost, TensorFlow/Keras     |
| Environment   | Jupyter Notebook                            |

---

## 📁 Folder Structure
solar-irradiance-prediction/
├── Solar Irradiance Prediction.ipynb # Jupyter notebook with code and results
├── dataset.csv # Weather dataset (user must add if needed)
├── README.md # Project documentation
├── requirements.txt # List of dependencies







✅ 1. Install All Packages Manually (One by One)
Just run this in your terminal:

pip install numpy pandas matplotlib seaborn scikit-learn xgboost tensorflow jupyter
This installs everything your project needs without a file.

✅ 2. Use a Virtual Environment (Recommended for Projects)
Keeps your dependencies isolated from your global Python environment.

🔹 Step-by-Step:

# Step 1: Create a virtual environment
python -m venv venv

# Step 2: Activate the environment
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate

# Step 3: Install packages inside the environment
pip install numpy pandas matplotlib seaborn scikit-learn xgboost tensorflow jupyter

# Step 4: (Optional) Freeze dependencies into a file
pip freeze > requirements.txt
✅ 3. Use conda (If You're Using Anaconda)
If you're working in Jupyter via Anaconda:

conda create -n solar-irradiance python=3.10
conda activate solar-irradiance
conda install numpy pandas matplotlib seaborn scikit-learn
pip install xgboost tensorflow jupyter

## Install dependencies 
pip install -r requirements.txt

##Launch Jupyter Notebook

jupyter notebook
Open Solar Irradiance Prediction.ipynb and run the cells step-by-step.

