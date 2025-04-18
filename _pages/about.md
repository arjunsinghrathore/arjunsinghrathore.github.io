---
permalink: /
title: "Hi, I’m Arjun"
excerpt: "Hi, I’m Arjun"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I’m a graduate‑student researcher at NYU interested in **LLMs, Agents, and MultiModal Models**. *Thanks for visiting—feel free to reach out if any of this resonates!*

## 🔭 Current Work

- **Multi‑agent LLM coordination (Advisor: [Dr.&nbsp;Karthik Narsimhan](https://karthikncode.github.io/))**
  * Working at Princeton NLP Group to design **Agent Context Protocols (ACPs)** that execute **Directed Acyclic Graph‑structured** workflows and dynamically equip each **agent** with the right **tool (web search, Python, filesystem, Google APIs, etc)** through **Model Context Protocol (MCP)** servers. Building algorithms to improve agentic workflow construction for multi-agent systems.

- **Dense Vision Spatial Understanding**
  * Fine‑tuning vision encoders such as **DINOv2, CLIP, and SigLIP** with a **language‑guided visual‑grounding** stage to align local image region representations with language captions describing them.
  * Built an **automated dataset generation** pipeline in which **Llama‑Vision‑Instruct** writes region captions and **Segment Anything Model 2** provides masks, producing a large, high‑resolution **region ↔ caption** dataset that strengthens **spatial reasoning in downstream multimodal models**.  

- **Liver Disease Detection with Multimodal Models (Advisor: [Dr.&nbsp;Sumit Chopra](https://www.spchopra.net/#projects))**
  * Collaborating with radiologists at NYU Langone Health to detect liver fibrosis by combining imaging and clinical features by training **MultiModal Models**.
  * Developing an LLM‑driven pipeline that extracts key findings from radiology reports and EHRs, turning a labor‑intensive labeling process into an **automated dataset generation** workflow for multimodal training.

## 🧑‍🔬 Previous Research Experience
- **Serre Lab, Brown University (Advisor: [Dr.&nbsp;Thomas Serre](https://serre-lab.clps.brown.edu/research/))** — Worked on building Neuro‑Inspired Vision Models for Scale-Invariant Object Detection.

## 🚀 What I’m Looking For

**Machine Learning Engineer** or **Research Engineer** roles at fast-paced and growth-oriented environments.


<h2 style="font-size: larger;"><strong>Publications:</strong></h2>
- **Agent Context Protocols Enhance Collective Inference**. Under Review at COLM 2025 (Link Coming Soon)
- **HMAX Strikes Back: Self-supervised Learning of Human-Like Scale Invariant Representations**. (Conference on Cognitive Computational Neuroscience, 2024) (Oral Talk)[Conference Paper Link](https://2024.ccneuro.org/pdf/533_Paper_authored_CCN_2024_HMAX-(2).pdf)
- **Subject Independent Emotion Recognition using EEG Signals Employing Attention Driven Neural Networks**. (Biomedical Signal Processing and Control, 2022) [Journal Link](https://www.sciencedirect.com/science/article/abs/pii/S1746809422000696)
- **Introducing Attention Mechanism for EEG Signals: Emotion Recognition with Vision Transformers**. (IEEE EMBC, 2021) [Conference Paper Link](https://ieeexplore.ieee.org/abstract/document/9629837)
- **CoGraph: Mapping the Structure of the Cognitive Sciences, Neurosciences, & AI**. (Conference on Cognitive Computational Neuroscience, 2022) [Conference Paper Link](https://2022.ccneuro.org/proceedings/0000299.pdf)

<h2 style="font-size: larger;"><strong>Projects:</strong></h2>

- **[Verifiable Rewards — Enforcing Correct Reasoning in LLMs via Reinforcement Learning](https://github.com/arjunsinghrathore/RL_VerifiableRewards)** · *PyTorch, DeepSpeed*  
  Fine‑tuned **Qwen‑7B** with **Group‑Relative Policy Optimization (GRPO)**, using **DeepSpeed** for distributed training and **verifiable reward signals** from a larger teacher (distilled‑DeepSeek‑R1); boosted **MATH** benchmark scores and showed that enforcing correct reasoning improves both performance and generalizability.

- **[Understanding the Effects of RLHF and DPO on LLMs](https://github.com/PranavGrandhi/DPO_RLHF)** · *Hugging Face, Python, HPC*  
  Studied how **Direct Preference Optimization (DPO)** and **RLHF** shape output diversity and generalization by fine‑tuning **Mistral‑7B‑v0.1** for summarization with **LoRA** adapters and **4‑bit** quantization.

- **[Text‑to‑SQL Context‑Aware Query System](https://github.com/AnanyaSSadana/text-to-sql-llm/tree/main)** · *Hugging Face, LangChain, ChromaDB, Python*  
  Built a Text‑to‑SQL pipeline with **Retrieval‑Augmented Generation (RAG)**; applied **PEFT LoRA** fine‑tuning to **Llama2‑7B** on WikiSQL & Spider and delivered an interactive IPEDS interface.

- **[Advanced Music Generation using Language Models](https://github.com/AniketRajpoot/DeepMusicGeneration)** · *PyTorch, Python*  
  Combined **Transformer‑XL** with **VQ‑VAE** for multi‑instrument music generation, achieving near‑lossless 6× audio compression.

- **High‑Performance Vector Similarity Search with CUDA & IVF‑PQ Optimization** · *CUDA, C++*  
  Parallelized IVF‑PQ indexing and fine‑search on GPU, significantly accelerating large‑scale vector search for RAG pipelines.

- **[Content‑Based Music Recommendation System](https://github.com/AnanyaSSadana/music-recommendation-system/tree/main)** · *Kafka, PySpark, Spark SQL, MLlib*  
  Stream‑processed Spotify data with **Kafka** and **PySpark**; used **KMeans** and **PCA** in **MLlib** to recommend songs and visualized results with Streamlit.

- **[Loan Default Prediction System](https://github.com/arjunsinghrathore/Loan-Default-Prediction-System)** · *Kubernetes, Docker, AWS, Python*  
  Deployed an XGBoost‑based loan default predictor on **AWS EKS** with **Docker**, accelerating inference via **daal4py**.
