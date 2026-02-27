# CHAOJIE ZHANG

Milsons Point, NSW 2061, Australia  
Tel: +61 474 845 288 | Email: Zhangcj330@gmail.com | LinkedIn: https://www.linkedin.com/in/chaojie-zhang

---

## EXECUTIVE SUMMARY

**I deploy GenAI like an engineer and sell it like a consultant.**

AI Deployment Engineer / ML Engineer with ~**5 years** across consulting + enterprise delivery (incl. internship experience), focused on turning GenAI into **production adoption**.
I build decision and automation systems teams rely on—e.g., a Command Centre real-time hazard map (**10–30 DAU**, ~**30‑min** refresh) that cut response decisions from **days to hours**, supporting outreach at **millions-of-customers** scale.
I also ship high-leverage automation and GenAI products end-to-end, including IFRS17 reporting automation (**60+ hours → ~10 minutes**) and BrickAI (production agentic app; **Actuarial Summit 2025 speaker**, ~**200** attendees).

---

## CORE SKILLS

- **GenAI deployment:** OpenAI API (chat + function/tool calling), structured outputs (JSON), RAG/vision prototyping, agent/tool integration (MCP)
- **Enterprise delivery:** use-case qualification, roadmap/backlog, exec communication, stakeholder management, time-to-value
- **Engineering:** Python, JavaScript (Next.js), API design (FastAPI), CI/CD (GitHub Actions), observability (New Relic)
- **Cloud/infra:** Kubernetes, Helm, Terraform, Docker; AWS (Lambda/SageMaker/Redshift)
- **Data:** dbt + BigQuery, geospatial analytics; familiarity with Snowflake/Databricks/Athena

---

## EXPERIENCE

### IAG — Data Engineer (API, AI/LLM, Deployment)
Sydney, NSW | Sep 2025 – Present

- Built a real-time **situational awareness** map for natural hazard events used in the Command Centre by ~**10–30 daily active users** (senior operational decision makers); enabled continuous monitoring during major events and reduced response decisions from **day-level to hour-level**, supporting outreach at scale (e.g., **millions of customers** in major hail events; **tens of thousands of policies** in bushfires).
- Designed the geospatial analytics layer and data model (claims + policy + hazard layers), including scheduled refresh pipelines (typically **~30-minute** updates) powering real-time operational dashboards.
- Delivered a production deployment on **Kubernetes** (Helm-based), integrating **CARTO** and **BigQuery**-backed querying to render live metrics on a map; implemented CI/CD via **GitHub Actions** with **approval gates** for production changes.
- Operated within enterprise data governance: contributed designs in the **Data & AI Architecture Forum (DAF)**; aligned to “single view” data products (e.g., **Single View of Property/Claims/Policy/Customer**) built on **dbt + BigQuery** with a controlled ingress layer.
- Partnered with senior stakeholders (GM/exec audiences) to define the operating model and metrics on the map (e.g., **claim count**, total damage, **sum insured**, hail distribution, roof type / solar panel distribution), and iterated based on feedback.
- Led use-case qualification and roadmap discussions for Command Centre decisioning workflows, translating stakeholder needs into a prioritized backlog and measurable success criteria.
- Supported safe operations with auditability and observability: leveraged **BigQuery query history** and platform logging across CARTO/Kubernetes with **New Relic**.
- Built reusable internal data services and packaged selected API calls into **MCP tools** for reuse by emerging agent workflows.

### Dataly — Senior Data/AI Consultant
Sydney, NSW | Nov 2023 – Sep 2025

- Automated monthly **IFRS17** valuation reporting end-to-end for Suncorp NZ, reducing cycle time from **60+ hours to ~10 minutes** and improving timeliness and reliability of regulatory reporting.
- Led GenAI/ML prototypes from discovery to executive-ready demos (Text-to-SQL exploration; claims decision-support concepts using tool calling + OCR/Vision + **PDS-grounded RAG**); helped stakeholders evaluate feasibility/ROI and make build-vs-buy decisions.
- Led discovery with business and technical stakeholders; translated needs into build plans, demos, and measurable success metrics.
- Codified learnings into reusable assets (templates, demo flows, and guidance) to help teams replicate wins across multiple stakeholders and workstreams.

### Servian — Associate Consultant
Sydney, NSW | Mar 2022 – Nov 2023

- **News Corp AU (Recommendations):** Delivered a production-grade, end-to-end recommendation pipeline for real-time personalized news using **Python, AWS Lambda, FastAPI**, and scalable cloud infrastructure.
- **Pylon (Computer Vision):** Trained and deployed a rooftop segmentation model (Mask R-CNN + custom post-processing), achieving **0.73 mAP (bbox)** / **0.71 mAP (segmentation)** and **<300ms** inference.

---

## SELECTED PROJECTS

### Founder / AI Engineer — BrickAI (Consumer GenAI Agent for Property Search)
2025 – Present | www.thebrickai.com

- Built and shipped a consumer-facing GenAI product for Australian property search and suburb selection; reached **<200** trial users.
- Took the product to market through live demos and community engagement: **speaker** at **Actuarial Summit 2025** (≈**200** attendees; room at capacity) and regular showcases at **AI meetups/conferences**, collecting feedback and iterating the roadmap.
- Owned the business narrative end-to-end: created product strategy materials and a **business plan** for a government grant application (**under review**).
- Built the agentic core using **OpenAI chat + function/tool calling** with **structured JSON outputs**, and improved reliability via trace/log-driven iteration (LangSmith-style conversation/transaction logs).

### GenAI / Claims — PDS-grounded RAG + Vision/OCR (Consulting prototypes)

- Prototyped claims decision-support concepts combining document extraction (OCR/vision), tool calling, and policy-grounded retrieval to improve faithfulness and reduce manual lookup.

---

## RESOURCES (Writing / Open-source)

- Medium: **“Three ways to structure tool calling with LLM agent — a security perspective”** (prompt injection / auth)  
  https://medium.com/@zhangcj330/three-ways-to-structure-tool-calling-with-llm-agent-a-security-perspective-0c30f637b4ee
- Resume repo: https://github.com/choosiezhang-bot/super-choosie-resume

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
