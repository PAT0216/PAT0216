# Hi, I'm Prabuddha Tamhane 

**Data Scientist & ML Engineer** | Master of Data Science @ UBC | MBA Finance + B.Tech

I build data-driven solutions at the intersection of **finance** and **machine learning**.

[![Website](https://img.shields.io/badge/Portfolio-pat0216.github.io-00ff88?style=for-the-badge&logo=github)](https://pat0216.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-prabuddha--tamhane-0077B5?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/prabuddha-tamhane)

---



## Github Stats
<div align="center"><img src="https://streak-stats.demolab.com?user=pat0216&theme=default&hide_border=true" alt="pat0216's GitHub Stats" /><a href="https://awesome-github-stats.azurewebsites.net/index.html??cardType=level&fontFamily=&preferLogin=false"> <img  alt="pat0216's GitHub Stats" src="https://awesome-github-stats.azurewebsites.net/user-stats/pat0216?cardType=level&fontFamily=&preferLogin=false" />  </a></div>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/PAT0216/PAT0216/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/PAT0216/PAT0216/output/github-contribution-grid-snake.svg">
    <img alt="github contribution grid snake" src="https://raw.githubusercontent.com/PAT0216/PAT0216/output/github-contribution-grid-snake.svg">
  </picture>
</div>
  
---

## Featured Projects

### Square One Satellite Imagery Roof Classifier — Deep Learning & MLOps
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


### [Paper Trader AI — Algorithmic Trading System](https://github.com/PAT0216/paper-trader)

> A production-grade, serverless MLOps system with 3 predictive strategies competing live on the S&P 500.

- 📊 **Alpha-Driven Strategy Performance**: Achieved a **+18.8% Alpha over SPY** (cumulative excess return) and a **1.54 Sharpe ratio** over a **7-month live run** (Oct 2025 – May 2026), outperforming SPY (+3.94%) with a -9.1% maximum drawdown limit.
- 🤖 **Multi-Model Machine Learning Engine**: Evaluates three competing strategies: Fama-French momentum factor model, XGBoost classifier with 15 technical indicators (RSI, MACD, etc.), and an LSTM network utilizing 60-day price sequences across **503 tickers** backtested on **9 years** of historical data.
- ⚙️ **Dockerized AWS MLOps Pipeline**: Daily automated ETL pipelines and parallel inference scheduled via EventBridge and run on containerized AWS Lambda functions, persisting prediction logs to S3 and SQLite cache.
- 📈 **Streamlit Dashboard & CI/CD**: Live Streamlit application hosting real-time strategy returns, performance benchmark charts, and automated daily model health checks backed by automated GitHub Actions tests.
- 🔗 [Live Dashboard](https://paper-trader-ai.streamlit.app/)


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

## Technical Skills

### Programming Languages
[![Python](https://img.shields.io/badge/Language-Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org/)
[![SQL](https://img.shields.io/badge/Database-SQL-003B57?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![R](https://img.shields.io/badge/Language-R-276DC3?style=for-the-badge&logo=r&logoColor=white)](https://www.r-project.org/)
[![C++](https://img.shields.io/badge/Language-C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)](https://isocpp.org/)
[![C](https://img.shields.io/badge/Language-C-00599C?style=for-the-badge&logo=c&logoColor=white)](https://en.wikipedia.org/wiki/C_(programming_language))
[![Bash](https://img.shields.io/badge/Language-Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)](https://www.gnu.org/software/bash/)
[![JavaScript](https://img.shields.io/badge/Language-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/Language-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/Language-CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)

### Machine Learning & Computer Vision
[![PyTorch](https://img.shields.io/badge/Framework-PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white)](https://pytorch.org/)
[![TensorFlow](https://img.shields.io/badge/Framework-TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white)](https://www.tensorflow.org/)
[![Scikit-Learn](https://img.shields.io/badge/ML-Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![XGBoost](https://img.shields.io/badge/ML-XGBoost-1E90FF?style=for-the-badge)](https://xgboost.readthedocs.io/)
[![OpenCV](https://img.shields.io/badge/Library-OpenCV-white?style=for-the-badge&logo=opencv&logoColor=black)](https://opencv.org/)

### Data Engineering & Cloud Infrastructure
[![AWS](https://img.shields.io/badge/Cloud-AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/)
[![Docker](https://img.shields.io/badge/DevOps-Docker-0db7ed?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![GitHub Actions](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)](https://github.com/features/actions)
[![MLflow](https://img.shields.io/badge/MLOps-MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)](https://mlflow.org/)

### Databases & Columnar Storage
[![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![SQLite](https://img.shields.io/badge/Database-SQLite-07405e?style=for-the-badge&logo=sqlite&logoColor=white)](https://sqlite.org/)
[![DuckDB](https://img.shields.io/badge/Database-DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)](https://duckdb.org/)

### Analytics & Visualization
[![Streamlit](https://img.shields.io/badge/Visualization-Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)](https://streamlit.io/)
[![Tableau](https://img.shields.io/badge/Visualization-Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)](https://www.tableau.com/)
[![PowerBI](https://img.shields.io/badge/Visualization-PowerBI-F2C811?style=for-the-badge&logo=Power%20BI&logoColor=black)](https://powerbi.microsoft.com/)
[![Excel](https://img.shields.io/badge/Tool-Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel)

---

## Education

**Master of Data Science** — University of British Columbia *(2025-2026)*  
**MBA Finance + B.Tech Computer Engineering** — NMIMS University

---

## Let's Connect

- **Website:** [pat0216.github.io](https://pat0216.github.io)
- **LinkedIn:** [prabuddha-tamhane](https://linkedin.com/in/prabuddha-tamhane)

*Open to opportunities in Data Science, Machine Learning Engineering, Financial Analytics, and Business Analytics*
