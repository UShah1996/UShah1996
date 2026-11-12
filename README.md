<h1 align="center">Hi, I'm Urmi Shah 👋</h1>

<p align="center">
  <b>ML Systems Engineer</b> · LLM Inference · RAG · Production ML<br/>
  MS Computer Engineering (ML) @ San José State University · 4.0 GPA · Graduating May 2027
</p>

<p align="center">
  <a href="https://linkedin.com/in/urmi-shah-2910"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:urmimshah96@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Open%20to-New%20Grad%20SWE%20%2F%20MLE%20(2027)-2ea44f?style=flat" alt="Open to new grad roles"/>
</p>

---

### About me

- 🏗️ **4+ years in industry** at **Mercedes-Benz R&D** and **Tata Consultancy Services**, building production ML, data pipelines and LLM services
- 🔬 **Graduate Research Assistant** under Prof. Vishnu Pendyala at SJSU, working on transformer internals (previously embodied AI and RL)
- 👩‍🏫 **Graduate Teaching Assistant** at SJSU for C++ / Data Structures and for the graduate technical writing course (GWAR)
- 🩺 **Software ML Intern at Cybele Health** (Summer 2026): built a full-stack referral platform and an AI profile-enrichment workflow that mixes verified data with LLM suggestions, confidence scoring and human review
- ⚡ I like the systems side of ML: making models fast, reliable and cheap to serve
- 🎯 Looking for **full-time new grad SWE and ML Engineering roles** starting mid-2027

---

### 🚀 Featured projects

| Project | What it does | Key results | Stack |
|---|---|---|---|
| [**Weave**](https://github.com/JNR-10/weave) *(MS project, in progress)* | Runtime-adaptive scheduler that splits LLM layers across 2–3 mixed Apple Silicon Macs and re-partitions live as KV-cache, load and thermals change | 3-person team; I own the placement policies, the "how many Macs" decision, and ablation design (adaptive vs. equal, memory-proportional and static splits) | MLX / MLX-LM, MLX Distributed, JACCL (RDMA over Thunderbolt 5), Python |
| [**Self-Healing Fraud Detection Platform**](https://github.com/manishav26/Fraud-Detection-Platform) *(in progress)* | Scores card transactions in real time, watches its own accuracy for concept drift, and retrains and hot-swaps the model without downtime | 2-person team; I own platform and security (services, streaming, storage, Kubernetes, auth). ~590K real transactions (IEEE-CIS) | Microservices, Kubernetes (k3d), Docker, MLflow, S3-compatible storage, token auth |
| [**QuadKey: Vacation Rental Booking**](https://github.com/gopinathsjsu/cmpe202-03-fall2026-quadkey-teamproject) *(in progress)* | End-to-end booking app with Customer, Host and Admin roles: search, booking, listings, analytics | 4-person Scrum team; I own data and infrastructure (database, readiness checks, Docker, AWS deployment) | FastAPI, PostgreSQL, React, AWS (RDS, S3, ECR, EC2 Auto Scaling, ALB), GitHub Actions |
| [**CardioWatch**](https://github.com/UShah1996/cardiowatch) | AFib detection from Apple Watch ECG + clinical data, two-stream late fusion | **AUC 0.953 ± 0.007** (3-fold CV, 15K ECGs); fixed a hospital-to-wearable domain gap (**~50% → 94%** on Apple Watch); **30–52 min** early warning; **AUC 0.909** zero-shot on MIT-BIH Holter | PyTorch, XGBoost, SHAP, MLflow, Streamlit · [Live demo](https://cardiowatch-spring2026.streamlit.app) |
| [**HyDE Retrieval**](https://github.com/UShah1996/HyDE) | Zero-shot dense retrieval with hypothetical document embeddings | **Recall@10 0.71** with no labeled data, **14.2 ms p99** on 100K MS MARCO passages, **96.4% less memory** (307 MB → 11 MB) via product quantization | FAISS IVF-PQ, Contriever, Hugging Face |
| [**AI-HOPE**](https://github.com/UShah1996/AI-HOPE) | Multi-agent LLM platform for clinical and genomic data analysis | **92% task completion**, fully local | Llama 2, multi-agent orchestration |
| [**FPGA MLP Accelerator**](https://github.com/UShah1996/240_mlp_fpga) | Handwritten digit inference on a Zybo Z7-20 | INT8 quantized MLP on hardware | Zybo Z7-20 FPGA, Python |

---

### 🔬 Research

- **Empirical Differential Geometry of Transformer Residual Flows**: a local flow estimator that cuts held-out update-prediction MSE by **54% (GPT-2 small)** and **60% (GPT-2 medium)** vs. a global-affine baseline
- **CompGen-EmbodiedAI**: compositional generalization study across PPO, hierarchical and Transformer RL agents on a 7-primitive skill benchmark. Zero-shot PPO / hierarchical agents keep **77% / 61%** of a depth-3 specialist's success rate
- **Bioinformatics roots**: published *In Silico Insights into HIV-1 Vpu-Tetherin Interactions and Its Mutational Counterparts* (MDPI); poster at BiATA 2020; built genomic data pipelines at CSIR that improved assembly accuracy by 20%

---

### 📜 Certifications

DeepLearning.AI Machine Learning Specialization (2026) · Applied Machine Learning in Python, University of Michigan (2026) · SAP Certified Associate, SAP Analytics Cloud: Planning

---

### 🛠️ Tech stack

**Languages:** Python · C++ · C · SQL · Java · TypeScript/JavaScript

**ML & LLMs:** PyTorch · Hugging Face · vLLM · Apple MLX · FAISS · scikit-learn · XGBoost · MLflow

**LLM apps:** RAG · HyDE · Agentic pipelines · Azure OpenAI

**Data & infra:** Apache Spark · Databricks · PostgreSQL · Cassandra · AWS · Azure · Docker · Kubernetes · FastAPI · GitHub Actions

**Frontend:** React · React Native · Vite

---

### 📚 Learning in public

[micrograd](https://github.com/UShah1996/micrograd) (autograd from scratch) · [makemore-bigram](https://github.com/UShah1996/makemore-bigram) (character-level LM) · [cpu-design](https://github.com/UShah1996/cpu-design) (CPU design in C++)

<p align="center"><i>Always happy to talk about LLM inference, RAG, and ML systems. Reach out!</i></p>
