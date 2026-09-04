## Hi, I'm Aleksander!

I am an **Artificial Intelligence** student at the **Poznan University of Technology**. I am a passionate software developer and data enthusiast focusing on building interactive web applications, data visualization pipelines, and exploring AI-driven solutions. 

Beyond pure backend and AI logic, I have a deep passion for high-fidelity architectural design in Minecraft and sports like tennis, cycling, and mountain hiking.

---

### Technical Stack

* **Languages:** Python, R, JavaScript, Bash, Java, C++
* **DevOps:** Docker, Ubuntu/Linux
* **Data & Tools:** Data Visualization, Git, Vector Databases (Qdrant)
* **Backend & AI:** FastAPI, LangGraph, LangChain, RAG, SQL
* **Frontend:** React, HTML/CSS

---

### Featured Projects

#### 📖 [BiblAI](https://github.com/Oleq202/BiblAI)
An agentic claim verification engine that evaluates natural language statements against a canonical scripture corpus using iterative retrieval and structured reasoning.
* **Stack:** Python, LangGraph, Qdrant, Google Gemini, FastAPI, Sentence-Transformers, Docker
* **Focus:** Built an Agentic RAG pipeline using LangGraph with a cyclical feedback loop that bridges vocabulary mismatch via HyDE query expansion, runs hybrid Dense (Qdrant) + Sparse (BM25 with Polish lemmatization) retrieval fused via Reciprocal Rank Fusion, and reranks candidates with a multilingual Cross-Encoder. Enforced strict Pydantic structured outputs with grounded verse citations, and developed an automated evaluation suite featuring Recall@K benchmarks and an independent LLM-as-a-Judge validation harness.

#### 🏁 [F1 Grid Sense](https://github.com/Oleq202/F1-Grid-Sense)
A machine learning pipeline and web app that predicts F1 race finishing order from pre-race data, then compares predictions against actual results.
* **Stack:** Python, scikit-learn, FastAPI, SQLite, FastF1
* **Focus:** Built a walk-forward cross-validated Random Forest model on ~145 non-sprint races (2018–present), avoiding lookahead leakage by training only on prior races. Exposed via a FastAPI backend and HTML/JS frontend showing predicted vs. actual finishing order, per-race rank correlation, and error metrics benchmarked against a naive grid-order baseline.

#### 🏢 [Structura](https://github.com/Oleq202/Structura)
A full-stack field service management system for property maintenance that enables building administrators to assign work orders and contractors to resolve them on-site.
* **Stack:** React 19, FastAPI, PostgreSQL, JWT Authentication, TailwindCSS
* **Focus:** Implemented three-tier role-based access control (Admin, Manager, Contractor) with scoped permissions, complete audit trail system for task modifications, and geographic organization of buildings by city/district for efficient regional management.

#### 🏎️ [F1-Analyzer Dashboard](https://github.com/Oleq202/F1-PUTwall)
An interactive, full-stack data analysis platform designed to visualize historical Formula 1 racing data, driver performance, and telemetry strategies.
* **Stack:** React, FastAPI, PostgreSQL, OpenF1 API
* **Focus:** Built a responsive dashboard frontend to process and map complex telemetry datasets into highly informative visual graphs.

---

### Contact
I am actively looking for opportunities in full stack development or AI deployment.

* **Linkedin:** https://www.linkedin.com/in/aleksander-widman/
* **Email:** aleksander.widman@gmail.com
