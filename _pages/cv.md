---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
- **M.S. in Artificial Intelligence**, Royal Holloway, University of London, UK  
  *Sep 2023 – Sep 2025*

- **B.S. in Computer Science and Information Engineering**,  
  National Chin-Yi University of Technology, Taiwan  
  *Sep 2014 – Jun 2018*

Work experience
======
- **Medical AI Researcher**, China Medical University Hsinchu Hospital, Taiwan  
  *Dec 2025 – Present*  
  - Conducted systematic research on hidden data leakage in OCT-based medical AI  
  - Identified patient-level leakage as a key source of performance inflation  
  - Designed leakage-aware evaluation framework to improve real-world generalization  
  - Performed statistical validation (bootstrap, FDR correction) for robust conclusions  

- **AI Research Intern**, BIIC Lab, National Tsing Hua University  
  *Jul 2020 – Jul 2021*  
  - Developed end-to-end computer vision pipeline for mango quality grading  
  - Managed large-scale dataset (80,000+ images) with automated preprocessing  
  - Deployed real-time model achieving improved accuracy and reduced labor cost  
  - Built monitoring system for model drift and inference performance  
  
Projects
======
- **AI Medical Imaging System with LLM-Augmented Reporting (oct-api)**  
  *Feb 2026 – Apr 2026*  
  - Built a production-ready OCT classification system with FastAPI and Docker  
  - Integrated LLM-based report generation with fallback safety mechanisms  
  - Implemented data drift monitoring and real-time inference APIs  

- **Leakage-Aware Evaluation Framework for Medical Imaging AI (oct-leakage)**  
  *Jan 2026 – Mar 2026*  
  - Developed framework to detect and mitigate hidden data leakage  
  - Designed patient-level data splitting strategy (GroupKFold)  
  - Conducted statistical evaluation to quantify performance inflation  

- **Instruction-Tuned Bilingual LLM**  
  *Jul 2025 – Aug 2025*  
  - Fine-tuned LLaMA and Qwen models using QLoRA  
  - Improved BLEU and ROUGE scores for bilingual customer support  

- **Mango Quality Detection System (YOLO-based)**  
  *Jun 2020 – Jul 2021*  
  - Built real-time object detection(YOLO-V5) system for industrial deployment  
  - Achieved high accuracy and real-time performance(30+ FPS) for sorting pipeline  

Skills
======
- **Programming:** Python, C++, SQL  
- **Machine Learning & AI:** PyTorch, TensorFlow, Scikit-learn, XGBoost  
- **Computer Vision:** Image classification, object detection, medical imaging  
- **LLM & Generative AI:** LLaMA, Qwen, HuggingFace, Prompt Engineering  
- **Tools & Systems:** Docker, FastAPI, Git, Linux, Postgres, MongoDB, MLOps  


<!-- Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->
  
<!-- Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
<!--   
Service and leadership
======
* Currently signed in to 43 different slack teams -->
