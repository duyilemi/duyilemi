# Production AI Engineer

**I build end-to-end AI systems that actually ship** — from LLM-powered applications and computer vision pipelines to cloud infrastructure and automated data workflows.

📧 charlieduyilemi@yahoo.com | 🔗 [LinkedIn](https://linkedin.com/in/charlesolajide) | 💻 [GitHub](https://github.com/duyilemi)

---

## What I Do

- **Architect LLM Systems** — Design RAG pipelines, multimodal AI workflows, and agent-based orchestration (LangGraph, LangChain, Groq)
- **Ship Production Backend** — Build FastAPI services with proper testing, monitoring, and CI/CD (Docker, GitHub Actions, Azure Monitor)
- **Automate Data & Infrastructure** — Create Airflow pipelines, Terraform configurations, and MLOps workflows that run themselves
- **Optimize for Constraints** — Deploy AI on edge devices and CPU-only environments (ONNX, quantization, batch processing)

---

## Featured Projects

### 🤖 Automated Video Compliance Auditor (LLM + Multimodal AI)
*Intelligent video auditing system for content moderation and policy compliance*

- Built intelligent video auditing system leveraging RAG and Azure OpenAI (GPT-4) to analyze content against regulatory frameworks
- Integrated Azure Video Indexer for speech-to-text and OCR extraction, enabling multimodal content understanding
- Designed FastAPI backend with telemetry monitoring via Azure Monitor for production observability
- Reduced manual compliance review effort through automated detection workflows and violation flagging

**Stack:** Azure OpenAI, Azure Video Indexer, FastAPI, RAG, LangGraph

---

### 📸 AI Photo Organizer (Computer Vision + Edge AI)
*Offline-first photo classification tool that runs AI entirely on local CPU*

- Built intelligent photo classification system leveraging PyTorch and ONNX Runtime for offline CPU inference without GPU dependency
- Exported MobileNetV3 model from PyTorch to ONNX, reducing deployment footprint from 800MB to 22MB (97% size reduction)
- Designed dual-interface architecture with Tkinter desktop GUI and FastAPI web service supporting concurrent batch uploads
- Achieved 2x inference throughput via SIMD-optimized batch processing (8 images/concurrent) on Intel Core i3 processors

**Stack:** PyTorch, ONNX Runtime, FastAPI, Tkinter, Docker, PyInstaller

---

### 📰 AI News Summarizer Pipeline (Data Engineering + LLM Orchestration)
*Production-grade data pipeline with automated orchestration and dataset versioning*

- Built end-to-end data pipeline with Apache Airflow orchestrating daily news ingestion, data quality validation, and LLM-based summarization via Groq API
- Implemented dataset versioning with DVC and designed FastAPI backend serving processed summaries through REST API with nginx reverse proxy
- Containerized multi-service architecture (PostgreSQL, Redis, Airflow, FastAPI, nginx) using Docker Compose with automated email alerting on pipeline failures
- Established CI/CD with GitHub Actions and comprehensive Pytest coverage for data fetching, API endpoints, and quality validation logic

**Stack:** Apache Airflow, Groq API, FastAPI, DVC, Docker, PostgreSQL, Pytest

---

### ⚙️ AWS Infrastructure Automation (Terraform + Cloud Architecture)
*Infrastructure-as-Code for reproducible cloud environments*

- Provisioned complete AWS environments (compute, networking, IAM, storage) using Terraform modules for consistent, repeatable deployments
- Implemented infrastructure state management and modular configurations supporting multiple environments (dev/staging/production)
- Automated deployment workflows reducing environment setup time from manual configuration to single `terraform apply`

**Stack:** Terraform, AWS (EC2, S3, IAM, VPC), Infrastructure as Code

---

## Technical Toolkit

**AI & Machine Learning:** Python, PyTorch, ONNX, LangChain, LangGraph, RAG, Vector DBs (Pinecone), Hugging Face, Groq

**Backend & APIs:** FastAPI, Uvicorn, REST API design, Async programming, JWT auth

**Data & MLOps:** Apache Airflow, DVC, Pandas, NumPy, Data validation, ETL pipelines

**Cloud & DevOps:** AWS, Azure, Docker, Docker Compose, Terraform, GitHub Actions, CI/CD

**Testing & Quality:** Pytest, unittest, Test-driven development, Data quality checks

---

## Beyond the Code

I don't just train models—I ship complete systems. That means:
- **Error handling** when APIs fail
- **Monitoring** so you know when things break  
- **Tests** so you can refactor without fear
- **Documentation** so the next engineer can onboard quickly

---

**Open to opportunities in:** AI Engineering, LLM Systems, Data Engineering, MLOps, Backend Development

📫 **Reach me:** charlieduyilemi@yahoo.com | [LinkedIn](https://linkedin.com/in/charlesolajide)
