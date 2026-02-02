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
My research interests focus on **Natural Language Processing (NLP)** and **The application of large language models**, especially **Automated Essay Scoring (AES)**. 

**Current focus:** The application of LLMS.


## Research {#research}

### Automated Essay Scoring with Task-Adaptive Prior Injection
I work on a collaborative AES framework that **anchors a Teacher LLM with numerical priors** and **task-adaptive contextual signals** (e.g., genre/level hints), enforcing a structured *reasoning-before-scoring* workflow.  
Key components include **delta calibration**, **legality projection (integer-only + range clipping)**, and **schema-validated structured outputs**, aiming to improve both **scoring accuracy** and **run-to-run stability**, while producing **rubric-grounded diagnostic feedback**. 


## <i class="far fa-file-alt"></i> Selected Publications
{#publications}


- **Towards Reliable and Consistent Essay Scoring: A Collaborative Framework with Task-Adaptive Prior Injection**  
  *ACL 2026 submission (under review).*  
  **Keywords:** Automated Essay Scoring, Teacher LLM, prior injection, scale drift, score–feedback alignment. 


## Projects {#projects}

### 1) Prior-Injection AES: Reliable Scoring & Consistent Feedback Calibration (ACL 2026)
- Built a hybrid scoring pipeline that integrates **stable neural priors** with **Teacher LLM calibration**, constrained by **task-adaptive signals** (genre/level/range hints).
- Implemented **context-constrained reasoning** with **delta correction** and **legality projection**, plus **JSON schema validation** to ensure controllable, reproducible outputs.
- Conducted repeated-decoding consistency evaluation and ablations on **ASAP/ASAP++**, improving stability and rubric-aligned feedback quality. 

### 2) MCM/ICM 2025 (Problem C): Olympic Success Prediction & “Great Coach” Effect
- Proposed an integrated framework combining **XGBoost medal count prediction**, **Bayesian Probit Regression with MCMC**, **Fixed Effects Models**, and **Lagged Regression**.
- Performed **feature engineering** and interpretability analysis via **SHAP**, and quantified uncertainty for “first medal” probability estimation.
- Output a complete modeling–validation–report pipeline with reproducible results and actionable insights for strategy planning. 

### 3) Baidu Brain Cup (Student Innovation Competition) — Real-time Visual Tracking & Closed-loop Control
- Designed a “perception–decision–actuation” closed-loop system on **Raspberry Pi**.
- Implemented **real-time target detection/tracking** using **OpenCV**, computed target coordinates, and controlled an actuator via a **stepper motor module** to track motion trajectories.
- Integrated embedded hardware wiring, sensor interfaces, motor driving, and system debugging for an end-to-end prototype. 


## Awards {#awards}

- **MCM/ICM 2025 — Meritorious Winner (Problem C)**
- **Baidu Brain Cup Student Innovation Competition — Third Prize** 

## Skills {#skills}

- **NLP / ML:** supervised learning, text modeling, evaluation metrics, error analysis; AES & rubric-aligned feedback generation. 
- **LLM Engineering:** deployment & inference services, API integration, prompt/pipeline design for controllability. 
- **Modeling:** XGBoost, Bayesian Probit + MCMC, fixed effects / lagged regression, SHAP interpretability. 
- **Programming:** Python (data processing, training, reproduction, analysis). 


## CV {#cv}

- **PDF:** [Download CV](files/cv.pdf)  
- **Email:** leojyh123456@gmail.com 


## Contact {#contact}

If you are interested in research collaboration or RA opportunities, feel free to reach out:
- **Email:** leojyh123456@gmail.com 
- **GitHub:** https://github.com/leo1232312
