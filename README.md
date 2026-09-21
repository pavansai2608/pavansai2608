### Hi, I'm Pavan 👋

I build AI and ML systems end to end — data pipeline, model, service, cluster, CI — and I measure whether they actually work. B.Tech CSE (Data Science) at NIIT University. **Open to internships.**

**What I've built:**

🩺 **[Bill Auditor](https://github.com/pavansai2608/bill-auditor)** — Agentic RAG that audits Indian health insurance bills clause by clause and names the exact clause behind every deduction. **Zero fabricated citations across every recorded eval version (v0–v12)**, a 399-clause hybrid index (BM25 + embeddings with cross-encoder reranking), 492 tests, 8-stage Jenkins pipeline on Kubernetes. The model never does arithmetic — every rupee figure is computed in Python. The eval harness documents what its own accuracy number does *not* prove.

⚙️ **[Predictive Autoscaling](https://github.com/pavansai2608/predictive-autoscaling)** — Forecasts a Kubernetes service's request rate 60 s ahead with a LightGBM quantile model and scales before the load lands. **p99 latency 62% lower than the stock HPA** (479 → 183 ms) for 28% more compute, three runs per arm on byte-identical traffic — and it reports the scenario where forecasting alone *loses*, plus the composition that fixes it.

📊 **[Customer Segmentation & Retention](https://github.com/pavansai2608/customer-segmentation-retention)** — RFM + K-Means segmentation, BG/NBD + Gamma-Gamma lifetime value, and XGBoost churn prediction (ROC-AUC 0.788) over 542K transactions, combined into a ranked retain / nurture / let-go decision for 4,334 customers. FastAPI + React, MLflow experiment tracking, DVC-tracked artifacts, live on Render.

🛒 **[MSME Marketplace](https://github.com/pavansai2608/msme-marketplace)** — Inherited a four-person codebase and audited it end to end: found and fixed a privilege-escalation path that let any logged-in user make themselves admin, two endpoints leaking customers' names and addresses, and a feature advertised as "XGBoost forecasting" that was a hardcoded constant. Rebuilt auth on httpOnly cookies with refresh-token rotation and CSRF protection, built a real hybrid recommender as its own FastAPI service, took the project from zero to 133 tests, and deployed it on k3s with automatic TLS.

**Tech I work with:**
Python · FastAPI · LangGraph/LangChain · scikit-learn · LightGBM · XGBoost · pandas · Node.js · React · MongoDB · MySQL · ChromaDB · Docker · Kubernetes · Jenkins · MLflow · DVC · Prometheus · AWS

📫 [LinkedIn](https://www.linkedin.com/in/pavan-sai-krishna-goli-b5a557291) · [Portfolio](https://portfolio-two-rho-1efh6kojg3.vercel.app)
