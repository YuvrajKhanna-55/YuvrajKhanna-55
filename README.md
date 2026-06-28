<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&pause=1200&color=58A6FF&center=true&vCenter=true&width=700&lines=Hi%2C+I'm+Yuvraj+Khanna+%F0%9F%91%8B;AI+%26+Data+Science+Undergraduate;Building+Transformers+from+Scratch;NLP+%7C+LLMs+%7C+Computer+Vision+%7C+GenAI)](https://git.io/typing-svg)


</div>

---

## About Me

---

## 🔭 Current Focus

| Area | What I'm Working On |
|---|---|
| **LLMs & RAG Systems** | Hybrid retrieval pipelines — dense + sparse search, cross-encoder reranking, grounded generation |
| **Transformers** | Reading and re-implementing architecture papers to understand design decisions, not just APIs |
| **Deep Learning** | PyTorch from tensors up — autograd, custom training loops, optimization strategies |
| **Computer Vision** | Transfer learning pipelines, class imbalance handling, DenseNet & ViT architectures |
| **Backend for AI** | FastAPI services, Streamlit interfaces, making ML models actually usable |
| **Open Source** | Reading codebases, raising issues, contributing where I can add real value |

---

## 🛠 Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**AI / ML / NLP**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/🤗%20Hugging%20Face-FFD21E?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**Backend & Tooling**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Concepts**

![Deep Learning](https://img.shields.io/badge/Deep%20Learning-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-4B8BBE?style=flat-square&logo=python&logoColor=white)
![LLMs](https://img.shields.io/badge/LLMs-FF6F00?style=flat-square&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-009688?style=flat-square&logo=fastapi&logoColor=white)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST%20APIs-009688?style=flat-square&logo=fastapi&logoColor=white)
![DSA](https://img.shields.io/badge/DSA-000000?style=flat-square&logo=leetcode&logoColor=white)

---

## 📌 Featured Projects

### 🔍 [Log Analysis RAG](https://github.com/YuvrajKhanna-55/Log-Analysis-RAG) — Retrieval-Augmented Log Analysis System

> End-to-end RAG pipeline for analyzing 10,000+ system log lines using natural language queries. The retrieval layer combines FAISS dense vector search with BM25 sparse retrieval, reranked by a Cross-Encoder (`ms-marco-MiniLM`) before the LLM inference step — because single-strategy retrieval leaves precision on the table.

**What's technically interesting:** Format-agnostic log parsing across system, web server, database, and cloud logs; 512-character semantic chunking with sensitive data anonymization (IPs, UUIDs, emails, URLs); Llama-3.1-8B for incident summary generation; Streamlit interface + CLI.

`PyTorch` `FAISS` `BM25` `Sentence Transformers` `LangChain` `Streamlit` `RAG` `Llama-3.1`

---

### ⚖️ [LawLens](https://github.com/YuvrajKhanna-55/LawLens) — Legal Document Summarization

> Fine-tuned FLAN-T5 on the Indian Legal Corpus (ILC) for abstractive summarization of judicial documents — a domain where generic summarization models fail because legal reasoning depends on precise language structure. Includes a head-to-head comparative study with PEGASUS under identical training conditions, evaluated with ROUGE metrics.

**What's technically interesting:** Full seq2seq fine-tuning pipeline — preprocessing, tokenization, training, inference, and evaluation. Memory-efficient training on T4 GPUs. FLAN-T5 consistently produced more coherent and context-aware summaries on Indian legal text. Research manuscript authored alongside the implementation.

`Hugging Face` `FLAN-T5` `PEGASUS` `NLP` `Fine-Tuning` `ROUGE` `Legal AI`

---

### 🫁 [Chest X-Ray Pneumonia Classification](https://github.com/YuvrajKhanna-55/Pytorch-NNs-From-Scratch)

> Transfer learning pipeline using DenseNet121 (pretrained on ImageNet) fine-tuned for binary pneumonia detection on a 5,856-image clinical dataset with severe class imbalance — the kind of problem where accuracy alone is a misleading metric.

**What's technically interesting:** `WeightedRandomSampler` + weighted cross-entropy to handle class skew; AdamW with differential learning rates and cosine annealing scheduling; early stopping. Results: **90.6% validation accuracy**, **84.5% test accuracy**, **0.93 ROC-AUC**.

`PyTorch` `DenseNet121` `Transfer Learning` `Computer Vision` `Medical Imaging`

---

### 🧠 [PyTorch NNs From Scratch]

> Building neural networks from tensors up — ANN, CNN, RNN, LSTM — to understand what each abstraction actually computes. Not a tutorial follow-along; built to develop intuition for architecture decisions.

`PyTorch` `Deep Learning` `ANN` `CNN` `RNN` `LSTM` `From Scratch`

---

### 📊 [COVID-19 Analysis & Forecasting]

> EDA and time-series forecasting of 2023 COVID-19 case trends — regional comparisons, spike visualization, and forecasting pipeline.

`Python` `Pandas` `Matplotlib` `Time Series` `EDA`

---

### ⚡ [Simple RAG Pipeline]
> Minimal RAG implementation using LangChain, ChromaDB, and Groq LLM for PDF-based question answering. Built to understand the mechanics before the abstractions.

`LangChain` `ChromaDB` `Groq` `RAG` `PDF QA`

---

## 📊 GitHub Analytics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=YuvrajKhanna-55&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true&bg_color=0d1117&title_color=58A6FF&icon_color=58A6FF&text_color=c9d1d9" />

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YuvrajKhanna-55&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58A6FF&text_color=c9d1d9&langs_count=8&hide=html,css" />

</div>

<div align="center">

<img src="https://streak-stats.demolab.com?user=YuvrajKhanna-55&theme=github-dark-blue&hide_border=true&background=0d1117&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF" />

</div>

<div align="center">

[![GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=YuvrajKhanna-55&bg_color=0d1117&color=58A6FF&line=58A6FF&point=ffffff&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## 📚 Learning Journey

**Currently Reading / Working Through**
- 📄 *Attention Is All You Need* — Vaswani et al. — re-implementing while reading
- 📄 *RAFT, RLHF, Constitutional AI* — studying alignment from first principles
- 📖 *Deep Learning* — Goodfellow, Bengio, Courville
- 🎥 Andrej Karpathy — Neural Networks: Zero to Hero
- 📖 *Designing Machine Learning Systems* — Chip Huyen

**Certifications Earned**
- 🏅 Google Cloud Generative AI Academy (Jun 2025)
- 🌍 Remote Sensing & GIS Applications — IIRS-ISRO (Mar 2025)
- 📊 Data Science Certification — TNCCDS (Apr 2025)

**On the Radar**
- Mixture of Experts (MoE) architectures
- Efficient inference, quantization, and model compression
- MLOps and production deployment patterns
- Reinforcement Learning fundamentals

---

## 🌐 Open Source & Community

As **ML Head of Advait-AI Society (VIPS-TC)**, I've spent the last year not just building things, but helping others build them too — mentoring projects in PyTorch, Hugging Face, and LangChain, and running workshops on transformers, image segmentation, and generative AI pipelines.

I believe teaching is one of the fastest ways to find gaps in your own understanding.

**How I engage with open source**
- Reading codebases to understand architectural decisions, not just APIs
- Raising reproducible, well-documented issues when I find bugs
- Contributing to documentation and tests before attempting core logic

---

## 📬 Let's Connect

Open to conversations about AI/ML engineering, research, internships, and open source collaboration.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yuvraj-khanna-b27352360)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YuvrajKhanna-55)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:khanna.yuvraj123@gmail.com)

</div>

---

## ⚡ A Few Things About Me

- I built a RAG pipeline with hybrid retrieval before fully understanding what "dense" vs "sparse" meant — then went back and learned the math. That order of operations works for me.
- I keep notes on every paper I read: problem statement, key idea, what it doesn't solve.
- I think the most underrated ML skill is knowing when a simple baseline is enough.
- I'm based in **New Delhi, India**.

---

<div align="center">

*"The goal isn't to use fewer tools — it's to understand the ones you do use well enough to replace them if you had to."*

---

<sub>Built with real information, not placeholders. · B.Tech AI & Data Science, GGSIPU Delhi · 2023–2027</sub>

</div>
