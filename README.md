# Hi, I'm Prabuddha Tamhane 

**Data Scientist & ML Engineer** | Master of Data Science @ UBC | MBA Finance + B.Tech

I build data-driven solutions at the intersection of **finance** and **machine learning**.

[![Website](https://img.shields.io/badge/Portfolio-pat0216.github.io-00ff88?style=for-the-badge&logo=github)](https://pat0216.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-prabuddha--tamhane-0077B5?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/prabuddha-tamhane)

---

## Featured Project

### [Square One Satellite Imagery Roof Classifier](https://github.com/PAT0216/mds-satellite-imagery) — Deep Learning & MLOps
> An automated property attribute pre-filling pipeline using vision transformers and confidence
calibration.

- **Foundation Models:** Fine-tuned DINOv2 and RemoteCLIP vision transformers using parameter-
efficient unfreezing and Layer-Wise Learning Rate Decay (LLRD).
- **Background Masking Pipeline:** Integrated Microsoft Building Footprint and OpenStreetMap
polygons with a custom U-Net segmentation fallback to prevent background shortcut learning.
- **Underwriting Calibration:** Implemented Platt scaling and Isotonic regression calibration to
achieve 96.83% precision and 35.46% coverage at the 95% confidence threshold.
- **Experiment Tracking:** Logged and tracked hyperparameters, reliability curves, and UMAP
projections using MLflow hosted on AWS (EC2/S3).


### [Paper Trader AI](https://github.com/PAT0216/paper-trader) — Algorithmic Trading System
> A production-grade MLOps system with 3 strategies competing live on S&P 500 stocks

- 📊 **4.3M+ data points** | 503 tickers | 9 years backtested
- 🤖 Momentum vs XGBoost vs LSTM — competing head-to-head
- ⚙️ Automated daily trading via GitHub Actions + Docker
- 📈 [Live Dashboard](https://paper-trader-ai.streamlit.app/)


### [Amazon Product Query Assistant](https://github.com/UBC-MDS/Amazon_recommender_search_assistant) — Hybrid RAG Search Assistant
> An offline Retrieval-Augmented Generation (RAG) system for querying the Amazon Appliances
reviews dataset.

- **Hybrid Retrieval:** Combined BM25 lexical search (rank-bm25) and semantic vector search
using Sentence-Transformers (all-MiniLM-L6-v2) indexed via FAISS.
- **Local Generation:** Deployed a local Ollama LLM orchestration (Llama 3.2 3B) for generating
grounded answers with citations.
- **Data Engineering:** Developed a fast data ingestion and preprocessing pipeline leveraging
DuckDB to stream and convert raw reviews and metadata to Parquet format.
- **Web Interface:** Wrapped the retrieval and generation components in an interactive Streamlit
UI.

---

## Tech Stack
**Languages:** Python, SQL, R, C++, JavaScript  
**ML/Data:** PyTorch, TensorFlow, XGBoost, Scikit-learn, Pandas, NumPy, DuckDB, FAISS  
**Tools & Infrastructure:** Docker, GitHub Actions, Streamlit, MLflow, AWS (EC2, S3), Git, PostgreSQL

---

## Education

**Master of Data Science** — University of British Columbia *(2025-2026)*  
**MBA Finance + B.Tech Computer Engineering** — NMIMS University

---

## Let's Connect

- **Website:** [pat0216.github.io](https://pat0216.github.io)
- **LinkedIn:** [prabuddha-tamhane](https://linkedin.com/in/prabuddha-tamhane)

*Open to opportunities in Data Science, Machine Learning Engineering, Financial Analytics, and Business Analytics*
