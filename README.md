## 👋 Hi, I'm Dheeraj Karanam

I build GenAI and data systems that hold up in production. Six years of data engineering in retail banking and telecom, now an MS Data Science student at Indiana University working on LLM agents, RAG, and ML evaluation.

- 🎓 **MS in Data Science** @ Indiana University Bloomington, Luddy School (May 2027)
- 🤖 **AI Intern** @ McAfee, Platform Engineering (May 2026 to Aug 2026)
- 💼 **Previously:** Data Engineer @ IBM (Barclays Retail Banking); Associate Software Engineer @ TCS (Virgin Media)
- 🎯 **Interested in:** LLM agents, RAG systems, MLOps, and ML for financial services

---

### 🤖 Recent Work: McAfee AI Intern

- **GenAI incident triage agent:** Routed Grafana alerts through AWS Lambda into Bedrock AgentCore to automate first-pass triage and root cause analysis for Platform Engineering and SRE teams.
- **MCP tool integration:** Exposed internal tooling and runbook actions to Bedrock agents through MCP servers; infrastructure provisioned with Terraform.
- **Guardrails:** Cross-account IAM, DynamoDB-based alert deduplication, and OPA policy checks on agent-proposed actions.
- **LLM explainability:** Built a SHAP-based token-level explanation module and embedding-based nearest-neighbor retrieval for an LLM scam-detection classifier.

---

### 🔬 Featured Projects

**Financial Insight System (RAG + LoRA + MCP)** · [finance_rag_lora_mcp](https://github.com/Dheeraj31104/finance_rag_lora_mcp)<br>
End-to-end ingestion and retrieval over 500+ financial documents with a vector database, agentic workflows through MCP tool calling, and a FastAPI QA dashboard tracking BERTScore, F1, latency, and data drift.

**CAG vs RAG Evaluation Framework (Medical Genomics)** · with Prof. Madurima Vardhan, IU<br>
LLM-based benchmarking framework (LangChain, FAISS) comparing RAG, CAG, and CRAG on biomedical question answering across Llama 3.1, OpenBioLLM, and BioMistral, profiled on IU BigRed200 HPC (SLURM, A100 GPUs) to characterize the latency vs accuracy trade-off. *(Research in progress)*

**Modular RAG Pipeline for Accounting Documents** · with Prof. Golshan, IU<br>
Context-aware chunking, retrieval, and aggregation over long financial filings, emitting structured JSON and tabular output. Swappable components (input source, prompt template, output schema) so pipelines reconfigure without touching core code.

**Self-Supervised Representation Learning (ResNet; CLTT/CTTT)** · [cltt_bigred](https://github.com/Dheeraj31104/cltt_bigred)<br>
Contrastive self-supervised learning to learn representations from unlabeled data, with a reproducible training and evaluation workflow.

---

### 🧰 Tech Stack

- **Programming:** Python (NumPy, Pandas, FastAPI, pytest), SQL, R
- **LLMs and GenAI:** LangChain, MCP, RAG, FAISS, LoRA, prompt engineering, Anthropic / OpenAI / Hugging Face APIs
- **Machine Learning:** scikit-learn, PyTorch, XGBoost, SHAP, model evaluation
- **MLOps and Software:** Git, Jenkins CI/CD, Docker, Airflow, MLflow, Databricks, Spark / PySpark, Terraform
- **Cloud and Data:** AWS (Lambda, Bedrock, IAM, DynamoDB), GCP, BigQuery, PostgreSQL, Hadoop, Hive
- **Analytics:** Tableau, Power BI, Matplotlib, Seaborn

---

### 🏗️ Industry Highlights

- **IBM (Barclays Retail Banking):** Built Hadoop/Spark and Ab Initio pipelines processing 10M+ rows of retail banking data; automated data validation frameworks that cut debugging effort by 80%; led platform migration of 108 workflows and 448 ETL jobs (Cloudera CDH to BDH, RHEL6 to RHEL8), improving performance by 25%.
- **TCS (Virgin Media):** Deployed a Rasa NLU classification model at 90% F1 score; designed SCD Type 1/2 models for a 645-table Netezza-to-BigQuery migration with data integrity during cutover; maintained 99% SLA across batch and near-real-time pipelines.

---

### 📜 Certifications

MITx: Machine Learning with Python (2024), Fundamentals of Statistics (2024), Probability (2024) · IBM: Python for Data Science (2023)

### 📫 Contact

[LinkedIn](https://www.linkedin.com/in/karanamdheeraj) · karanamdheeraj2024@gmail.com
