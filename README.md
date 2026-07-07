# Ryota Okauchi (岡内 亮太)

**Master's student, Civil Engineering, The University of Tokyo.** Previously PM / algorithm & software engineer at AKARI Inc.

I work on **multi-agent systems and applied ML** for civil and infrastructure problems — autonomous construction machinery, geotechnical data, energy markets — and build the full stack that runs them, from data pipelines to APIs and web apps.

---

## 🤖 What I build

**Multi-agent systems for autonomous construction machinery — my main focus.**
I'm building [**CAP — Cooperative Agent Protocol**](https://github.com/cooperative-agent-protocol) *(open-sourcing soon)*: the protocol that lets fleets of autonomous construction machines coordinate on a worksite — doing for machines what the spoken call-outs of a human crew do, keeping everyone in sync and clear of each other. A **site agent** (ReAct loop) breaks a natural-language goal into work orders; **machine agents** (also ReAct loops) carry them out; and **CAP** is what they coordinate over — work orders, reservations, and hand-offs — defined as a versioned spec + SDK (gRPC) with a **conformance test suite** and **TLA⁺-checked** state machines. The whole thing runs in a physics simulator before it touches real equipment.

**Applied ML on real-world data.**
- **Geotechnical risk screening** — calibrated, uncertainty-aware subsurface-property predictions from a **0.5M-record national borehole database**, trained on HPC and served behind an API. *(preprint below)*
- **Infrastructure knowledge graphs** — an LLM + **Graph-RAG** pipeline (JanusGraph · Qdrant) that turns heterogeneous inspection records (PDF, tabular, image) into a queryable knowledge graph, with a web UI on top.
- **Electricity-market forecasting** — the econometric value of weather information for day-ahead markets under high renewable penetration.

I work across the whole pipeline — from data and models to the software that serves them.

`agentic & multi-agent AI` · `LLM agents (ReAct · tool-calling)` · `full-stack + cloud-native` · `uncertainty-aware ML` · `formal verification (TLA⁺)`

---

## 📄 Selected work

- **A calibrated regional screening framework for SPT *N*-values from public borehole records under strict spatial cross-validation**
  ![Preprint](https://img.shields.io/badge/Preprint-SSRN-B31B1B?style=flat) · under review at *Computers and Geotechnics*
  R. Okauchi, P.-J. Chun · [SSRN preprint](https://ssrn.com/abstract=6842366)

- **Forecast-Skill Scarcity, Price Floors, and the Value of Weather Information in Solar-Saturated Electricity Markets**
  ![Preprint](https://img.shields.io/badge/Preprint-SSRN-B31B1B?style=flat)
  R. Okauchi, P.-J. Chun · [SSRN preprint](https://ssrn.com/abstract=7067947)

- **Point-cloud segmentation with synthetic data from virtual environments, and its real-world applicability**
  ![Award](https://img.shields.io/badge/Award-JSCE-F4B400?style=flat) **AI & DX Encouragement Award** (AI・DX奨励賞) · *AI・データサイエンス論文集*, Vol. 6(2), pp. 51–61, 2025
  R. Okauchi, P.-J. Chun · 仮想環境を利用した点群セグメンテーションモデルの作成と実環境適用性の評価 · [DOI](https://doi.org/10.11532/jsceiii.6.2_51)

---

## 🛠️ Stack

**GenAI & Agents**

`multi-agent systems` · `ReAct agents · tool-calling` · `Graph-RAG` · `LoRA / DPO fine-tuning`

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat&logo=latex&logoColor=white)

**ML & Data**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![Polars](https://img.shields.io/badge/Polars-CD792C?style=flat&logo=polars&logoColor=white)
![GPyTorch](https://img.shields.io/badge/GPyTorch-792EE5?style=flat)
![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?style=flat)

**Web & API**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

**Robotics & Sim**

![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=flat&logo=ros&logoColor=white)
![MuJoCo](https://img.shields.io/badge/MuJoCo-2E7D32?style=flat)

**Cloud & Infra**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
&nbsp;+ HPC (SLURM / PBS · Apptainer)

Also: `TLA⁺` for formal specification & model checking, `Hydra`, `uv`, `Ruff`, `pytest`.

---

## 📫 Reach me

- 📧 **Email** — ryoutaokauchi@g.ecc.u-tokyo.ac.jp
- 🎓 **Google Scholar** — https://scholar.google.com/citations?user=weZg1LMAAAAJ
- 🔬 **researchmap** — https://researchmap.jp/r-okauchi
- 🆔 **ORCID** — https://orcid.org/0009-0001-5391-7133
- 💼 **LinkedIn** — https://www.linkedin.com/in/ryota-okauchi-65625a401
