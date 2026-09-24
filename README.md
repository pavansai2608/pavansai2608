### Hi, I'm Pavan 👋

I build AI and ML systems end to end — data pipeline, model, service, cluster, CI — and I measure whether they actually work. B.Tech CSE (Data Science) at NIIT University. **Open to internships.**

**What I've built:**

🩺 **[Bill Auditor](https://github.com/pavansai2608/bill-auditor)** — Audits health insurance bills against the policy document line by line, and names the exact clause behind every deduction. Where no clause clearly applies, the line is flagged for a human rather than guessed at. **Zero fabricated citations across every recorded eval version (v0–v12)**, and the model never does arithmetic — every rupee figure is computed in Python.

⚙️ **[Predictive Autoscaling](https://github.com/pavansai2608/predictive-autoscaling)** — Autoscalers react after the traffic has already arrived, so the first users of a spike pay for it. This forecasts the request rate 60 s ahead and scales before the load lands. **p99 latency 62% lower than the stock HPA** (479 → 183 ms) for 28% more compute — and it reports the scenario where forecasting alone *loses*.

🎫 **[Complaint Classification & Resolution System](https://github.com/pavansai2608/complaint-classification-system)** — Support teams read every complaint before they know which one is urgent, so the angriest customer often waits the longest. This reads each complaint as it arrives, works out what it is about and how upset the customer is, and orders the queue by urgency instead of arrival time. It also drafts a reply the agent edits before sending. **78.8% accuracy, 0.79 macro-F1** on a held-out set, with low-confidence cases handed to a human. [Live example, no account needed](https://3-105-252-57.sslip.io).

📊 **[Customer Segmentation & Retention](https://github.com/pavansai2608/customer-segmentation-retention)** — A retention budget gets spread evenly across customers who are worth very different amounts. This turns 542K transactions into a ranked retain / nurture / let-go decision for 4,334 customers: who is worth keeping, what they are likely to spend next, and who is about to leave. **Churn ROC-AUC 0.788**, live on Render.

🛒 **[MSME Marketplace](https://github.com/pavansai2608/msme-marketplace)** — Inherited a four-person e-commerce codebase for small Indian manufacturers and made it fit to run: replaced a feature advertised as "XGBoost forecasting" that was a hardcoded constant with a real recommender, fixed the access-control and data-exposure bugs the audit surfaced, took the project from zero tests to 133, and deployed three services on AWS k3s with automatic TLS.

**Tech I work with:**
Python · TypeScript · FastAPI · LangGraph/LangChain · scikit-learn · LightGBM · XGBoost · transformers · pandas · Node.js · Express · React · MongoDB · MySQL · ChromaDB · Docker · Kubernetes · Jenkins · MLflow · DVC · AWS

📫 [LinkedIn](https://www.linkedin.com/in/pavan-sai-krishna-goli-b5a557291) · [Portfolio](https://portfolio-two-rho-1efh6kojg3.vercel.app)
