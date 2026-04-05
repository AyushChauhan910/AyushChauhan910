<h1 align="center">Ayush Chauhan</h1>
<p align="center">
  Computer Science @ BITS Pilani, Hyderabad · AI/ML · Full-Stack · Agentic Systems
</p>
<p align="center">
  <a href="mailto:talktoayushchauhan@gmail.com">Email</a> ·
  <a href="https://linkedin.com/in/ayush-chauhan-bba21a315">LinkedIn</a> ·
  <a href="https://portfolio-website-chi-ebon-13.vercel.app/">Portfolio</a>
</p>

---

## About

B.E. Computer Science student at BITS Pilani (2023–2027) focused on building production-grade AI systems and full-stack applications. I work across the stack — from LangGraph agentic pipelines and RAG systems to React frontends and containerized APIs.

Currently exploring: Agentic AI, Data Engineering, and Open-Source contributions.

---

## Featured Projects

### [FinSight — Autonomous Financial Research Agent](https://fin-sight-full.vercel.app)
`LangGraph · LangChain · ChromaDB · FastAPI · React · Groq (Llama 3.1 70B)`

- Architected a 5-stage stateful LangGraph agent (decompose → retrieve → draft → validate → retry) with self-correcting hallucination detection, served via FastAPI with SSE for real-time token streaming
- Built async SEC EDGAR ingestion pipeline (httpx + asyncio) for 200-page 10-K/10-Q filings into ChromaDB with BGE-small embeddings — ~60% faster than sequential processing
- Benchmarked on a 50-question financial QA set: **87% accuracy vs 61% for naive RAG** (43% relative improvement)
- Shipped full-stack to production with live agent trace visualization, citation drawer, and 5-tab analyst report UI

### [PLGA Microsphere Drug Release Prediction](https://github.com/AyushChauhan910/PLGA)
`Python · XGBoost · LightGBM · SHAP · scikit-learn`

- Engineered 11 domain-informed features grounded in polymer degradation theory; expanded 25-formulation dataset to 450+ samples via sliding-window augmentation
- Built 7-model comparison pipeline with LOO-CV; stacked ensemble: **RMSE = 4.39%, R² = 0.820**
- LightGBM achieved **12.1% MAE**, outperforming neural networks (15.6%) — consistent with tree ensemble superiority on small pharmaceutical datasets
- SHAP analysis confirmed Drug LogP, GA fraction, and Tg offset as primary release modulators
- **Under review** at Journal of Controlled Release (2026)

### [Production-Scale Deepfake Detection System](https://deepfakedetector.app)
`PyTorch · Flask · React.js · Docker · OpenCV`

- Multimodal detection (image, video, audio) via CNN-LSTM + audio spectral analysis — **91.3% F1-score** on FaceForensics++
- Reduced inference latency from ~3.4s to **2.0s (41% improvement)** via frame-level temporal attention
- Containerized Flask API (Docker + Render) sustaining **500+ daily requests at p95 < 1.8s** under Locust load testing
- React dashboard with drag-and-drop upload and real-time confidence scoring — **200+ unique users within 3 weeks**

---

## Open-Source Contributions

### [facebookresearch/sam2](https://github.com/AyushChauhan910/sam2/tree/feat/adaptive-temporal-sampler) — Meta FAIR ⭐ 18.5k
- Implemented a motion-adaptive temporal frame sampler replacing uniform stride with motion-density-proportional allocation using lightweight L1 pixel-diff scoring
- Measured **4.1% mean improvement** in high-motion frame coverage across 15 DAVIS-2017 sequences; 80–108% gains on motion-burst sequences
- Integrated backward-compatibly via opt-in Hydra config with 8 unit tests — zero regression on DAVIS-2017 val (J&F = 88.43 maintained)

---

## Experience

**Digital Transformation Intern** — Absolute Smart Solutions *(May–July 2025)*
- Built Next.js + Tailwind corporate platform with Core Web Vitals optimization (LCP < 2.1s), driving **30% lift in qualified leads** over 6 weeks
- Translated 12 Figma specs into reusable React components; reduced image payload by **65%** via WebP + lazy loading
- Built Python + Jira REST API automation to auto-triage tickets, cutting manual tracking overhead by **20%** across a 6-person team

---

## Competitive Programming & Achievements

- **Kaggle Titanic** — Top 24% (2,951 / 12,300+ teams) | Stacked XGBoost + LightGBM + CatBoost ensemble · 0.787 accuracy
- **OpenEnv Hackathon (Hugging Face × Meta)** — Round 2 Qualifier, Top 30% | Built OpenEnv-compliant SQL Analyst Agent

---

## Tech Stack

**Languages:** Python, JavaScript/TypeScript, SQL, Java, C++  
**AI/ML:** PyTorch, Scikit-Learn, XGBoost, LightGBM, LangChain, LangGraph, RAG, FAISS, ChromaDB, OpenCV, Librosa, SHAP  
**Frontend:** React.js, Next.js, Redux, Tailwind CSS  
**Backend:** Node.js, Express.js, Flask, FastAPI  
**Databases:** MongoDB, PostgreSQL  
**DevOps:** Docker, Vercel, Render, Hugging Face Spaces, GitHub Actions  

---

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AyushChauhan910&layout=compact&langs_count=10&theme=tokyonight" height="160"/>
</div>
