# 🚗 Car Price Predictor

This project predicts the resale price of a car based on its features such as manufacturing year, kilometers driven, fuel type, seller type, transmission type, ownership history, mileage, engine capacity, and maximum power.

## 📚 Dataset
- **Source**: `Cardetails.csv`
- **Features**:  
  - Car brand (name)
  - Year of manufacture
  - Kilometers driven
  - Fuel type (Diesel, Petrol, LPG, CNG)
  - Seller type (Dealer, Individual, Trustmark Dealer)
  - Transmission (Manual, Automatic)
  - Ownership history
  - Mileage (kmpl)
  - Engine capacity (CC)
  - Max power (bhp)
  - Number of seats
- **Target**: Selling price

## 🛠 Model Details
- **Model Used**: Linear Regression
- **Libraries**: scikit-learn, pandas, numpy
- **Output**: Selling Price Prediction (in ₹ INR)

## 🚀 How to Run Locally
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Car-Price-Predictor.git
    cd Car-Price-Predictor
    ```

2. Install required libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Streamlit App:
    ```bash
    streamlit run car_price_app.py
    ```

## 📦 Requirements
- Python 3.10+
- pandas
- numpy
- scikit-learn
- streamlit

## 🎯 Project Structure
