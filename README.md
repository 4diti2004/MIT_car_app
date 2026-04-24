🚗 Car Price Prediction App

 📌 Description

This project is a Machine Learning-based web application that predicts the price of used cars based on user inputs such as insurance type, fuel type, kilometers driven, ownership, transmission, and registration year. The application is built using Python and Streamlit.

---

🎯 Objectives

* Perform data preprocessing and feature encoding
* Train a regression model for car price prediction
* Deploy the model using a Streamlit web application

---
🛠️ Technologies Used

* Python
* Streamlit
* Scikit-learn
* Pandas
* NumPy

---

 📂 Project Structure

```id="djqh56"
CAR_PREDICT_APP/
│── app.py                      # Streamlit application
│── final_model.pkl             # Trained ML model
│── scaler.pkl                  # Data scaler
│── Car Dataset Processed.csv   # Dataset
│── model.ipynb                 # Model training notebook
│── models.ipynb                # Additional notebook
│── requirements.txt            # Dependencies
│── README.md                   # Project documentation
```

---

⚙️ Installation & Setup

1. Create Virtual Environment

```id="lglx96"
python -m venv venv
venv\Scripts\activate
```

 2. Install Dependencies

```id="9v6tdz"
pip install -r requirements.txt
```

---

 ▶️ How to Run the Project

```id="up6t3t"
streamlit run app.py
```

---

 🌐 Application Usage

Open your browser and go to:

```
http://localhost:8501/
```

Enter the following details:

* Insurance Validity
* Fuel Type
* KMs Driven
* Ownership
* Transmission
* Registration Year

The application will predict:

* Car Price in Lakhs
* Approximate Price in INR (₹)

---

⚙️ How It Works

* User inputs are converted into numerical format using dictionaries
* Data is scaled using `scaler.pkl`
* Prediction is made using `final_model.pkl`

Reference implementation: 

---

 📊 Input Features

* Insurance Validity
* Fuel Type
* KMs Driven
* Ownership
* Transmission
* Registration Year

---

 📈 Output

* Predicted Car Price (in Lakhs)
* Price converted into Indian Rupees (₹)

---

📦 Dependencies

All required libraries are listed in: 

---

 📸 Screenshots

<img width="587" height="483" alt="image" src="https://github.com/user-attachments/assets/77b5a839-8afd-4dc3-bc1f-9cccc8812272" />
<img width="550" height="128" alt="image" src="https://github.com/user-attachments/assets/07e1dea9-bcf8-4e10-8c30-b31b708388bb" />



---

🌟 Future Scope

* Improve model accuracy
* Add more input features
* Deploy application online
* Enhance UI design

---

 👩‍💻 Author

Aditi Deshpande

---

 ⭐ Conclusion

This project demonstrates how Machine Learning can be used to predict car prices and deployed as an interactive web application using Streamlit.
