# Rahul N

Software Engineer focused on Backend Development and Applied AI
Python · FastAPI · PostgreSQL · NLP · ML

---

## What I Work On

I build backend services and ML pipelines primarily in Python. My recent work sits across two areas: REST API development with FastAPI and PostgreSQL, and applied machine learning covering NLP, classification, and explainability tooling (SHAP).

The projects below are portfolio and learning projects. They are not currently deployed to production environments, but are built with the intent of reflecting real engineering decisions — data modelling, API design, model evaluation, and system integration.

---

## Projects

### [ai-hiring-copilot](https://github.com/rahul4018/ai-hiring-copilot)

A resume parsing and candidate-matching tool. Uses spaCy for named-entity extraction from resume text, scores candidates against job descriptions, and presents ranked results in a Streamlit dashboard. The backend is FastAPI with PostgreSQL persistence. Also integrates a locally-run LLM for generating candidate summaries, avoiding external API calls.

**Stack:** Python, FastAPI, PostgreSQL, spaCy, Streamlit, local LLM inference

---

### [lightweight-ai-network-threat-detection](https://github.com/rahul4018/lightweight-ai-network-threat-detection)

A network intrusion detection classifier built on a standard IDS dataset. Trains a scikit-learn model to classify traffic as benign or malicious, adds SHAP values to explain per-prediction feature attribution, and serves both the predictions and explanations over a FastAPI endpoint. Includes a dashboard UI styled as a SOC (Security Operations Center) view.

The SHAP integration was a deliberate design choice — classification alone gives you a verdict, but SHAP makes the contributing features visible, which matters in a security context.

**Stack:** Python, FastAPI, scikit-learn, SHAP, HTML/CSS dashboard

---

### [Predictive-Maintenance-AI4I2020](https://github.com/rahul4018/Predictive-Maintenance-AI4I2020)

An ML experiment on the [AI4I 2020 Predictive Maintenance dataset](https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset) — a public benchmark for industrial machine failure prediction. Covers exploratory data analysis, feature engineering, and comparison of multiple classifiers (logistic regression, random forest, gradient boosting). The goal was to identify the model and feature set that best detects early failure signals.

This is a Jupyter-based research project, not a served application.

**Stack:** Python, Jupyter, scikit-learn, pandas, matplotlib

---

### [senapransakthi](https://github.com/rahul4018/senapransakthi)

A full-stack application combining a Python ML backend with a TypeScript frontend. The backend handles data ingestion and model inference; the frontend displays results in real time. Built to practise wiring together a model-serving backend with a reactive UI rather than keeping them as separate notebooks and scripts.

**Stack:** Python, TypeScript, REST API

---

### [pharmacy-management-system](https://github.com/rahul4018/pharmacy-management-system-porject)

A management tool for small pharmacies covering medicine inventory, billing, sales tracking, and customer records. Designed with local deployment in mind — small medical stores that need basic record-keeping without a cloud dependency.

**Stack:** Python

---

### [weather-dashboard](https://github.com/rahul4018/weather-dashboard)

A frontend dashboard that fetches and displays live weather data from a public weather API. Demonstrates API integration, basic state management, and TypeScript usage on the frontend.

**Stack:** TypeScript, HTML, CSS, REST API

---

## Stack

```
Languages:   Python (primary), TypeScript
Backend:     FastAPI, REST API design, PostgreSQL
ML/NLP:      scikit-learn, spaCy, SHAP, pandas, matplotlib
Serving:     local LLM inference (Ollama / similar), Streamlit, FastAPI
```

---

Bengaluru · he/him · [GitHub](https://github.com/rahul4018)
