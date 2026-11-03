<p align="center"><img src="banner.jpg" alt="Nihal Yadav — AI & Software Engineer" width="100%"></p>

<h1 align="center">Nihal Yadav</h1>

<p align="center">
<b>AI Trainer & ML Engineer</b> · LLM Evaluation · Code Review · Agentic-Coding Benchmarks<br>
M.Tech, Artificial Intelligence & Machine Learning — <b>IIT Delhi</b>
</p>

<p align="center">
<a href="https://linkedin.com/in/nihal-yadav-5131582b8"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="mailto:ynihal494@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
<a href="https://huggingface.co/NIHAL670"><img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face"></a>
<a href="https://leetcode.com/u/Nihal_yadav"><img src="https://img.shields.io/badge/LeetCode_1850-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode"></a>
<a href="https://portfolio-n-5uz6.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"></a>
</p>

---

### Summary

I evaluate frontier language models and build the systems that grade them. As an **AI Trainer at Handshake AI**, I author agentic-coding evaluation tasks, build deterministic graders, and diagnose exactly where models fail. At **AfterQuery** I shipped expert benchmark tasks capturing real computer work that today's best AI agents cannot yet do.

I bring graduate-level depth in machine learning (IIT Delhi), production software-engineering experience, and a habit of reporting results honestly — separating genuine model errors from specification defects, and documenting gaps rather than tuning a metric.

**Available for:** LLM evaluation · code review of model output · response ranking & comparison · STEM / ML reasoning projects · ML Engineer, AI Engineer and Software Engineer roles.

---

### At a glance

| | |
|---|---|
| 🎓 **Education** | M.Tech in AI & ML, IIT Delhi (CGPA 8.0/10) · B.Tech in AI & ML |
| 🧪 **Model evaluation** | Two frontier-model evaluation contracts — Handshake AI (2025 – present) and AfterQuery (2026) |
| ✅ **Grading rigour** | Deterministic harnesses with automated rubrics of **100+ checks** per larger task; every task cleared quality gates |
| 💻 **Coding strength** | LeetCode contest rating **1850** (390+ solved) · Codeforces **1400** (160+ solved) |
| 📄 **Research** | Preprint on real-time audio deepfake detection (Zenodo, 2026) |

---

### What I bring to AI training projects

**LLM evaluation & rubric scoring** — Write rubrics and automated checks that score model responses reproducibly; give concise, evidence-based pass/fail justifications.

**Code review of model output** — Review Python, JavaScript, C++, C and SQL for correctness, edge cases, complexity and style, backed by strong DSA fundamentals.

**Task authoring & difficulty calibration** — Design multi-file problems with precise specifications, reference solutions and sealed verifiers; tune difficulty using candidate-model pass rates so tasks separate strong models from weak ones.

**Failure analysis** — Trace failing runs to root cause, distinguishing real model mistakes from ambiguous or contradictory specs, and fix the source of false-negative grades.

**STEM & ML reasoning** — Deep learning, classical ML, speech/audio and time-series modelling, with hands-on experience training and evaluating models end to end.

**Guidelines & confidentiality** — Follow detailed project guidelines and confidentiality rules; consistent quality through strict multi-stage review pipelines.

---

### Experience

**AI Trainer — Software Engineering & LLM Evaluation** · *Handshake AI Fellowship* · Remote · 2025 – Present
- Author multi-file software-engineering evaluation tasks for a frontier agentic-coding benchmark, spanning frontend and systems-level problems.
- Build a deterministic grading harness for each task — a reference solution plus an automated rubric of 100+ checks on larger tasks — so responses are scored reproducibly.
- Run candidate LLMs on each task and compare pass rates across test setups to calibrate difficulty to a target band.
- Review failing runs to separate model errors from spec defects; traced and eliminated a recurring spec-vs-reference contradiction that caused false-negative grades.

**Expert — AI Agent Benchmark Tasks** · *AfterQuery* · Remote · Jan 2026 – May 2026
- Shipped 5+ expert benchmark tasks through a strict review pipeline, each capturing hard, real computer work that current AI agents cannot yet complete.
- Packaged each task in the Harbor format: precise instruction, containerised environment, sealed verifier grading the agent's final result, and reference solution.

**Machine Learning Intern** · *Infosys Springboard* · Remote · Apr 2025 – Jan 2026 · *Completed with distinction*
- Built and deployed a cryptocurrency price-forecasting app on Streamlit with multi-step forecasts and confidence intervals; recognised by program mentors.
- Compared LSTM, GRU, Random Forest and XGBoost under a single evaluation protocol; the best model cut RMSE by 20–30% over the naive baseline.

---

### Selected work

**[IronWall AI — Speech Deepfake Detection](https://github.com/NIHAL670/DEEP-FAKE-DETECTION-MODEL)** · [Preprint](https://doi.org/10.5281/zenodo.23755056)
Fine-tuned wav2vec2-large-xlsr-53 (300M parameters) to classify real vs. AI-generated speech. Reached 75.1% validation accuracy, diagnosed underfitting, and documented the gap to published baselines instead of tuning the reported metric. Added a reference-free quality gate that abstains on unusable audio, served through FastAPI with a React dashboard (accuracy, F1, AUC, EER vs. SNR).
`wav2vec2` `TensorFlow/Keras` `Hugging Face` `FastAPI` `React`

**[Smart Agriculture AI System](https://github.com/NIHAL670/AI-powered-crop-prediction-and-disease-detection-model)**
Three-module platform: a 7-class crop recommender at 89% test accuracy with calibrated top-3 output, fertiliser optimisation, and a CNN leaf-disease detector across 6 crops at 92% validation accuracy on 4,000 images.
`Python` `scikit-learn` `CNN` `Docker` `Hugging Face Spaces`

**[Nova Cart — Full-Stack E-Commerce](https://github.com/NIHAL670/Nova-ecart-)**
26 routes, JWT authentication with role-based access, secure Stripe payment webhooks, and 32 passing tests in CI.
`Next.js 15` `Node.js/Express` `MongoDB` `Redis` `Stripe`

**[Crypto Price Forecasting](https://github.com/NIHAL670/cryptop_prediction_model)**
Time-series features engineered from 4,000 rows of OHLCV data with sliding windows and MinMax scaling; four model families benchmarked under one protocol and deployed on Streamlit.
`Python` `TensorFlow` `XGBoost` `Streamlit`

---

### Technical skills

| Area | Tools |
|---|---|
| **Languages** | Python · JavaScript · TypeScript · C++ · C · SQL |
| **ML / DL** | PyTorch · TensorFlow/Keras · Hugging Face Transformers · scikit-learn · XGBoost · pandas · NumPy |
| **Specialisms** | LLM evaluation · speech/audio modelling · time-series forecasting · computer vision (CNNs) |
| **Backend & web** | FastAPI · Node.js/Express · React · Next.js · REST APIs |
| **Data & infra** | PostgreSQL · MongoDB · Redis · Docker · Git/GitHub · Streamlit · Hugging Face Spaces |

---

### Publication

**N. Yadav.** *IronWall AI: A Chunk-Level, Explainable and Batched Architecture for Real-Time Audio Deepfake Detection.* Preprint, Zenodo, Oct 2026. [doi:10.5281/zenodo.23755056](https://doi.org/10.5281/zenodo.23755056)

### Education

- **M.Tech, Artificial Intelligence and Machine Learning** — Indian Institute of Technology (IIT) Delhi · CGPA 8.0/10 · 2022 – 2024
- **B.Tech, Artificial Intelligence and Machine Learning** — Ajay Kumar Garg Engineering College, Ghaziabad · 2018 – 2022

---

<p align="center">
<b>Open to AI training, LLM evaluation and ML engineering opportunities.</b><br>
📧 <a href="mailto:ynihal494@gmail.com">ynihal494@gmail.com</a> · 📍 Ghaziabad, India · Remote
</p>
