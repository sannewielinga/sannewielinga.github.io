---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Summary
AI Research Engineer and MSc AI (Open Universiteit, 2025) bridging **research and production**: LLM hallucination detection, **neuro-symbolic** methods (ASP + ML), and **MLOps** on Kubernetes. I design rigorous experiments and then turn results into reliable, maintainable systems.

[GitHub](https://github.com/sannewielinga){: .btn .btn--primary }
[Google Scholar](https://scholar.google.com/citations?user=KE_WpOsAAAAJ){: .btn }
[LinkedIn](https://www.linkedin.com/in/sanne-wielinga-501914114/){: .btn }

Education
======
* **MSc, Artificial Intelligence** — Open Universiteit, **2025**
  * Focus: model-based AI, Answer Set Programming, hybrid ML + logic, LLM evaluation, responsible AI.
* **BSc, Artificial Intelligence** — Vrije Universiteit Amsterdam, **2019**

Experience
======
* AI Research Engineer / ML Engineer — **Crisp (Point-of-Sale)** · 2019–present
  * **Time-series forecasting** platform for stores and operations  
  Built multi-seasonal forecasts (daily/weekly/holiday effects, custom seasonality per store/product) for **sales** and **ticket volumes** used in planning and SLAs.
  * **Tip prediction** models to inform staffing and incentives; deployed as scheduled inference jobs with monitoring.
  * **Recommendations**: production **LightGCN** pipeline producing product recommendations; evaluated with Recall@K / NDCG@K and tuned for cold-start scenarios.
  * **Voice of customer**: review **sentiment analysis** and topic tagging to surface product issues and drive roadmap decisions.
  * **Customer analytics**: **RFM-based clustering**, **churn probability**, and a business-ready **CLV** formulation (frequency, value, horizon, retention) integrated into the dashboard.
  * **Internal support LLM (RAG)**: search-augmented assistant over internal knowledge to speed support and onboarding; guardrails + evaluation harness.
  * **Platform & MLOps**: deployed the customer **portal/dashboard** on **AWS EKS** with **GitLab CI/CD**; containerized services, **K8s CronJobs**, autoscaling, health probes, and certificate management (Let’s Encrypt).  
  All ML services run as **daily/rolling pipelines** with versioned artifacts and alerting.
  * **Collaboration & leadership**: helped lead a team of developers; frequent customer sessions to scope features and validate impact; wrote docs and playbooks.

* AI Research Engineer — **Forward International** · 2024
  * Research on **hallucination detection for smaller LLMs** (medical QA).  
  * Prototyped **hybrid ML + ASP** approaches (FOLD-R++ rules + classic ML) and reproducible experiment pipelines. 

* Data/ML Contractor — **TO THE MARKET** · 7-month contract
  * Delivered data/ML workstreams as an external partner.  


Skills
======
**Research & Methods:** experimental design, ablations, error analysis, statistical testing, eval tooling  
**LLM & Reasoning:** hallucination detection, RAG, prompt/guardrails, **ASP/Clingo**, FOLD-R++  
**ML:** time-series (seasonality/holidays), recommender systems (GNN/LightGCN), classification/regression  
**Data/Platform:** Python (pandas, scikit-learn, PyTorch), SQL, Docker, **Kubernetes** (CronJobs, HPA, probes), **Helm**, **GitLab CI/CD**, **AWS EKS**  
**Analytics:** feature engineering, cohorting (RFM), churn/CLV modeling, dashboards & reporting  
**Practices:** testing, code review, reproducible pipelines, documentation, stakeholder communication

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->
    
Service and leadership
======
* Mentoring and knowledge-sharing on **Kubernetes/MLOps** and **hybrid ML + ASP** across teams; regular customer co-design sessions.
