### Hi, I'm Aditya

Applied AI student at **TH Rosenheim** (B.Sc.), based in Munich / Rosenheim.
I build AI systems that make real decisions and can explain every one of them: LLM agents with guardrails, explainable ML for fraud and AML, and tools for EU AI Act compliance.

Head of the Student Board at the **Mind Makers Masterclass** (Gründungshub Oberbayern), working on real business problems with partner companies. Pitched my projects twice at the IDEAchallenge (TH Rosenheim).

**Open to Werkstudent roles in AI, ML and data in Munich.**

---

### Selected projects

| Project | What it does | Result |
|---|---|---|
| [**AI Act Compliance Copilot**](REPO-LINK) | Generates EU AI Act Annex IV technical documentation from Hugging Face model cards. Two-pass LLM pipeline: extract, then independently verify every field against the source. | **0% hallucination** (at 28% field coverage) vs. 37% for a plain LLM baseline, across 10 models. It refuses to guess: only fields it can prove get filled. 114 tests. |
| [**Export Agent**](REPO-LINK) | LLM agent that classifies goods into HS codes, checks country-risk and dual-use rules and decides: approve, flag or block, with a stored reason. | FastAPI microservice with a PostgreSQL memory layer that reuses past decisions to cut tokens and latency. |
| [**Vaultlayer**](REPO-LINK) | Lets banks train AML models without exposing personal data: HMAC pseudonymisation, IBAN tokenisation, CTGAN synthetic transactions. | Model trained only on synthetic data: **0.806 AUC** (real-data ceiling 0.931). |
| [**Veritas**](REPO-LINK) | LLM pipeline that breaks an investment memo into claims, assumptions and evidence and tracks whether the thesis still holds. | Working prototype pitched at IDEAchallenge 2026. |
| [**Elliptic AML Graph**](REPO-LINK) | GraphSAGE GNN vs. XGBoost on 203k Bitcoin transactions, with GNNExplainer subgraphs for investigators. | Found **16 illicit transactions** the feature-only model missed. |

---

### Tech I use

**Languages & data:** Python (pandas, NumPy), SQL, PostgreSQL, Java
**ML:** scikit-learn, PyTorch, PyTorch Geometric, XGBoost, Hugging Face Diffusers
**LLMs:** OpenAI API, structured outputs (instructor + Pydantic), agents with rule layers and memory, RAG
**Explainability & governance:** SHAP, GNNExplainer, EU AI Act, GDPR, BaFin / EBA guidelines
**Apps:** FastAPI, Flask, Streamlit, Next.js

---

### Contact

[LinkedIn](https://www.linkedin.com/in/aditya-singh-shekhawat) · adityasinghshekhawat000@outlook.com

Languages: English (C1), German (B2, daily at work), Hindi (native)
