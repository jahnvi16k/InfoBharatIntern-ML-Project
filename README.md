# Bike Rental Prediction using Machine Learning
This project was developed as part of the **Info Bharat Interns (NeuroNova)** internship. The goal is to predict bike rental counts based on weather and time-based features using machine learning.
## 🎯 Objective

To build a predictive model that accurately estimates the number of bike rentals based on features such as date, time, weather conditions, and holiday information.

## 📊 Dataset

- **Source:** [Bike Sharing Demand - Kaggle](https://www.kaggle.com/c/bike-sharing-demand)
- The dataset contains daily and hourly data on bike rentals.
- Key features:
  - `datetime`: Date and hour of the rental
  - `season`, `holiday`, `workingday`: Indicators for conditions
  - `weather`, `temp`, `atemp`, `humidity`, `windspeed`: Weather-related data
  - `casual`, `registered`, `count`: Rental counts
 
## 🛠️ Technologies Used

- Python
- Jupyter Notebook (Google Colab)
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

## 🧠 Machine Learning Models
Two different regression models were implemented and compared:

- **Linear Regression:** A simple model to establish a baseline prediction.
- **Random Forest Regressor:** An ensemble model that improved accuracy by reducing overfitting and handling non-linear relationships.

### 📏 Evaluation Metrics
- **RMSE (Root Mean Squared Error)**
- **R² Score**

## 📈 Results

- The **Random Forest Regressor** performed better than Linear Regression.
- It achieved a higher R² Score and a lower RMSE, indicating better prediction accuracy.
- The model was able to capture patterns related to working days, weather, and time-based trends effectively.

## 📁 Project Structure


> 📌 **Tip:** If you haven’t uploaded all these files yet, don’t worry — this is just a suggested structure. You can update it later after you upload them.

---

After this, type **“next”** and we’ll move to the **How to Run** section.

## 🚀 How to Run

1. Clone the repository or download the ZIP file.
2. Open the `bike_rental_prediction.ipynb` file in **Google Colab** or **Jupyter Notebook**.
3. Make sure required libraries (like pandas, numpy, scikit-learn) are installed.
4. Run the cells in order to train the model and see the predictions.






