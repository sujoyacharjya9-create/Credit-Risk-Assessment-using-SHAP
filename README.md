# 💳 Credit Risk Assessment Using SHAP

An end-to-end Machine Learning project focused on predicting credit risk using customer financial data. The project uses an XGBoost model to assess credit risk and SHAP to understand the factors influencing model predictions.

It also includes a FastAPI backend and a simple web interface to make the prediction system accessible.

## 🚀 About the Project

In the banking and financial industry, assessing a customer's credit risk is an important part of the loan approval process. Financial institutions need to understand whether a customer is likely to repay a loan or has a higher probability of default.

The goal of this project is to build a Machine Learning-based system that can predict credit risk from customer information.

Along with predictions, SHAP is used to explain how different features contribute to the model's decisions, making the results easier to understand.

## ✨ Features

- **Credit Risk Prediction:** Predicts customer credit risk using financial information.
- **XGBoost Classifier:** Uses XGBoost to build the prediction model.
- **SHAP Explainability:** Explains how different features influence model predictions.
- **Threshold Optimization:** Uses an optimized classification threshold to improve decision-making.
- **FastAPI Backend:** Handles prediction requests through API endpoints.
- **Web Interface:** Provides a simple interface built with HTML, CSS, and JavaScript.
- **Model Persistence:** Saves and loads trained models using Joblib.

## 🛠️ Technologies Used

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Machine Learning | Scikit-learn, XGBoost |
| Explainable AI | SHAP |
| Data Processing | Pandas, NumPy |
| Backend Framework | FastAPI |
| API Server | Uvicorn |
| Model Serialization | Joblib |
| Frontend | HTML, CSS, JavaScript |
| Development Tools | Jupyter Notebook, VS Code |

## 📂 Project Structure

```text
Credit-Risk-Assessment-using-SHAP/
│
├── static/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── Credit_Risk.ipynb
├── credit_risk_dataset.csv
├── credit_risk_model.pkl
├── best_threshold.pkl
├── main.py
├── render.yaml
├── requirements.txt
├── runtime.txt
└── .gitignore
```

## ⚙️ Installation and Setup

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/sujoyacharjya9-create/Credit-Risk-Assessment-using-SHAP.git
```

### 2. Navigate to the Project Folder

```bash
cd Credit-Risk-Assessment-using-SHAP
```

### 3. Create a Virtual Environment

```bash
python3 -m venv venv
```

Activate the environment:

**macOS / Linux**

```bash
source venv/bin/activate
```

**Windows**

```bash
venv\Scripts\activate
```

### 4. Install the Required Libraries

```bash
pip install -r requirements.txt
```

### 5. Start the FastAPI Application

```bash
uvicorn main:app --reload
```

### 6. Open the Application

Once the server starts, open the following URL in your browser:

**Web Application:**

http://127.0.0.1:8000

**FastAPI Documentation:**

http://127.0.0.1:8000/docs

## 📊 Model Explainability Using SHAP

SHAP (SHapley Additive exPlanations) is an Explainable AI technique based on cooperative game theory.

It helps us understand how individual input features affect a Machine Learning model's predictions.

In this project, SHAP is used to:

- Understand the contribution of individual features.
- Identify factors that influence credit risk predictions.
- Make model decisions easier to interpret.
- Improve the transparency of the prediction process.

The `Credit_Risk.ipynb` notebook contains the model development and analysis workflow.

## 📦 Model Files

The project uses two saved model files:

- `credit_risk_model.pkl` – Contains the trained Machine Learning model.
- `best_threshold.pkl` – Stores the optimized classification threshold.

Both files are loaded by the FastAPI application when it starts.

## 🔮 Future Improvements

Some areas that can be explored to improve the project further:

- Add more detailed SHAP visualizations.
- Improve the frontend design and user experience.
- Add additional model evaluation metrics.
- Implement model monitoring.
- Improve application scalability and deployment.

## 👨‍💻 Author

**Sujoy Acharjya**

B.Tech in Computer Science and Engineering (AI & ML)

GitHub: [@sujoyacharjya9-create](https://github.com/sujoyacharjya9-create)

---

If you find this project useful or interesting, feel free to ⭐ the repository!
