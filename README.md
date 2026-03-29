# Cleber F. Carvalho

**Machine Learning Engineer · AI Systems · LLM Applications**

ML Engineer with a background spanning production software delivery, applied research,
and AI systems development. Two years of graduate-level ML research at Kyoto University
of Advanced Science (healthcare AI, time series forecasting, LSTM architectures).
Four years of production Android engineering at a French assistive technology company,
deploying systems used by 3,000+ users across France, Belgium, and Switzerland.

Currently building production-oriented AI systems under **Iskra Labs**, an independent
engineering initiative focused on LLM applications, RAG pipelines, and measurable
system design.

Olá! 🇧🇷 · Cześć! 🇵🇱 · こんにちは! 🇯🇵 · ¡Hola! 🇪🇸

---

## Selected Work

### [Clinical Evidence Navigator](https://github.com/cleberfc23/clinical-evidence-navigator)
RAG system for querying clinical guidelines with citation-backed, hallucination-mitigated
responses.

- Modular architecture: decoupled ingestion → ChromaDB → LangGraph inference → FastAPI → Streamlit
- End-to-end latency reduced from ~358s to ~7.1s (>98% improvement)
- Stack: LangChain · LangGraph · ChromaDB · HuggingFace · Gemini · FastAPI · Docker

---

### [Sygnały — Public Signals Mining](https://github.com/cleberfc23/sygnaly-miner)
NLP pipeline for discovering themes and emerging signals in large Polish-language text
corpora.

- Dataset: 248,123 documents (Polish news corpus); 2,890-document high-quality subset
  after cleaning (~96.3% retention)
- Pipeline: text preprocessing → CountVectorizer → KMeans (k=8) → PCA visualization
- Live demo: [sygnaly-miner.streamlit.app](https://sygnaly-miner.streamlit.app/)
- Stack: Python · NLP · scikit-learn · Sentence Embeddings · Streamlit · Docker

---

### [Clinical SQL Analytics — Diabetes Readmissions](https://github.com/cleberfc23/clinical-sql-analytics-diabetes-readmissions)
SQL and Python pipeline for analyzing hospital readmission patterns in diabetic patients.

- Modelled 101,766 encounters across 71,518 patients; risk buckets with readmission
  rates from 35.52% (low) to 50.58% (high)
- Stack: SQL · Python · Pandas · SQLite

---

## Core Technologies

**AI & ML** — LangChain · LangGraph · HuggingFace · OpenAI · Gemini · RAG ·
vector search · LLM evaluation  
**ML Frameworks** — PyTorch · TensorFlow · scikit-learn · time-series forecasting  
**Data** — Pandas · NumPy · analytical SQL · MLflow  
**Languages** — Python · SQL · Kotlin · Java  
**Tools** — Docker · FastAPI · Streamlit · Git · Jupyter  
**Cloud** — GCP · Vertex AI · BigQuery

---

## Background

**ML Research · Kyoto University of Advanced Science** (2023–2025)
Graduate-level research on LSTM architectures for short-term glucose prediction.
Benchmarked recurrent and convolution-enhanced variants across 250+ patients (T1/T2
diabetes cohorts). Identified and mitigated time-series data leakage revealing up to
28% inflated NRMSE; improved cross-dataset generalisation by up to 14% MAE / 30% NRMSE.

**Android Engineer · JIB, France** (2019–2023)
Production delivery of assistive smart home Android applications (Kotlin, Jetpack
Compose, MVVM, IoT/Tuya SDK). Deployed across France, Belgium, and Switzerland —
3,000+ users, 1,000+ households, ~40 healthcare institutions.

---

## Open to Opportunities

Available for **remote roles based in Poland**.
Based in Brazil · open to relocation discussions.

[LinkedIn](https://www.linkedin.com/in/cleberfc23/) · cleberfc23@gmail.com
