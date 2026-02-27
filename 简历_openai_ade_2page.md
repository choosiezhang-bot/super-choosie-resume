# CHAOJIE ZHANG

Milsons Point, NSW 2061, Australia  
Tel: +61 474 845 288 | Email: Zhangcj330@gmail.com | LinkedIn: https://www.linkedin.com/in/chaojie-zhang

---

## EXECUTIVE SUMMARY

**I deploy GenAI like an engineer and sell it like a consultant.**

AI Deployment Engineer / ML Engineer with ~4+ years delivering enterprise AI and data products in insurance and consulting, plus a production GenAI app.
I turn GenAI capability into adoption by moving customers from **use-case → architecture → production**, with disciplined delivery (governance, CI/CD approval gates, observability) and strong stakeholder alignment.
I’ve shipped a Command Centre real-time hazard map (**10–30 DAU**, ~**30‑min** refresh) cutting response decisions from **days to hours**, and automated IFRS17 reporting from **60+ hours to ~10 minutes**—built hands-on with **OpenAI API (chat + function calling)**, governed “single view” data products (dbt + BigQuery), and **Kubernetes/Helm** with **New Relic**.

---

## CORE SKILLS

- **GenAI/LLM:** OpenAI API (chat + function calling), structured outputs (JSON), RAG, prompt engineering, vision/multimodal prototyping, agent/tool integration (MCP)
- **Backend/Apps:** Python, FastAPI, API design, automation, CI/CD (GitHub Actions / GitLab CI)
- **Frontend:** JavaScript, Next.js (production web app)
- **Cloud/Infra:** AWS (Lambda, SageMaker, Redshift, CloudWatch), Kubernetes, Helm, Terraform, Docker
- **Data Platforms:** BigQuery, Redshift, Snowflake, Databricks, Athena, Teradata; Spark
- **ETL/Orchestration:** dbt, PySpark, AWS Glue, Kinesis, Airflow, Fivetran; Azure Data Factory
- **Observability:** New Relic (platform logs/monitoring)

---

## EXPERIENCE

### IAG — Data Engineer (API, AI/LLM, Deployment)
Sydney, NSW | Sep 2025 – Present

- Built a real-time **situational awareness** map for natural hazard events used in the Command Centre by ~**10–30 daily active users** (senior operational decision makers); enabled continuous monitoring during major events and reduced response decisions from **day-level to hour-level**, supporting outreach at scale (e.g., **millions of customers** in major hail events; **tens of thousands of policies** in bushfires).
- Designed the geospatial analytics layer and data model (claims + policy + hazard layers), including scheduled refresh pipelines (typically **~30-minute** updates) powering real-time operational dashboards.
- Delivered a production deployment on **Kubernetes** (Helm-based), integrating **CARTO** and **BigQuery**-backed querying to render live metrics on a map; implemented CI/CD via **GitHub Actions** with **approval gates** for production changes.
- Operated within enterprise data governance: contributed designs in the **Data & AI Architecture Forum (DAF)**; aligned to “single view” data products (e.g., **Single View of Property/Claims/Policy/Customer**) built on **dbt + BigQuery** with a controlled ingress layer.
- Partnered with senior stakeholders (GM/exec audiences) to define the operating model and metrics on the map (e.g., **claim count**, total damage, **sum insured**, hail distribution, roof type / solar panel distribution), and iterated based on feedback.
- Supported safe operations with auditability and observability: leveraged **BigQuery query history** and platform logging across CARTO/Kubernetes with **New Relic**.
- Built reusable internal data services and explored packaging API calls into **MCP tools** for reuse by emerging agent workflows.

### Dataly — Senior Data/AI Consultant
Sydney, NSW | Nov 2023 – Sep 2025

- Automated monthly **IFRS17** valuation reporting end-to-end for Suncorp NZ, reducing cycle time from **60+ hours to ~10 minutes** and improving timeliness and reliability of regulatory reporting.
- Led GenAI/ML prototypes from discovery to executive-ready demos (Text-to-SQL exploration; claims decision-support concepts using tool calling + OCR/Vision + **PDS-grounded RAG**); helped stakeholders evaluate feasibility/ROI and make build-vs-buy decisions.
- Worked across architecture and implementation (Python + cloud + data platforms), translating stakeholder needs into build plans, demos, and success metrics.

### Servian — Associate Consultant
Sydney, NSW | Mar 2022 – Nov 2023

- **News Corp AU (Recommendations):** Delivered a production-grade, end-to-end recommendation pipeline for real-time personalized news using **Python, AWS Lambda, FastAPI**, and scalable cloud infrastructure.
- **Pylon (Computer Vision):** Trained and deployed a rooftop segmentation model (Mask R-CNN + custom post-processing), achieving **0.73 mAP (bbox)** / **0.71 mAP (segmentation)** and **<300ms** inference.

---

## SELECTED PROJECTS

### Founder / AI Engineer — BrickAI (Consumer GenAI Agent for Property Search)
2025 – Present | www.thebrickai.com

- Built and shipped a consumer-facing GenAI product for Australian property search and suburb selection; reached **<200** trial users.
- Implemented an agentic workflow centered on **chat + tool/function calling** with **structured JSON outputs** to orchestrate multi-step retrieval and ranking.
- Built a Next.js (**JavaScript**) frontend and iterated rapidly using user feedback and lightweight human evaluation (task completion, retrieval quality, image understanding accuracy).
- Instrumented conversation/transaction logs (LangSmith-style) to compare runs and improve prompts/tools based on real user traces.

### GenAI / Claims — PDS-grounded RAG + Vision/OCR (Consulting prototypes)

- Prototyped claims decision-support concepts combining document extraction (OCR/vision), tool calling, and policy-grounded retrieval to improve faithfulness and reduce manual lookup.

---

## THOUGHT LEADERSHIP

- Published: **“Three ways to structure tool calling with LLM agent — a security perspective”** (prompt injection / auth considerations)  
  https://medium.com/@zhangcj330/three-ways-to-structure-tool-calling-with-llm-agent-a-security-perspective-0c30f637b4ee

---

## ADDITIONAL EXPERIENCE (SELECTED)

### Westpac — Data Engineer / Analyst (Customer Remediation)

- Supported remediation programs through data extraction, reconciliation, and analysis; contributed to triage/prioritization analysis across **~10+ initiatives**, helping reduce operational cost and interest leakage (estimated **~$1M** scale).

---

## EDUCATION

**University of Sydney** — Master of Commerce (Business Analytics and Quantitative Finance)  
Sydney, NSW | Aug 2019 – Dec 2021  
WAM: 81 | Beta Gamma Sigma Australia Alumni Chapter Scholarship

**University of Oklahoma** — Bachelor of Business Administration (Finance)  
Oklahoma, US | Sep 2012 – Dec 2016

---

## CERTIFICATIONS

- Google Cloud Professional Data Engineer
- AWS Certified Cloud Practitioner
- Databricks Data Analyst Associate
- Microsoft Certified: Azure Fundamentals
- Microsoft Certified: Azure AI Fundamentals
- Scrum Master Certified (SMC)
