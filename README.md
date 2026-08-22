<div align="center">

# Sourjya Mukherjee
### Machine Learning · Data Science · AI Systems 

ECE graduate (B.Tech, 2026) building production-grade ML systems:
from deep learning research to deployed, tested, containerized applications.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sourjya-mukherjee)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mukherjeesourjya081@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-000000?style=for-the-badge&logo=readdotcv&logoColor=white)](https://drive.google.com/file/d/1oJOqu5oYsxDaLBOjDmLVH4xUOTSnBYOg/view?usp=sharing)
[![Portfolio](https://img.shields.io/badge/Portfolio-2563EB?style=for-the-badge&logo=globe&logoColor=white)](https://smukherjee2004.github.io/Portfolio/)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://kaggle.com/mukherjeesourjya)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/sourjyam)
[![DeepML](https://img.shields.io/badge/DeepML-6C3EF5?style=for-the-badge&logo=codeforces&logoColor=white)](https://www.deep-ml.com/profile/4rIqr1YHx3hmiadyNFkkA5rnbRE2)

</div>

---

## Featured Projects

### [Agentic Personal Assistant — Local LLM-Powered Productivity Agent](https://github.com/SMukherjee2004/agentic_PA)
Tool-augmented agent running entirely on a local Ollama LLM (Mistral / Llama3.1 / Qwen2.5) with native function-calling, orchestrating a ReAct-style agentic loop across Google Calendar, Gmail, Docs, and Sheets — zero cloud LLM dependency.
- RAG pipeline (ChromaDB + Sentence-Transformers) syncing live per-user data into context on every turn
- OAuth 2.0 + JWT session auth, two-step tool-dispatch to eliminate spreadsheet-ID hallucination
- 22 automated tests (auth boundaries, tool dispatch, DB persistence) · fully Dockerized
- **Stack:** Python · FastAPI · React · TailwindCSS · Ollama · ChromaDB · Docker · Pytest

### [Two-Stage Semantic Search & Ranking Engine](https://github.com/SMukherjee2004/product-search-engine)
Retrieval-and-ranking pipeline on the Amazon ESCI Shopping Queries dataset: fine-tuned MiniLM sentence-transformer for dense retrieval via FAISS, followed by a LightGBM LambdaRank reranker over engineered relevance features.
- Recall@100: 50.5% · NDCG@10: 0.227 — ongoing work on hard-negative mining to close the retrieval gap
- Served via FastAPI with LRU response caching · containerized with Docker
- **Stack:** Python · PyTorch · Sentence-Transformers · FAISS · LightGBM · FastAPI · Docker

### Physics-Informed Autoencoders for Parasitic Extraction in III-V Semiconductor Diodes
*(B.Tech Dissertation)* — Physics-informed ML framework extracting six intrinsic SSEC parameters of a GaN self-switching nanodiode from S-parameter measurements.
- Physics-Informed Autoencoder (PIAE) with Tikhonov-regularized bottleneck + 2-port passivity constraint; Conditional VAE for uncertainty quantification
- MAPE < 5% on four of five observable parameters, validated via six mechanistic interpretability analyses (Integrated Gradients, Jacobian cross-talk, SVD rank decomposition)
- **Stack:** Python · PyTorch · Keysight ADS · Variational Autoencoders

**→ [See all repositories](https://github.com/SMukherjee2004?tab=repositories)**

---

## Core Stack

**ML / Deep Learning**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Transformers](https://img.shields.io/badge/🤗%20Transformers-FFD21E?style=flat-square)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**LLMs / GenAI**
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![LangChain](https://img.shields.io/badge/RAG_Pipelines-1C3C3C?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-4285F4?style=flat-square)

**MLOps / Deployment**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Languages & Data**
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)

---

## Currently

- Building an end-to-end MLOps pipeline (CI/CD, model registry, drift-triggered retraining) to round out production ML systems experience
- Exploring LLM fine-tuning (LoRA/QLoRA) and inference optimization (quantization, vLLM serving)
- Open to **Machine Learning Engineer / AI Engineer / Data Scientist** roles

---

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=smukherjee2004&theme=tokyonight&hide_border=true&background=0D1117&ring=F8B400&fire=F8B400&currStreakLabel=F8B400&sideNums=58A6FF&sideLabels=8B949E&dates=8B949E&stroke=F8B400" alt="streak stats"/>

</div>
