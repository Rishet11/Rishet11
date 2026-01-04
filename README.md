<h1 align="center">Rishet Mehra</h1>
<p align="center">
AI/ML Systems Engineer • LLMs, Verification & RAG • Production-Oriented
</p>

---

## Overview
I build **AI systems that are designed to be correct, inspectable, and reliable in real-world conditions** — not just fluent or impressive in demos.

My work sits at the intersection of:
- **LLM-based systems** (RAG, claim verification, grounding)
- **Explicit uncertainty handling** (knowing when the system should not answer)
- **End-to-end engineering** (from data ingestion to backend APIs and usable interfaces)

I care more about **failure modes and evaluation** than hype.

---

## Flagship Work

### 🔹 Verique — Verification-First LLM System
- Designed a system that **extracts factual claims from LLM outputs** and evaluates them independently
- Each claim is classified as: **verified, not verifiable, outdated, or opinion**
- Introduced a dedicated **“What We Don’t Know”** layer to surface uncertainty instead of hiding it
- Built with judge-facing transparency in mind, prioritizing **epistemic honesty over completeness**

**Why it matters:**  
Most AI systems optimize for confidence. Verique optimizes for **trust**.

---

### 🔹 VidWise AI — Retrieval-Centric LLM Application
- Built an end-to-end **Retrieval-Augmented Generation (RAG)** system for querying long-form YouTube content
- Designed chunking, retrieval, and reranking logic to improve grounding and answer quality
- Integrated embeddings and vector search (FAISS) with LLM reasoning
- Shipped as a full-stack application for real user interaction

**Why it matters:**  
Demonstrates practical LLM systems engineering beyond prompt-level experimentation.

---

### 🔹 Property Price Prediction — Forecasting Under Constraints
- Developed time-series models to forecast property prices **10 years ahead**
- Explicitly modeled **seasonality, long-term trends, and upper/lower bounds**
- Built multivariable regression pipelines with hyperparameter tuning (GridSearchCV)
- Prioritized interpretability and stability over raw accuracy alone

**Why it matters:**  
Shows ML reasoning under uncertainty, not just model fitting.

---

## Industry Experience

**AI Research & Development Intern — Zanista AI (UK)**
- Engineered scalable web crawlers for real-time financial news ingestion
- Integrated LLM pipelines for summarization, sentiment analysis, NER, and topic clustering
- Designed data-cleaning and deduplication workflows to improve downstream reliability
- Worked on transforming noisy, unstructured data into API-ready datasets

**Web Developer Intern — BharatFare**
- Debugged and fixed production issues in a live, user-facing platform
- Integrated and consumed APIs across frontend and backend services
- Worked within an existing **TypeScript / Node.js** codebase under production constraints
- Shipped changes that directly impacted real users

---

## Technical Focus
- **AI/ML:** LLMs, RAG, embeddings, retrieval, reranking, uncertainty handling  
- **ML:** Machine Learning, Deep Learning, Time Series Modeling  
- **Data & Systems:** Crawlers, PDF intelligence, clean data pipelines  
- **Engineering:** Python, LangChain, FAISS, TensorFlow, Streamlit, SQL, TypeScript, Node.js  

---

## How I Approach Engineering
- Prefer **explicit limitations** over fake confidence
- Treat **evaluation** as a first-class concern
- Design systems that remain honest when data or evidence is weak
- Optimize for **long-term reliability**, not short-term demos

---

📧 **Email:** rishetmehra11@gmail.com  
🔗 **LinkedIn:** https://www.linkedin.com/in/rishetmehra  
💻 **GitHub:** https://github.com/Rishet11
