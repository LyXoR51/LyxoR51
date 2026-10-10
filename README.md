<h1 align="center">Florent Proust</h1>

<p align="center">
  <strong>AI Engineer · MLOps</strong>
</p>

<p align="center">
  After 10 years in technical roles across the cosmetics, pharmaceutical and automotive industries, I moved into AI engineering. I build and ship LLM applications and ML systems end to end: agents, RAG, training and CI/CD pipelines, monitoring, containerized deployment.<br><br>
  My focus is on making AI systems reliable and production-ready: guardrails, observability, reproducible deployments.
</p>
<p align="center">
  🔗 <a href="https://www.linkedin.com/in/florent-proust-49334a90/" target="_blank">Connect with me on LinkedIn</a>
</p>

---

## Projects

### Bob – Multi-Agent AI Assistant (LLM Engineering)

🚀 [Live Demo](https://maintenance-ai.fp-data-ia.fr/) • 📝 [GitHub Repo](https://github.com/LyXoR51/bob-maintenance-assistant)

Personal **AI assistant for vehicle maintenance**, self-hosted and used in production. A classifier routes each question to a specialized agent: a **SQL agent** over the maintenance history (PostgreSQL, read-only role) or a **RAG agent** over technical manuals (Qdrant, FastEmbed). A **deterministic response guard** checks dates, mileages and types against the raw tool results to catch hallucinations, and a small **Ministral 3B** model is kept reliable through tool design rather than model size. Built with **LangChain, Mistral API, Streamlit, PostgreSQL, Qdrant, Docker, Caddy**, with LangSmith tracing.


### Est’Immo – Real Estate Price Estimation Platform - MLOps

🚀 [Live Demo](https://lyx51-housing-price-estimator-streamlit.hf.space) • 📝 [GitHub Repo](https://github.com/LyXoR51/Housing_price_estimator) 

AI-driven platform for real estate price prediction with a **full MLOps pipeline**: training, CI/CD, monitoring, and deployment. Built with **FastAPI, Streamlit, MLflow, Airflow, Docker, Jenkins**.


### Real-time Credit Card Fraud Detection – MLOps Platform

🚀 [Live Demo](https://lyx51-fraud-detection-streamlit.hf.space/) • 📝 [GitHub Repo](https://github.com/LyXoR51/projet_fraud_detection_credit_card)


AI-driven **credit card fraud detection system** featuring an **end-to-end MLOps pipeline** for data ingestion, validation, batch prediction, and alerting.
Built with **Airflow, MLflow, FastAPI, Streamlit, PostgreSQL, Docker**, and **XGBoost**, with cloud deployment on **Hugging Face, NeonDB, and AWS S3**.


### Anime Recommendation Engine - LLM / NLP

🚀 [Live Demo](https://lyx51-anime-recommandation-streamlit.hf.space) • 📝 [GitHub Repo](https://github.com/LyXoR51/Anime_recommandation_engine)

**AI-powered anime recommendation platform** leveraging **LLMs**, **semantic embeddings**, and **sentiment analysis** to deliver **personalized suggestions**. Built with **Transformers**, **Streamlit**, and **Docker** for reproducibility and interactive exploration.


## Infrastructure & Learning

### MLflow Server Deployment

🌐 [Live Server](https://lyx51-mlflow-server.hf.space) • 📝 [GitHub Repo](https://github.com/LyXoR51/mlflow_server) 

**Base repository providing multiple configurations** to deploy and test an **MLflow tracking server** locally, on **Hugging Face Spaces**, or via **remote endpoints**. Demonstrates hands-on **MLOps experience**, including containerized deployment and production-ready setups.


### Personal Tech Exploration

📝 [GitHub Repo](https://github.com/LyXoR51/learning_journey) 

A personal repository documenting my **learning journey across multiple technologies**, starting with **Python** and **SQL**, with hands-on exercises, projects, and experiments.
