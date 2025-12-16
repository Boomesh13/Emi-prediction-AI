#💵 Emi-prediction-AI

An intelligent Streamlit web app that predicts a user's EMI eligibility, identifies High-Risk applicants, and estimates their maximum affordable EMI using Machine Learning models trained on real-world financial data.

📝Overview
EMIPredict AI helps financial institutions and individuals evaluate EMI loan eligibility.
It uses a trained classification model to determine the risk category:

❌ Not Eligible
🚨 High Risk
✅ Eligible
and a regression model to estimate the maximum monthly EMI the applicant can afford.

 🧠Features
✅ EMI eligibility classification (Eligible / High Risk / Not Eligible)
✅ Confidence scores for each class
✅ EMI amount prediction (regression model)
✅ Interactive data visualization using Plotly and Seaborn
✅ Admin & Model Monitoring panel
✅ Cached model loading for fast performance
✅ Deployed seamlessly on Streamlit Cloud

🧩 Tech Stack
## 🧩 Tech Stack

| Component | Technology |
| :--- | :--- |
| **Frontend** | Streamlit |
| **Backend / Models** | Python, scikit-learn, joblib |
| **Visualization** | Plotly, Matplotlib, Seaborn |
| **Model Tracking** | MLflow |
| **Deployment** | Streamlit Cloud |
| **Data Handling** | Pandas, NumPy |

🗂️ Project Structure
Emi-prediction-AI/ │ ├── app.py # Main Streamlit app ├── emi_prediction_dataset.csv # Training dataset (required) ├── models/ │ ├── bestmodel_emi_classifier.pkl # Classification model │ └── bestmodel_emi_regressor.pkl # Regression model │ ├── requirements.txt # All dependencies ├── README.md # Project documentation └── screenshots/ # (Optional) App screenshots

Install Dependencies
pip install -r requirements.txt
Run Locally
streamlit run app.py
Then open the link shown in the terminal (usually http://localhost:8501)
🧾 Requirements
streamlit pandas numpy matplotlib seaborn plotly mlflow joblib scikit-learn

📈 MLflow Tracking
mlflow ui --port 5007
Then open → http://localhost:5007
🌐 Deployment on Streamlit Cloud
Push your repository to GitHub

Go to Streamlit Cloud

Connect the repo and deploy

Make sure these files exist in GitHub:

app.py

requirements.txt

models/bestmodel_emi_classifier.pkl

models/bestmodel_emi_regressor.pkl

emi_prediction_dataset.csv

🖼️ Screenshots(ML Flow UI)

<img width="1897" height="1024" alt="image" src="https://github.com/user-attachments/assets/57e014f8-446f-4fe3-9de0-8e3c4b3840d0" />


