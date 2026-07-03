
# AQI & Respiratory Health Correlation Analysis
### Leveraging Machine Learning and LLM-RAG Architecture for Air Quality and COPD Insights

## Overview

This project investigates the correlation between Air Quality Index (AQI) and Chronic Obstructive Pulmonary Disease (COPD) prevalence using machine learning models and a Retrieval-Augmented Generation (RAG) pipeline built on open-source Large Language Models (LLMs).

The system enables data-driven analysis of how air pollutants — including PM2.5, PM10, and atmospheric gases — impact respiratory health outcomes, with a focus on Indian datasets and real-world feasibility.

## Tech Stack

| Layer | Tools |
| Language | Python |
| Data Processing | Pandas, NumPy |
| Machine Learning | Scikit-learn, XGBoost, LightGBM |
| Embeddings | Sentence Transformers |
| Vector Databases | FAISS, ChromaDB |
| Backend API | FastAPI |
| Frontend | Streamlit |
| Database | SQL |
| LLM | Open-source models (local deployment) |
| Version Control | Git, GitHub |

## Project Structure

```
├── data/               # Raw and processed datasets
├── notebooks/          # Exploratory data analysis and experiments
├── models/             # Trained model artifacts
├── embeddings/         # Vector store and embedding configs
├── api/                # FastAPI backend
├── app/                # Streamlit frontend
├── literature/         # Literature review summaries
└── docs/               # Project documentation and reports
```

---

## Key Features

- Correlation analysis between AQI metrics and COPD incidence using ML models
- RAG pipeline for intelligent querying of domain literature and health data
- Interactive dashboard for data visualisation and model inference
- Modular architecture supporting multiple open-source LLMs

## Datasets

Sourced from Indian repositories including:
- Central Pollution Control Board (CPCB)
- data.gov.in : city-wise AQI records
- ICMR & NFHS : epidemiological health data

## Status

🟡 **In Progress** — Implementation phase initiated

- [x] Literature review completed (15+ papers)
- [x] Tech stack finalised
- [x] Repository initialised
- [ ] Data preprocessing pipeline
- [ ] Model training and evaluation
- [ ] RAG pipeline integration
- [ ] Frontend deployment

---

## License

This project is for academic and research purposes only.
