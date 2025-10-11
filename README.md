# 💻 Laptop Price Prediction using Machine Learning

This project predicts the price of a laptop based on its specifications such as brand, processor type, RAM, storage, and display features.  
It uses advanced **machine learning algorithms** and a **Streamlit web app** for an interactive user experience.

---

## 🚀 Live Demo  
👉 **Streamlit App:** [Click Here to Try It!](https://laptop-price-prediction-pwtaikqpb6pxwqrdl2hbh2.streamlit.app/)

---

## 📘 Project Overview
The goal of this project is to build an ML model that accurately predicts laptop prices based on their configurations.  
By analyzing different hardware and brand features, this model helps estimate a fair market price for laptops.

### Key Objectives
- Build a regression model for laptop price prediction  
- Perform Exploratory Data Analysis (EDA) to understand feature relationships  
- Deploy a user-friendly web app using Streamlit  

---

## 🧠 Tech Stack
- **Programming Language:** Python  
- **Web Framework:** Streamlit  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Model Used:** Random Forest Regressor / XGBoost Regressor  

---

## ⚙️ Features
✅ Clean, interactive Streamlit interface  
✅ Predicts laptop prices in real-time  
✅ Accepts user inputs for key laptop specs  
✅ Displays predicted price instantly  
✅ Modular and reusable code structure  

---

## 🔍 Workflow
1. **Data Collection & Cleaning:** Handled missing values, duplicates, and irrelevant features  
2. **Feature Engineering:** Encoded categorical variables and created derived attributes  
3. **EDA:** Used visualizations to identify key factors affecting price  
4. **Model Training:** Trained and compared multiple regression models  
5. **Evaluation:** Selected the best-performing model using RMSE and R² score  
6. **Deployment:** Built and deployed an interactive Streamlit web app  

---

## 🧩 Installation & Setup

### 1️⃣ Clone the repository

git clone https://github.com/yourusername/laptop-price-prediction.git
cd laptop-price-prediction

### 2️⃣ Create a Virtual Environment

python -m venv .venv

### 3️⃣ Activate the Environment

source .venv/Scripts/activate

### 4️⃣ Install Dependencies

pip install -r requirements.txt

### 5️⃣ Run the Streamlit App

streamlit run app.py

### 6️⃣ Open in Browser

After running the above command, Streamlit will display a local URL (like http://localhost:8501).
Click the link or paste it into your browser to launch the app.

---

## 📈 Model Performance

Achieved strong predictive performance with R² Score > 0.85
Random Forest Regressor produced the most reliable results
Model efficiently generalizes across various brands and configurations

## 📊 EDA Insights

Processor Type, RAM, and Brand were among the strongest predictors of price
High-end GPUs and SSDs significantly increase laptop prices

## 👨‍💻 Author

Anand Mehto
📧 anandmehto78@gmail.com
🔗 linkedin.com/in/anandmehto

## 🏆 Acknowledgment

This project was developed as part of my Data Science learning journey to demonstrate:
End-to-end ML workflow (EDA → Feature Engineering → Model Building → Deployment)
Real-world problem solving through data-driven decision-making
