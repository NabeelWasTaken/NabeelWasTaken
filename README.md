<!-- Profile README -->

<!-- Header -->
<p align="center">
  <img src="https://img.shields.io/badge/AI%2FML-Builds%20That%20Ship-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Cloud-AWS-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Data-Postgres%20%7C%20Supabase-blue?style=for-the-badge" />
</p>

<h1 align="center">Hi, I'm Nabeel 👋</h1>
<p align="center">
  I build practical AI, clean backends, and cloud deployments that stick.
  I like turning messy data into reliable products with clear metrics.
</p>

<p align="center">
  <a href="mailto:nabeeluni2021@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-informational?logo=gmail&style=flat-square" /></a>
  <a href="https://www.linkedin.com/in/nabeel03/"><img src="https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin&style=flat-square" /></a>
</p>

---

## 🔧 What I focus on
- **Recommendation Systems** — retrieval and ranking with TensorFlow Recommenders, FastAPI serving, and measurable impact
- **Applied Computer Vision for Catalogs** — image embeddings for visually similar products, ANN search (FAISS/ScaNN), and batch/online pipelines for e-commerce
- **LLM-backed Evaluation & Automation** — rubric-aligned grading, schema-validated structured outputs, and eval harnesses to track quality and regressions
- **Data-heavy backends** — typed contracts, observability, and straightforward deployments
- **AWS automation** — S3 + CloudFront, Route 53, Lambda, GitHub Actions, safe rollbacks

---

## 🚀 Notable Projects I've Worked On
- 🛒 **Danube Home Recommendation System (production)**
  - Built “Customers also bought” with **TensorFlow Recommenders**, exported to **TF Serving**, wrapped in **FastAPI**
  - Designed offline eval (Recall@K, NDCG) and tracked online metrics like CTR and add-to-cart lift
- 🏗️ **BuildMapper — Contractor Connection Graph**
  - Surfaced trusted subcontractor relationships using shared project history
  - **Postgres/Supabase**, RLS, overlap and recency-weighted ranking for connection strength
- ☁️ **CloudFront + Lambda Subdomain Automation (Boons)**
  - Deployed SPA to **S3 + CloudFront** and automated **subdomain wiring with Lambda**
  - Result: zero-touch releases after push with predictable cache invalidations
- 🎓 **Graider (CalHacks)**
  - AI grading from rubrics with a clean dashboard, question parsing, and structured feedback
  - **Python, FastAPI, Reflex (Pynecone), Postgres**

---

## 🧩 Selected Projects

### 1) Danube Home — “Customers Also Bought”
**Stack:** TensorFlow Recommenders, Keras, TF Serving, FastAPI, Redis, batch + streaming ingestion  
**Notes:** clear separation of retrieval vs. ranking, offline evaluation + online tracking, reproducible training jobs

### 2) BuildMapper — Contractor Graph for Construction Trades
**Stack:** Postgres/Supabase, SQL, RLS, server-side functions  
**Notes:** score = f(shared projects, role overlap, recency). Transparent ranking and queryable audit trail

### 3) Boons — CloudFront + Lambda Subdomain Automation (Under Process ⛏)
**Stack:** S3, CloudFront, Route 53, Lambda, GitHub Actions  
**Notes:** IaC-style setup, safe rollbacks, invalidation strategy documented in README

### 4) Graider — AI Grading System
**Stack:** Python, FastAPI, Reflex/Pynecone, Postgres  
**Notes:** rubric-based scoring, structured feedback, upload → parse → evaluate → return annotated results

### 5) Visual Similarity for Furniture/E-commerce
**Stack:** Python, CV, embedding search, FastAPI  
**Notes:** image → embedding → nearest-neighbor lookup to suggest visually similar products

---

## 🛠️ Tech
**Languages:** Python, TypeScript/JavaScript, SQL, Java, C++  
**ML/AI:** TensorFlow, Keras, TensorFlow Recommenders, scikit-learn, PyTorch 
**Backend:** FastAPI, Node/Express, REST, webhooks, background jobs  
**Data:** Postgres, Supabase, Redis, CSV/Parquet pipelines, MySQl, MongoDB  
**Cloud/DevOps:** AWS (IAM, S3, CloudFront, Lambda, EC2, Route 53), Docker, GitHub Actions  
**Frontend:** React, Tailwind, Reflex (Pynecone)  
**Quality:** pydantic, Joi, pytest, structured logging, metrics

<p>
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-Recommenders-FF6F00?logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-Production-009688?logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Postgres-DB-336791?logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-Backend-3ECF8E?logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-S3%20%7C%20CloudFront%20%7C%20Lambda-232F3E?logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-Ready-2496ED?logo=docker&logoColor=white" />
</p>

---

## 📐 Engineering Principles
- Ship thin slices and measure impact
- Separate retrieval and ranking, track offline and online metrics
- Prefer clear contracts and typed schemas
- Keep pipelines observable: logs, counters, dashboards, alerts

---

## 📫 Contact
- Email: nabeeluni2021@gmail.com
- LinkedIn: https://www.linkedin.com/in/nabeel03/


---


<!-- Optional: GitHub stats (uncomment and set your username) -->
<!--
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=<your-github-username>&show_icons=true" />
  <img src="https://streak-stats.demolab.com?user=<your-github-username>" />
</p>
-->

<!-- Footer -->
<p align="center">
  <sub>When I am not shipping features I am watching or playing football, and tinkering with computer vision projects.</sub>
</p>
