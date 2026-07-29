<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:6a00ff,100:00fff7&height=190&section=header&text=Somesh%20R%20Bhandarkar&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20Engineer%20%7C%20Machine%20Learning%20Engineer%20%7C%20GenAI%20%2B%20MLOps&descAlignY=58&descAlign=50" width="100%"/>

<a href="https://git.io/typing-svg">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=900&color=39FF14&center=true&vCenter=true&width=750&lines=AI+Engineer+%7C+Machine+Learning+Engineer;Building+production+GenAI+%2B+ML+systems+that+ship;Latent+Diffusion+%7C+RAG+%7C+LLMOps;Currently%3A+ML+Engineer+%40+University+at+Buffalo;Open+to+AI+Engineer+%2F+ML+Engineer+roles" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-someshrb7-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/someshrb7)
[![Instagram](https://img.shields.io/badge/Instagram-someshrb7-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/someshrb7/)
[![Profile Views](https://komarev.com/ghpvc/?username=SomeshBhandarkar&style=for-the-badge&color=9D00FF&label=PROFILE+VIEWS)](https://github.com/SomeshBhandarkar)

</div>

<br/>

## 🧠 About Me

I'm a Master's student in Data Science at the **University at Buffalo**, working as an **AI / Machine Learning Engineer** building generative AI pipelines for medical imaging. I work across the full stack of modern AI engineering — training and fine-tuning models, building LLM/RAG applications, and shipping both into production.

- 🤖 **AI Engineer side:** building RAG pipelines, LLM-powered applications, and agentic systems (LangChain, LangGraph, FAISS, GPT-4, Claude, Gemini) — from prompt design to production API
- 🔬 **ML Engineer side:** training **latent diffusion models** (PathLDM, HistoDiffusion) for synthetic histopathology generation on H100 / A100 clusters, plus classic CV/ML (YOLOv8, Random Forest)
- 🛠️ Comfortable end-to-end: data pipelines → model training → containerization (Docker) → deployment (AWS SageMaker, GCP) → experiment tracking (MLflow)
- 🎯 Open to **AI Engineer / Machine Learning Engineer / Applied Scientist** roles
- ⚡ Fun fact: national-level football player

<br/>

## 💼 Experience

<table>
<tr>
<td width="190" valign="top"><b>Sep 2025 – Present</b></td>
<td>
<b>Machine Learning Engineer</b> <sub>(AI Engineering + GenAI)</sub> · University at Buffalo<br/>
<sub>
• Cut image preprocessing time 75% (2 hrs → 30 min) by engineering a Python pipeline that standardized 200–300 patches/slide across 1,000+ whole-slide histopathology images (150GB)<br/>
• Hit FID 3.5 and 85% classification accuracy on synthetic liver histopathology by training PathLDM &amp; HistoDiffusion latent diffusion models in PyTorch across 5 runs on H100/A100 GPUs<br/>
• Tripled the training dataset (1K → 3K samples) and fixed class imbalance via a GPT-4 + Gemini synthetic data pipeline generating 2,000+ rare tumorous liver samples<br/>
• Deployed real-time inference on AWS SageMaker at 1,000ms latency, containerized with Docker, with experiment tracking centralized in MLflow across 5 runs
</sub>
</td>
</tr>
<tr>
<td width="190" valign="top"><b>Jul 2022 – Jun 2024</b></td>
<td>
<b>Software Engineer</b> <sub>(Machine Learning)</sub> · Delta India<br/>
<sub>
• Increased client ARR 25% by cutting monthly customer churn 15% via a production TensorFlow + Scikit-learn model on AWS SageMaker, serving 25,000+ daily requests at &lt;250ms latency<br/>
• Shortened model update cycle from 2 weeks to 4 days by building an Airflow-orchestrated, MLflow-versioned retraining pipeline on S3 and Redshift<br/>
• Prevented a 12-point production accuracy drop by deploying real-time model monitoring (Evidently AI + Weights &amp; Biases) across 2 live models, catching upstream feature drift 2 days early<br/>
• Cut nightly batch inference runtime 50% (3.5h → 1.7h) on 1.5M daily records by redesigning the Spark job on AWS EMR for better parallelism
</sub>
</td>
</tr>
<tr>
<td width="190" valign="top"><b>Jan 2022 – Jun 2022</b></td>
<td>
<b>Software Engineer Intern</b> <sub>(Machine Learning)</sub> · Delta India<br/>
<sub>
• Improved support ticket classification F1-score from 74% to 85% by fine-tuning DistilBERT in PyTorch on 150,000 samples across 6 imbalanced categories<br/>
• Eliminated 3 hrs/week of manual data prep by scheduling a daily Scikit-learn + Airflow pipeline from Redshift into training-ready features<br/>
• Reduced model selection time from 3 days to 4 hours by standardizing 20+ experiment runs (Random Forest, XGBoost, Logistic Regression) in a single MLflow registry<br/>
• Cut environment setup time from 4 hrs to 30 min across 3 machines by containerizing training scripts in Docker with pinned dependencies
</sub>
</td>
</tr>
</table>

<br/>

## 🚀 Featured Projects

### 🔐 [ClauseIQ](https://github.com/SomeshBhandarkar/ClauseIQ)
`Python` `FastAPI` `RAG` `LangChain` `FAISS` `Sentence-Transformers` `Claude API`

Cuts contract review from hours to under 60 seconds — a RAG pipeline (FAISS + Sentence Transformers + Claude) that flags 25 risky clause types from any uploaded PDF and returns plain-English, confidence-scored risk reports. Hallucination risk engineered out via semantic chunking and grounded prompting.

### 🧘 [MindMate — AI-Powered Mental Health App](https://github.com/SomeshBhandarkar/MindMate---A-health-screening-app)
`Python` `LangChain` `OpenAI` `FastAPI` `React` `Vercel`

Sub-2-second-latency RAG pipeline (LangChain + OpenAI embeddings + FAISS) grounded in a curated clinical knowledge base, serving context-aware mental health support through a FastAPI + React app deployed live on Vercel.

### 🏗️ [DeepDetect — Damage Detection Platform](https://github.com/SomeshBhandarkar/DeepDetect---FrontEnd)
`PyTorch` `YOLOv8` `Computer Vision` `PostgreSQL` `React` `FastAPI`

Real-time structural crack and building-damage detection at 0.78 mAP using a YOLOv8-nano model with iterative dataset refinement, served via a FastAPI + React REST API with full prediction-metadata storage for continuous retraining.

### 💰 [LoanSure — Loan Approval System](https://github.com/SomeshBhandarkar/LoanSure---A-loan-approval-system)
`Python` `Scikit-learn` `MLflow` `DagsHub` `Docker` `GCP` `Streamlit`

82% test-accuracy loan-approval classifier (Random Forest) with fully reproducible experiment tracking via MLflow + DagsHub, containerized and deployed as a Streamlit + FastAPI app on GCP for zero-touch real-time inference.

<br/>

## 🧰 Tech Arsenal

**Machine Learning & AI**

![Python](https://img.shields.io/badge/-Python-39FF14?style=for-the-badge&logo=python&logoColor=black)
![PyTorch](https://img.shields.io/badge/-PyTorch-39FF14?style=for-the-badge&logo=pytorch&logoColor=black)
![scikit-learn](https://img.shields.io/badge/-scikit--learn-39FF14?style=for-the-badge&logo=scikitlearn&logoColor=black)
![HuggingFace](https://img.shields.io/badge/-Hugging%20Face-39FF14?style=for-the-badge&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/-LangChain-39FF14?style=for-the-badge&logo=langchain&logoColor=black)
![OpenAI](https://img.shields.io/badge/-OpenAI%20%7C%20Claude%20%7C%20Gemini-39FF14?style=for-the-badge&logo=openai&logoColor=black)

**MLOps & Deployment**

![Docker](https://img.shields.io/badge/-Docker-00E5FF?style=for-the-badge&logo=docker&logoColor=black)
![MLflow](https://img.shields.io/badge/-MLflow-00E5FF?style=for-the-badge&logo=mlflow&logoColor=black)
![FastAPI](https://img.shields.io/badge/-FastAPI-00E5FF?style=for-the-badge&logo=fastapi&logoColor=black)
![Airflow](https://img.shields.io/badge/-Apache%20Airflow-00E5FF?style=for-the-badge&logo=apacheairflow&logoColor=black)
![DagsHub](https://img.shields.io/badge/-DagsHub-00E5FF?style=for-the-badge&logo=dagshub&logoColor=black)
![CI/CD](https://img.shields.io/badge/-CI%2FCD-00E5FF?style=for-the-badge&logo=githubactions&logoColor=black)

**Cloud Platforms**

![AWS](https://img.shields.io/badge/-AWS%20SageMaker%20%7C%20S3%20%7C%20Lambda%20%7C%20EMR-FF2BD1?style=for-the-badge&logo=amazonaws&logoColor=black)
![Azure](https://img.shields.io/badge/-Azure%20ADLS%20%7C%20Synapse-FF2BD1?style=for-the-badge&logo=microsoftazure&logoColor=black)
![GCP](https://img.shields.io/badge/-Google%20Cloud-FF2BD1?style=for-the-badge&logo=googlecloud&logoColor=black)

**Data Engineering, Languages & Tools**

![SQL](https://img.shields.io/badge/-SQL-FF9F1C?style=for-the-badge&logo=postgresql&logoColor=black)
![MySQL](https://img.shields.io/badge/-MySQL-FF9F1C?style=for-the-badge&logo=mysql&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-FF9F1C?style=for-the-badge&logo=postgresql&logoColor=black)
![MongoDB](https://img.shields.io/badge/-MongoDB-FF9F1C?style=for-the-badge&logo=mongodb&logoColor=black)
![Snowflake](https://img.shields.io/badge/-Snowflake-FF9F1C?style=for-the-badge&logo=snowflake&logoColor=black)
![Spark](https://img.shields.io/badge/-Apache%20Spark-FF9F1C?style=for-the-badge&logo=apachespark&logoColor=black)
![JavaScript](https://img.shields.io/badge/-JavaScript-FF9F1C?style=for-the-badge&logo=javascript&logoColor=black)
![Git](https://img.shields.io/badge/-Git%20%2F%20GitHub-FF9F1C?style=for-the-badge&logo=github&logoColor=black)
![PowerBI](https://img.shields.io/badge/-Power%20BI-FF9F1C?style=for-the-badge&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/-Tableau-FF9F1C?style=for-the-badge&logo=tableau&logoColor=black)

<br/>

## 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=SomeshBhandarkar&show_icons=true&theme=radical&hide_border=true&include_all_commits=true&count_private=true" width="48%"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=SomeshBhandarkar&theme=radical&hide_border=true" width="48%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SomeshBhandarkar&layout=compact&theme=radical&hide_border=true" width="40%"/>
<img src="https://github-readme-activity-graph.vercel.app/graph?username=SomeshBhandarkar&theme=react-dark&hide_border=true" width="56%"/>

<img src="https://github-profile-trophy.vercel.app/?username=SomeshBhandarkar&theme=radical&no-frame=true&row=1&column=7"/>

</div>

<br/>

## 🐍 Contribution Snake

<div align="center">
<img src="https://raw.githubusercontent.com/SomeshBhandarkar/SomeshBhandarkar/output/github-contribution-grid-snake-dark.svg" />
</div>

<br/>

<div align="center">

### 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/someshrb7)
[![Instagram](https://img.shields.io/badge/Instagram-Follow-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/someshrb7/)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00fff7,100:0d1117&height=100&section=footer" width="100%"/>

</div>
