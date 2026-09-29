<div align="center">

<a href="https://github.com/WickDager">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1200&color=36BCF7&center=true&vCenter=true&width=720&lines=Hi+%F0%9F%91%8B+I'm+Amos+Masarira;Data+Scientist+%C2%B7+ML+Engineer;From+oil+%26+gas+engineering+to+machine+learning" alt="Typing SVG" />
</a>

**🛢️ BSc Oil & Gas Engineering &nbsp;→&nbsp; 📊 MSc Informatics & Computer Science (Data Science), NUST MISIS**

<a href="mailto:masariraa2006@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://github.com/WickDager?tab=repositories"><img src="https://img.shields.io/badge/Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositories" /></a>

*"Turning caffeine, deadlines, and questionable ideas into working systems."*

</div>

---

## 🧠 About

I'm a **data scientist** with a background in **oil & gas engineering**. I build ML systems end to end, from anomaly detection on pump sensor data and recommender-systems research to LLM-powered workflows and full-stack products, and I care about evaluation that holds up: like-for-like comparisons, significance tests, and honest uncertainty.

| | |
|---|---|
| 🔭 **Recently** | A multi-agent sentiment analysis benchmark · an AI-assisted pharmacy operations platform |
| 🌱 **Learning** | Transformer architectures · multi-agent LLM systems |
| 💬 **Ask me about** | Predictive maintenance · recommender systems · NLP & sentiment · ML deployment |

---

## 🛠️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=py,pytorch,sklearn,pandas,numpy,django,react,nextjs,ts,vite,tailwind,supabase,postgres,redis,docker,githubactions,cpp,git&perline=9" alt="Tech stack icons" />

</div>

| Area | Tools |
|---|---|
| **ML & Data** | `PyTorch` `scikit-learn` `LightGBM` `XGBoost` `SHAP` `Keras` `Hugging Face Transformers` `Pandas` `NumPy` `Jupyter` |
| **Methods** | Anomaly detection · survival analysis · recommender systems (iALS, EASE^R, LightFM) · time-series · uncertainty quantification |
| **Data & Workflow** | `Hadoop / YARN` `n8n` `Docker` `GitHub Actions` `pytest` |
| **Backend** | `Python` `Django` `DRF` `Celery` `Redis` `PostgreSQL` `Supabase` `Deno` |
| **Frontend** | `React` `Next.js` `TypeScript` `Vite` `Tailwind CSS` |

---

## 🚀 Featured Projects

### 🔬 Research & Machine Learning

| Project | What it does | Stack |
|---|---|---|
| [**From Single Models to Multi-Agent Systems**](https://github.com/WickDager/single-to-multi-agent-sentiment) | Benchmarks 8 single-model sentiment classifiers against a multi-agent system (sentiment + sarcasm + aspect agents). On the same 1,000 reviews the 3-agent setup scores 0.952 F1 vs 0.944 for RoBERTa, at about 8× the CPU latency. Includes the evaluation caveats up front. | `Transformers` `PyTorch` `Keras` `scikit-learn` |
| [**Impact of Content Embeddings on Recommendations**](https://github.com/WickDager/impact-of-content-embeddings-on-recommendations) | Sensitivity analysis of collaborative filtering (iALS, EASE^R, LightFM) on the VK-LSVD dataset. Content embeddings beat pure CF in every hybrid setup (8 of 9 gains significant at p < 0.05); best result is iALS + concat at d=64, with diminishing returns around d=32. | `implicit ALS` `LightFM` `Python` |
| [**ESP Predictive Maintenance**](https://github.com/WickDager/esp-predictive-maintenance) | Failure prediction for Electric Submersible Pumps: LSTM and Transformer autoencoders for anomaly detection, Bi-LSTM RUL regression, XGBoost + SHAP for failure classification, Cox PH / Weibull AFT survival analysis, and Monte Carlo Dropout uncertainty. AUC-ROC ≈ 0.94–0.96 on the Kaggle pump sensor data. | `PyTorch` `XGBoost` `SHAP` |
| [**Gender Prediction for Targeted Advertising**](https://github.com/WickDager/gender-prediction-advertising) | Built for a VK competition on All Cups: request logs to per-user features (user agent, geo, referer embeddings) to a LightGBM classifier. **82.3% accuracy, 0.817 F1** on a 100K-user hold-out set. | `LightGBM` `Pandas` `scikit-learn` |

### 🌐 Full-Stack Products

| Project | What it does | Stack |
|---|---|---|
| [**Trivaro: Prop Trading Firm**](https://github.com/WickDager/trivaro-prop-trading-firm) | Prop trading platform where traders buy challenges, prove themselves in a simulated MT5 environment, and get funded. A Python MT5 bridge streams equity snapshots and trades into Supabase edge functions, and a Deno Telegram bot handles payment intake, with USDT, USDC and BTC payments verified on-chain. Turborepo monorepo. | `Next.js 16` `React 19` `Supabase` `Deno` `Python` `Turborepo` |
| [**HabitFlow**](https://github.com/WickDager/habitflow) | Telegram Mini App for tracking daily habits in under 10 seconds. Custom JWT minted from Telegram init data and validated with HMAC, Supabase row-level security on every query, optimistic updates, an IndexedDB offline check-in queue, Redis rate limiting, and English/Russian support. | `Next.js 16` `Supabase` `Upstash Redis` `Telegram WebApp API` |

### ⚙️ Applied Engineering

| Project | What it does | Stack |
|---|---|---|
| [**HDAOS: Health Dispensary Analytical Ordering System**](https://github.com/WickDager/health-dispensary-analytical-ordering-system) | Pharmacy operations platform: LLM-based extraction of supplier invoices into reviewable line items, FEFO batch inventory, procurement suggestions, CRM, approval workflows, RBAC, and audit trail. Works with multiple LLM providers. | `Django` `DRF` `Celery` `React` `TypeScript` |
| [**AI Lead Enrichment & Approval**](https://github.com/WickDager/ai-lead-enrichment-approval) | n8n workflow that enriches new leads, scores them with OpenAI, asks for human approval through Slack buttons, then syncs approved leads to Google Sheets and a CRM. Python helpers are unit-tested and run in CI. | `n8n` `Python` `OpenAI` `Slack` |
| [**Hadoop WordCount Container**](https://github.com/WickDager/hadoop-wordcount-container) | Docker client that runs a streaming MapReduce WordCount on an external Hadoop 3.3.6 cluster through YARN. | `Hadoop` `Docker` `Python` |
| [**Gold Pattern Trader**](https://github.com/WickDager/gold-pattern-trader) | XAUUSD trading bot: a Sierra Chart ACSIL study exports 1-minute data, and a Python MT5 trader handles pattern invalidation and delta divergence. | `Python` `C++` `MetaTrader 5` |

---

## 🏆 Highlights

- 🧠 **Domain expertise:** oil & gas engineering plus data science, so I understand the physical systems behind the data.
- 📏 **Rigorous evaluation:** significance testing, like-for-like comparisons, and Monte Carlo Dropout uncertainty instead of single headline numbers.
- 🥇 **Competitive ML:** built the top-ranked model among all participants in the VK Summer Internship Programme.
- 🤖 **Applied LLM systems:** document extraction with human-in-the-loop approval, multi-provider model support, and AI-scored workflows.
- 🚢 **Notebook to production:** tests, CI, and Docker around the models, not just the experiments.
- 🔐 **Production-minded full-stack:** HMAC/JWT auth with row-level security, on-chain payment verification, and real-time trade monitoring.

---

## 📊 GitHub Activity

<div align="center">

<img src="https://raw.githubusercontent.com/WickDager/WickDager/main/profile-summary-card-output/dracula/0-profile-details.svg" width="49%" alt="Profile details" />
<img src="https://raw.githubusercontent.com/WickDager/WickDager/main/profile-summary-card-output/dracula/3-stats.svg" width="49%" alt="GitHub stats" />

<img src="https://raw.githubusercontent.com/WickDager/WickDager/main/profile-summary-card-output/dracula/2-most-commit-language.svg" width="32%" alt="Most used languages" />
<img src="https://raw.githubusercontent.com/WickDager/WickDager/main/profile-summary-card-output/dracula/1-repos-per-language.svg" width="32%" alt="Repos per language" />
<img src="https://raw.githubusercontent.com/WickDager/WickDager/main/profile-summary-card-output/dracula/4-productive-time.svg" width="32%" alt="Productive time of day" />

<img src="https://raw.githubusercontent.com/WickDager/WickDager/main/profile-3d-contrib/profile-night-rainbow.svg" alt="3D contribution skyline" width="95%" />

</div>

---

<div align="center">

## 📫 Let's Connect

<a href="mailto:masariraa2006@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

Open to internships, collaborations, and interesting ML problems.

</div>
