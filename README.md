# 🚗 Car Price Predictor

A machine learning project to **predict the resale price of a car** based on various vehicle attributes using a **Linear Regression** model.

---

## 📚 Dataset
- **Source**: `Cardetails.csv`
- **Features**:
  - Car Brand (Name)
  - Year of Manufacture
  - Kilometers Driven
  - Fuel Type (Diesel, Petrol, LPG, CNG)
  - Seller Type (Dealer, Individual, Trustmark Dealer)
  - Transmission Type (Manual, Automatic)
  - Ownership History
  - Mileage (kmpl)
  - Engine Capacity (CC)
  - Max Power (bhp)
  - Number of Seats
- **Target**: Selling Price

**Note**: Dataset is not uploaded to GitHub due to size limitations.

---

## 🛠️ Workflow
1. **Data Cleaning**
   - Handling missing values
   - Encoding categorical variables
2. **Feature Selection**
   - Selecting relevant features impacting car price
3. **Model Building**
   - Linear Regression model
   - Model evaluation using R² Score and RMSE
4. **Model Deployment**
   - Streamlit application for interactive predictions

---

## 🚀 How to Run Locally

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Car-Price-Predictor.git
    cd Car-Price-Predictor
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate    # Linux/Mac
    venv\Scripts\activate      # Windows
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the Streamlit App:
    ```bash
    streamlit run car_price_app.py
    ```

---

## 📦 Requirements
> Example `requirements.txt` content:

```text
pandas>=1.5.3
numpy>=1.24.2
scikit-learn>=1.2.2
streamlit>=1.22.0
```

✅ Using common and stable versions to ensure smooth setup.

---

## 📁 Project Structure
```
Car-Price-Predictor/
├── car_price_app.py            # Streamlit web app script
├── car_price_model.pkl         # Saved Linear Regression model
├── requirements.txt            # List of required libraries
└── README.md                   # Project documentation
```

---

## 🌟 Future Enhancements
- Incorporate ensemble models (Random Forest, XGBoost)
- Deploy the app using platforms like Heroku or AWS
- Add additional car features for better prediction accuracy
- Implement model explainability (SHAP values)

---

## 👨‍💻 Author
**Nishnat Dangoria**  
_Passionate about building impactful machine learning projects!_

---

