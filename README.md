# Smart Healthcare Management Platform



An AI-powered full-stack healthcare analytics platform designed to assist clinicians in predicting chronic disease risks, monitoring patient health trends, and generating explainable AI-driven insights through interactive dashboards and real-time analytics.



The platform integrates advanced machine learning models, forecasting architectures, explainable AI techniques, and REST-based backend services to provide intelligent patient risk assessment and clinical decision support.



---



# Features



- Chronic disease risk prediction system

- Real-time patient health analytics

- Interactive clinician dashboard

- Explainable AI insights using SHAP

- CSV-based bulk patient analysis

- Forecasting patient deterioration trends

- REST API integration using FastAPI

- Multi-condition patient risk assessment

- AI-generated healthcare insights using Gemini API

- Responsive and modern healthcare UI



---



# Tech Stack



## Frontend

- NextJS

- ReactJS

- TypeScript

- Tailwind CSS



## Backend

- FastAPI

- Python



## Machine Learning & AI

- XGBoost

- Random Forest

- PyTorch Forecasting

- Temporal Fusion Transformer (TFT)

- SHAP

- Gemini API



---


# System Architecture



```text

Frontend (NextJS + ReactJS)

        ↓

FastAPI Backend Services

        ↓

ML Prediction Engine

(XGBoost / Random Forest / TFT)

        ↓

SHAP Explainability Layer

        ↓

Gemini API Insights Generation

```




# Project Structure

```bash
Smart-Healthcare-Management-Platform/
│
├── Dashboard Components/      # Healthcare Dashboard UI Components
├── ML Models/                 # Trained ML & Forecasting Models
├── app/                       # NextJS App Router Pages
├── components/                # Reusable React Components
├── hooks/                     # Custom React Hooks
├── lib/                       # Utility Functions & Services
├── metrics images/            # Model Metrics & Evaluation Graphs
├── public/                    # Static Assets
├── styles/                    # Global Styles
│
├── test_data.csv              # Sample Healthcare Dataset
├── package.json               # Project Dependencies
├── tsconfig.json              # TypeScript Configuration
├── next.config.mjs            # NextJS Configuration
└── README.md
```

---


# AI & ML Capabilities



## Disease Prediction Models

The platform integrates multiple machine learning models for disease prediction and patient risk scoring:



- XGBoost

- Random Forest

- Temporal Fusion Transformer (TFT)



These models were trained and evaluated on healthcare datasets to predict disease progression and deterioration risks with high accuracy.



### Performance

- Achieved up to **92.4% AUROC**

- Improved interpretability using SHAP explainability

- Enabled real-time prediction workflows



---



# Explainable AI



The platform incorporates SHAP (SHapley Additive Explanations) to provide transparent model predictions.



Clinicians can:

- Understand feature importance

- Visualize prediction contributions

- Interpret model behavior

- Improve trust in AI-generated healthcare decisions



---



# Forecasting System



Using Temporal Fusion Transformer (TFT) models built with PyTorch Forecasting, the platform predicts future patient deterioration trends and helps clinicians identify high-risk cases early.



The forecasting system supports:

- Time-series patient analysis

- Trend prediction

- Temporal health monitoring

- Sequential healthcare forecasting











