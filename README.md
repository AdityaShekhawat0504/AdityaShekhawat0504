## Hi, I'm Aditya

**Applied AI student (B.Sc.) at TH Rosenheim, building AI systems that make decisions you can check.**
LLM agents with guardrails, explainable ML for fraud and anti-money-laundering, and tools for EU AI Act compliance. Based in Munich / Rosenheim.

**Open to Werkstudent roles in AI, ML and data.**

[LinkedIn](https://www.linkedin.com/in/aditya-singh-shekhawat) · adityasinghshekhawat000@outlook.com

---

### Projects

| Project | What it does | Result |
|---|---|---|
| [**AI Act Compliance Copilot**](https://github.com/AdityaShekhawat0504/ai-act-compliance-copilot) | Generates EU AI Act Annex IV technical documentation from Hugging Face model cards. Two-pass LLM pipeline: extract, then verify every field against the source. v2 adds an evidence pack that maps a SaaS product to its AI Act role, risk tier and Article 50 obligations. | **0% hallucination** (at 28% field coverage) vs. 37% for a plain LLM baseline, across 10 models. Fills only what it can prove. |
| [**Export Agent**](https://github.com/AdityaShekhawat0504/export-agent) | FastAPI service that classifies shipments into HS codes with an LLM, checks sanctions and returns approve / review / block with a stored reason. | Memory of human-verified answers skips the LLM on repeat products. Uncertain cases go to a human instead of being guessed. |
| [**Privacy-First Banking Compliance Layer**](https://github.com/AdityaShekhawat0504/Privacy-First-Banking-Compliance-Layer-) | Lets banks train AML models without exposing personal data: HMAC pseudonymisation, IBAN tokenisation, CTGAN synthetic transactions, SHAP explanations. | Model trained only on synthetic data: **0.806 AUC** (real-data ceiling 0.931). |
| [**Explainable AML on the Elliptic Graph**](https://github.com/AdityaShekhawat0504/elliptic-aml-gnn) | GraphSAGE GNN vs. XGBoost on 203k Bitcoin transactions, with GNNExplainer subgraphs an investigator can read. | Found **16 illicit transactions** the feature-only model missed. |
| [**Veritas**](https://github.com/AdityaShekhawat0504/Veritas) | Breaks investment memos into claims, assumptions and evidence, and scores whether the thesis still holds. | [Live prototype](https://veritas-rose-beta.vercel.app). Pitched at IDEAchallenge 2026. |
| [**Fraud Detection Dashboard**](https://github.com/AdityaShekhawat0504/Fraud-detection) | Flask app scoring card transactions 0–100 with IsolationForest and a plain-English reason for each flag. Single and batch CSV mode. | **ROC-AUC 0.954** on 284,807 transactions (0.17% fraud). |
| [**Tiny Diffusion**](https://github.com/AdityaShekhawat0504/Tiny-diffusion) | DDPM trained from scratch on CIFAR-10, plus a DDPM vs. DDIM sampler ablation. | Stochastic DDIM (100 steps) matched DDPM quality at **4× the speed**. |

---

### Tech

**Languages and data:** Python (pandas, NumPy), SQL, PostgreSQL, Java, TypeScript
**ML:** scikit-learn, PyTorch, PyTorch Geometric, XGBoost, Hugging Face Diffusers
**LLMs:** OpenAI API, structured outputs (Pydantic), agents with rule layers and memory, RAG
**Explainability and governance:** SHAP, GNNExplainer, EU AI Act, GDPR, BaFin / EBA guidelines
**Apps and tooling:** FastAPI, Flask, Streamlit, Next.js, Docker, GitHub Actions

---

### Also

- Head of the Student Board, **Mind Makers Masterclass** (Gründungshub Oberbayern): real business problems with partner companies.
- Pitched at the **IDEAchallenge**, TH Rosenheim, in 2025 and 2026.
- Languages: English (C1), German (B2, daily at work), Hindi (native).
