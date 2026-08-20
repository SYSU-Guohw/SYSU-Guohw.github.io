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
* M.S. in Beijing, Peking University, 2026 (incoming)
* B.S. in Shenzhen, Sun Yat-sen University, 2022


Honors and Awards
======
* **Outstanding Graduate of Sun Yat-sen University** (June 2026)
* **National Scholarship** (2023-2024 Academic Year)
* **First-Class Excellent Student Scholarship** (SYSU, 2022-2025, Every Academic Year)
* **China Robot Competition & RoboCup China Open:** National Third Prize (Team Leader)
* **National College Students' Mathematical Modeling Contest (Guangdong):** Provincial Third Prize
  
Internship
======
* **Research Intern**, Meituan, M17 Team (2025.11 – 2026.7)

Research & Industry Experience
======

### 1. Meituan LongCat-Next Unified Foundation Model
* **Role:** Research Intern  **Nov. 2025 – Jun. 2026**
* **Summary:** Worked on pre-training data construction and model training for **LongCat-Next Unified Foundation Model**, based on a unified discrete-token (**Discrete Native Autoregressive**) architecture. Contributed to multimodal understanding, generation, and interleaved image-text generation.
* **Contributions:** Built scalable pipelines for **Caption image-text data, Knowledge-rich Entity data, UI Agent Caption & Grounding data, and interleaved image-text trajectory data**. Expanded the Caption dataset to **85M image-text pairs** and implemented automated pipelines for large-scale data production and quality validation. Also contributed to model pre-training, trajectory filtering, and data quality control.
* **Publication:** Co-authored *LongCat-Next: Lexicalizing Modalities as Discrete Tokens*.

### 2. When Should the Teacher Move? Temporal Coupling and Stability in Self On-Policy Distillation
* **Summary:** Systematically studies how teacher update schedules affect long-horizon stability in Self On-Policy Distillation. Identifies reference collapse and teacher contamination under different update mechanisms, and proposes **Consolidation-Gated Teacher Refresh (CGTR)**, a state-aware teacher refresh strategy that preserves isolation periods while preventing unstable student snapshots from being copied to the teacher. CGTR achieves **zero collapse across four tasks** with a single shared parameter set.
* **Status:** **First Author; Under Review at EMNLP 2026 (Long Paper)**.

### 3. MCPHallu: Benchmarking Reasoning, Execution, and Memory Hallucinations in MCP Agents
* **Summary:** Introduced **MCPHallu**, a benchmark for diagnosing hallucination failures in LLM agents operating under the Model Context Protocol (MCP). The benchmark covers **358 tasks across five domains** and evaluates four failure types: Branch Collapse, Unreachable Goal, Tool Misuse, and Context Forgetting. Experiments on **14 frontier LLMs and nearly 5,000 execution trajectories** reveal fine-grained reliability issues beyond overall task success rate.
* **Status:** **Co-first Author; Under Review at NeurIPS 2026 E&D Track**.

### 4. Unified Medical Image Segmentation with State Space Modeling Snake
* **Summary:** Proposed **Mamba Snake**, a deep snake algorithm based on State Space Modeling (SSM) to address multi-scale structural heterogeneity in Unified Medical Image Segmentation (UMIS). Introduced a Mamba Evolution Block for spatiotemporal information aggregation and a dual-classification collaborative mechanism for improving micro-structure segmentation. Achieved a **3% mDice improvement** over SOTA methods across five clinical datasets.
* **Status:** **Second Author; Accepted at ACM MM 2025 (CCF-A, Oral)**.

### 5. GAMED-Snake: Gradient-aware Adaptive Momentum Evolution Deep Snake Model for Multi-organ Segmentation
* **Summary:** Introduced **GAMED-Snake**, a deep snake architecture that combines gradient-aware differential convolution, a Distance Energy Map Prior (DEMP), and cross-attention to model dynamic features across adjacent iterations. The proposed approach improves semantic segmentation by alleviating misclassification and mask-hole problems, achieving an approximately **2% improvement in mDice**.
* **Status:** **Co-first Author; Accepted at ICME 2025 (CCF-B)**.

### 6. TEAMS: Text-prompted spatiotEmporal dual-heAd Mamba Snake
* **Summary:** Proposed the first **multimodal state-space deep snake framework** for medical image segmentation. TEAMS integrates a Spatiotemporal Snake Evolution Strategy (SSES), Contour Morphology-Aware Module (CMAM), and Text-driven Collaborative Dual-Head Snake (TCDHS) mechanism to improve segmentation of complex anatomical structures and enhance cross-modal generalization.
* **Status:** **Third Author; Accepted at Medical Image Analysis (IF=14.0)**.
