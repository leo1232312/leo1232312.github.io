---
permalink: /
title: "Yihang Jiang"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

## About Me {#about}

I am **Yihang Jiang**, an undergraduate student majoring in **Artificial Intelligence** at **South China University of Technology (SCUT)**.  
My research interests focus on **Natural Language Processing (NLP)** and **Educational Assessment**, especially **Automated Essay Scoring (AES)** and **reliable score–feedback alignment**. :contentReference[oaicite:3]{index=3} :contentReference[oaicite:4]{index=4}

**Current focus:** building *stable and consistent* scoring systems by combining **neural scorers** with **Teacher LLM calibration**, mitigating **scale drift** and **score–feedback misalignment**. :contentReference[oaicite:5]{index=5}


## Research {#research}

### Automated Essay Scoring with Task-Adaptive Prior Injection
I work on a collaborative AES framework that **anchors a Teacher LLM with numerical priors** and **task-adaptive contextual signals** (e.g., genre/level hints), enforcing a structured *reasoning-before-scoring* workflow.  
Key components include **delta calibration**, **legality projection (integer-only + range clipping)**, and **schema-validated structured outputs**, aiming to improve both **scoring accuracy** and **run-to-run stability**, while producing **rubric-grounded diagnostic feedback**. :contentReference[oaicite:6]{index=6}


## Publications {#publications}

- **Towards Reliable and Consistent Essay Scoring: A Collaborative Framework with Task-Adaptive Prior Injection**  
  *ACL 2026 submission (under review).*  
  **Keywords:** Automated Essay Scoring, Teacher LLM, prior injection, scale drift, score–feedback alignment. :contentReference[oaicite:7]{index=7}


## Projects {#projects}

### 1) Prior-Injection AES: Reliable Scoring & Consistent Feedback Calibration (ACL 2026)
- Built a hybrid scoring pipeline that integrates **stable neural priors** with **Teacher LLM calibration**, constrained by **task-adaptive signals** (genre/level/range hints).
- Implemented **context-constrained reasoning** with **delta correction** and **legality projection**, plus **JSON schema validation** to ensure controllable, reproducible outputs.
- Conducted repeated-decoding consistency evaluation and ablations on **ASAP/ASAP++**, improving stability and rubric-aligned feedback quality. :contentReference[oaicite:8]{index=8} :contentReference[oaicite:9]{index=9}

### 2) MCM/ICM 2025 (Problem C): Olympic Success Prediction & “Great Coach” Effect
- Proposed an integrated framework combining **XGBoost medal count prediction**, **Bayesian Probit Regression with MCMC**, **Fixed Effects Models**, and **Lagged Regression**.
- Performed **feature engineering** and interpretability analysis via **SHAP**, and quantified uncertainty for “first medal” probability estimation.
- Output a complete modeling–validation–report pipeline with reproducible results and actionable insights for strategy planning. :contentReference[oaicite:10]{index=10}

### 3) Baidu Brain Cup (Student Innovation Competition) — Real-time Visual Tracking & Closed-loop Control
- Designed a “perception–decision–actuation” closed-loop system on **Raspberry Pi**.
- Implemented **real-time target detection/tracking** using **OpenCV**, computed target coordinates, and controlled an actuator via a **stepper motor module** to track motion trajectories.
- Integrated embedded hardware wiring, sensor interfaces, motor driving, and system debugging for an end-to-end prototype. :contentReference[oaicite:11]{index=11}


## Awards {#awards}

- **MCM/ICM 2025 — Meritorious Winner (Problem C)** :contentReference[oaicite:12]{index=12} :contentReference[oaicite:13]{index=13}
- **Baidu Brain Cup Student Innovation Competition — Third Prize** :contentReference[oaicite:14]{index=14}


## Skills {#skills}

- **NLP / ML:** supervised learning, text modeling, evaluation metrics, error analysis; AES & rubric-aligned feedback generation. :contentReference[oaicite:15]{index=15}
- **LLM Engineering:** deployment & inference services, API integration, prompt/pipeline design for controllability. :contentReference[oaicite:16]{index=16}
- **Modeling:** XGBoost, Bayesian Probit + MCMC, fixed effects / lagged regression, SHAP interpretability. :contentReference[oaicite:17]{index=17}
- **Programming:** Python (data processing, training, reproduction, analysis). :contentReference[oaicite:18]{index=18}


## CV {#cv}

- **PDF:** [Download CV](files/cv.pdf)  
- **Email:** leojyh123456@gmail.com :contentReference[oaicite:19]{index=19}


## Contact {#contact}

If you are interested in research collaboration or RA opportunities, feel free to reach out:
- **Email:** leojyh123456@gmail.com :contentReference[oaicite:20]{index=20}
- **GitHub:** https://github.com/leo1232312
