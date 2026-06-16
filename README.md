# Ryota Okauchi (岡内 亮太) 👋

**Master's student, Civil Engineering @ The University of Tokyo** · ex-AKARI Inc. (PM / Algorithm & Software Engineer)

I take AI out of the lab and into the field. I build **multi-agent systems and LLM/agent pipelines** for real, physical, high-stakes domains — autonomous construction machinery, national infrastructure data, energy markets — and ship them end-to-end, from messy data to production APIs, web apps, and HPC.

---

## 🤖 What I build

**Agentic systems for the physical world — my main focus.**
I'm building [**CAP — Cooperative Agent Protocol**](https://github.com/cooperative-agent-protocol) *(open-sourcing soon)*: a multi-agent platform that lets fleets of autonomous construction machines cooperate on a worksite. An LLM **site agent** decomposes a natural-language goal into work orders (ReAct-style); per-machine **agents** execute them over the CAP protocol (gRPC) on top of **ROS2**, driving a **MuJoCo / operasim physics simulator** before anything touches real equipment. The protocol itself ships as a versioned spec + SDK with a **conformance test suite** and **TLA⁺-checked** state machines. A genuinely new application domain, built to production standards — full-stack **FastAPI + React**, containerized, and deployed on **Kubernetes**.

**Taking ML into real field domains.**
- **Geotechnical risk screening** — calibrated, uncertainty-aware subsurface-property predictions from a **0.5M-record national borehole database**, trained on HPC and served behind an API. *(preprint below)*
- **Infrastructure knowledge graphs** — an LLM + **Graph-RAG** pipeline (JanusGraph · Qdrant) that turns heterogeneous inspection records (PDF, tabular, image) into a queryable knowledge graph, with a web UI on top.
- **Electricity-market forecasting** — the econometric value of weather information for day-ahead markets under high renewable penetration.

I care about the whole path: **real data → honest uncertainty → systems people actually use.**

`agentic & multi-agent AI` · `LLM agents (ReAct · tool-calling)` · `full-stack + cloud-native` · `uncertainty-aware ML` · `formal verification (TLA⁺)`

---

## 📄 Selected work

- **A calibrated regional screening framework for SPT *N*-values from public borehole records under strict spatial cross-validation**
  ![Preprint](https://img.shields.io/badge/Preprint-SSRN-B31B1B?style=flat) · under review at *Computers and Geotechnics*
  R. Okauchi, P.-J. Chun · [SSRN preprint](https://ssrn.com/abstract=6842366)

- **Point-cloud segmentation with synthetic data from virtual environments, and its real-world applicability**
  ![Award](https://img.shields.io/badge/Award-JSCE-F4B400?style=flat) **AI & DX Encouragement Award** (AI・DX奨励賞) · *AI・データサイエンス論文集*, Vol. 6(2), pp. 51–61, 2025
  R. Okauchi, P.-J. Chun · 仮想環境を利用した点群セグメンテーションモデルの作成と実環境適用性の評価 · [DOI](https://doi.org/10.11532/jsceiii.6.2_51)

---

## 🛠️ Stack

**GenAI & Agents**

![Claude](https://img.shields.io/badge/Claude-D97757?style=flat&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat&logo=qdrant&logoColor=white)
&nbsp;+ ReAct agents · multi-agent coordination · Graph-RAG · LoRA/DPO fine-tuning

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
&nbsp;+ operasim · gRPC

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

---

<sub>AI that leaves the lab and runs in the real world.</sub>
