# Awesome-Model-Risk-Management

## Top Model Risk Management (AI) Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on AI Governance, Model Inventory, Fairness, Drift Monitoring, Explainability, Validation & Regulatory Compliance*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Model Risk Management (MRM) / AI Governance**. These systems help organizations inventory models, monitor performance and drift, assess fairness and bias, document validation, enforce policies, and meet emerging AI regulations (EU AI Act, NIST AI RMF, SR 11-7-style expectations, etc.).



**Examples** include ModelOp, Fiddler AI, Arthur AI, Monitaur, IBM watsonx.governance, SAS Model Manager, DataRobot AI Governance, Truera, FairNow, and Holistic AI (the category leaders).



**Open-source emphasis**: Full enterprise MRM/governance platforms are mostly commercial. Strong open building blocks exist for **fairness** (Fairlearn, AIF360), **monitoring** (Evidently, WhyLogs), **explainability** (Alibi, SHAP), and emerging open AI-governance projects. This section lists the strongest available open resources and is realistic about the governance-system-of-record gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[ModelOp](https://www.modelop.com/)**  

  Enterprise AI governance and model operations platform acting as a system-of-record for model inventory, lifecycle controls, and compliance across ML, GenAI, and agentic systems.



- **[Fiddler AI](https://www.fiddler.ai/)**  

  AI observability and model performance platform focused on monitoring, explainability, fairness, and drift for models and LLMs in production.



- **[Arthur AI](https://www.arthur.ai/)**  

  AI performance and governance platform providing monitoring, explainability, and controls for machine learning and generative AI systems.



- **[Monitaur](https://monitaur.ai/)**  

  Model risk and AI governance platform oriented toward regulated industries, emphasizing documentation, evidence, and audit-ready controls.



- **[IBM watsonx.governance](https://www.ibm.com/watsonx)**  

  Governance module within the watsonx portfolio for model inventory, factsheets, risk workflows, and alignment with AI regulations.



- **[SAS Model Manager](https://www.sas.com/)**  

  Established model management and governance capabilities within the SAS analytics ecosystem for validation, monitoring, and deployment control.



- **[DataRobot AI Governance](https://www.datarobot.com/)**  

  Governance and compliance features integrated with DataRobot’s AI platform for model lifecycle oversight and risk management.



- **[Truera (now part of DataRobot ecosystem / related offerings)](https://www.datarobot.com/)**  

  Explainability and model-intelligence technology historically focused on debugging, fairness, and governance of ML models.



- **[FairNow](https://www.fairnow.ai/)**  

  AI fairness and compliance-oriented platform helping organizations assess and document bias and regulatory alignment.



- **[Holistic AI](https://www.holisticai.com/)**  

  AI governance and risk platform supporting inventory, assessment, and compliance workflows including EU AI Act-oriented capabilities.



## Open-Source GitHub Projects

- **[Fairlearn](https://github.com/fairlearn/fairlearn)**  

  Python package for assessing and mitigating unfairness in machine learning models, with metrics and algorithms widely used in responsible-AI workflows.



- **[AI Fairness 360 (AIF360)](https://github.com/Trusted-AI/AIF360)**  

  Comprehensive open-source toolkit from IBM for detecting, understanding, and mitigating bias in ML models throughout the lifecycle.



- **[Evidently](https://github.com/evidentlyai/evidently)**  

  Open-source ML and LLM observability library for data drift, model performance, data quality, and monitoring reports.



- **[WhyLogs / WhyLabs open components](https://github.com/whylabs)**  

  Open logging and profiling libraries for data and model monitoring that feed into observability and governance pipelines.



- **[Alibi / Alibi Detect](https://github.com/SeldonIO/alibi)**  

  Open-source Python libraries for ML model inspection, explanation, and outlier/drift detection.



- **[SHAP](https://github.com/shap/shap)**  

  Widely used open-source framework for explaining model predictions (game-theoretic feature attributions).



- **[InterpretML](https://github.com/interpretml/interpret)**  

  Open-source toolkit for training interpretable models and explaining black-box systems.



- **[VerifyWise and open AI governance projects](https://github.com/)**  

  Emerging open-source AI governance platforms aimed at inventory, risk assessment, and regulatory alignment (e.g., EU AI Act / ISO 42001-oriented workflows).



- **[Great Expectations / data validation open tools](https://github.com/great-expectations/great_expectations)**  

  Open data validation frameworks often used as part of model-risk and data-quality controls.



- **[Model cards and documentation open templates](https://github.com/)**  

  Community templates and tools for model cards, datasheets, and governance documentation.



### Additional Strong Open-Source Options

- Combining **Fairlearn + AIF360** for fairness assessment and mitigation research and pre-production checks.

- Using **Evidently + Alibi + SHAP** for production monitoring, drift, and explainability pipelines.

- Adopting open model-card and inventory templates as a lightweight governance starting point.

- Accepting that enterprise model inventories, policy engines, audit workflows, regulatory mapping, and cross-model risk aggregation still favor commercial platforms (ModelOp, IBM watsonx.governance, Fiddler, Arthur, Monitaur, SAS, DataRobot, Holistic AI, etc.).

- Focusing open-source efforts on transparency of metrics, reproducible fairness tests, and ownership of monitoring data.



**Frameworks for building custom systems**: Maintain a model inventory (even a structured registry) → run fairness and validation tests with Fairlearn/AIF360 → monitor production with Evidently/Alibi → generate model cards and audit evidence → escalate high-risk models to a commercial governance platform when required. Suitable for teams building internal AI risk capabilities. Regulated enterprises typically still adopt commercial MRM/AI-governance platforms for system-of-record and exam readiness.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Model risk management and AI governance intersect with financial regulation, the EU AI Act, and other emerging rules. Open-source tools alone rarely satisfy formal model-risk or regulatory expectations without additional process, documentation, and oversight. This list is not legal, regulatory, or compliance advice.



---

**Made for model risk officers, AI governance leads, and ML engineers building responsible AI systems.**

Let's keep AI risk management rigorous, transparent, and as open as practical.
