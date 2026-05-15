# 🏥 Insurance Premium Prediction API

A modern Machine Learning powered REST API that predicts **Insurance Premium Categories** based on user health and demographic information.

Built using **FastAPI**, **Scikit-learn**, and **Pydantic**, this project demonstrates real-world ML model deployment with clean backend architecture, input validation, automated feature engineering, and Docker support.

---

# ✨ Features

- 🤖 Machine Learning Premium Prediction
- 📊 Confidence Score & Probability Distribution
- 🧠 Automatic Feature Engineering
- 📦 Clean FastAPI Architecture
- ✅ Pydantic Input Validation
- ⚡ High Performance REST APIs
- 🐳 Docker Support
- 📈 Health Monitoring Endpoint
- 🔍 Model Version Tracking
- 🧮 BMI & Lifestyle Risk Calculation

---

# 🏗️ Architecture

This project follows:

- 🧱 Clean Project Structure
- 🤖 ML Inference Architecture
- 📦 Modular API Design
- ⚡ FastAPI REST Standards

### 🔄 Workflow

```bash
User Input → Feature Engineering → ML Model → Prediction Response
````

---

# 📂 Project Structure

```bash
InsurancePremium/
│
├── app.py
│
├── model/
│   ├── model.pkl
│   └── predict.py
│
├── schema/
│   ├── user_input.py
│   └── prediction_response.py
│
├── config/
│   └── city_tier.py
│
├── Dockerfile
├── requirements.txt
└── README.md
```

---

# 🛠️ Tech Stack

| Technology        | Usage                     |
| ----------------- | ------------------------- |
| 🐍 Python         | Main Programming Language |
| ⚡ FastAPI         | Backend API Framework     |
| 🤖 Scikit-learn   | Machine Learning Model    |
| 📦 Pydantic       | Data Validation           |
| 🚀 Uvicorn        | ASGI Server               |
| 🐳 Docker         | Containerization          |
| 📊 NumPy / Pandas | Data Processing           |

---

# 🤖 Machine Learning Features

The API automatically computes additional features before prediction:

| Feature           | Description                               |
| ----------------- | ----------------------------------------- |
| 🧮 BMI            | Calculated using weight & height          |
| 🚬 Lifestyle Risk | Derived from smoking & BMI                |
| 👨 Age Group      | Categorized age segmentation              |
| 🌆 City Tier      | Metro / Major / Other city classification |

---

# 📡 API Endpoints

| Method | Endpoint   | Description                        |
| ------ | ---------- | ---------------------------------- |
| `GET`  | `/`        | Welcome Endpoint                   |
| `GET`  | `/health`  | API & Model Health Status          |
| `POST` | `/predict` | Predict Insurance Premium Category |

---

# 📥 Prediction Input

The API accepts:

* 👤 Age
* ⚖️ Weight
* 📏 Height
* 💰 Income
* 🚬 Smoking Status
* 🌆 City
* 💼 Occupation

---

# 📤 Prediction Response

The API returns:

* 🎯 Predicted Premium Category
* 📊 Confidence Score
* 📈 Class Probability Distribution

### Example Response

```json
{
  "predicted_category": "High",
  "confidence": 0.8432,
  "class_probabilities": {
    "Low": 0.01,
    "Medium": 0.15,
    "High": 0.84
  }
}
```

---

# 🧠 Feature Engineering Logic

| Computed Field | Logic                                |
| -------------- | ------------------------------------ |
| BMI            | `weight / height²`                   |
| Lifestyle Risk | Based on smoker status & BMI         |
| Age Group      | Young / Adult / Middle Aged / Senior |
| City Tier      | Tier-1 / Tier-2 / Tier-3             |

---

# 🐳 Docker Support

The project is fully containerized and Docker-ready for deployment and scalable environments.

---

# 📚 API Documentation

Interactive Swagger API documentation available through FastAPI.

```bash
/docs
```

---

# 🎯 Project Goals

This project was built to showcase:

* Machine Learning Model Deployment
* FastAPI Backend Development
* Real-world Prediction APIs
* Feature Engineering
* Production-Level API Design
* Dockerized ML Applications
* Clean & Scalable Architecture

---
```
```
