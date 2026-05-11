# 🦾 vla_paper_tracker

This repository tracks and organizes cutting-edge research papers on **Vision-Language-Action (VLA)** models and general-purpose robotic foundation models.

It focuses on the emerging paradigm of training robots with large-scale multimodal data using:
- **Vision-Language Models (VLMs)**
- **Action Generation / Diffusion Policies**
- **Flow Matching & Sequence Modeling**
- **Cross-Embodiment Learning**
- **Robot Foundation Models**
- **Generalist Robot Policies**

The goal is to maintain a structured and regularly updated reading list for researchers, students, and practitioners working on embodied AI, robotics foundation models, and VLA systems.

---

# 📚 Paper Collection

## 🦾 Vision-Language-Action Models

| Date | Title | Authors | Venue | Notes |
|---|---|---|---|---|
| 2024-10-09 | [Fine-Tuning Vision-Language-Action Models: Optimizing Speed and Success](https://arxiv.org/abs/2502.19645) | Kim et al. | ArXiv 2025 | Studies different fine-tuning strategies for OpenVLA |
| 2025-02-24 | [π0.5: a Vision-Language-Action Model with Open-World Generalization](https://www.physicalintelligence.company/download/pi05.pdf) | Physical Intelligence et al. | PI Blog / Technical Report 2025 | Improved generalization and robustness over π0 |
| 2024-10-09 | [π0: A Vision-Language-Action Flow Model for General Robot Control](https://www.physicalintelligence.company/download/pi0.pdf) | Physical Intelligence et al. | ArXiv 2024 | Introduces flow matching for action generation |
| 2024-06-11 | [OpenVLA: An Open-Source Vision-Language-Action Model](https://arxiv.org/pdf/2406.09246) | Kim et al. | ArXiv 2024 | Open-source VLA trained on Open X-Embodiment |
| 2024-12-01 | [RoboMamba: Efficient Vision-Language-Action Modeling](https://arxiv.org/) | TBA | ArXiv 2024 | TBA |
| 2024-07-01 | [Octo: An Open-Source Generalist Robot Policy](https://arxiv.org/pdf/2405.12213) | Octo Model Team | RSS 2024 | Open-source multi-robot policy |
| 2024-03-28 | [RT-H: Action Hierarchies Using Language](https://robotics-transformer-x.github.io/assets/rt_h.pdf) | Brohan et al. | Robotics: Science and Systems (RSS) 2024 | Hierarchical robot control with language grounding |
| 2024-03-13 | [Open X-Embodiment: Robotic Learning Datasets and RT-X Models](https://arxiv.org/pdf/2310.08864) | Open X-Embodiment Collaboration | ICRA 2024 | Large-scale cross-embodiment dataset |
| 2023-12-13 | [RoboFlamingo: Vision-Language-Action Models for Robot Manipulation](https://arxiv.org/pdf/2312.01378) | Li et al. | ArXiv 2023 | Adapts Flamingo-style architectures to robotics |
| 2023-07-28 | [RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control](https://arxiv.org/pdf/2307.15818) | Brohan et al. | CoRL 2023 | Landmark VLA work extending VLMs to robot actions |
| 2023-07-28 | [RT-1: Robotics Transformer for Real-World Control at Scale](https://arxiv.org/pdf/2212.06817) | Brohan et al. | RSS 2023 | Scalable transformer-based robot policy |
---


---

## ⚙️ Action Generation & Policy Learning

| Date | Title | Authors | Venue | Notes |
|---|---|---|---|---|
| 2023-03-21 | [Diffusion Policy: Visuomotor Policy Learning via Action Diffusion](https://arxiv.org/pdf/2303.04137) | Chi et al. | RSS 2023 | Foundational diffusion-based robot policy |
| 2022-11-16 | [Decision Transformer: Reinforcement Learning via Sequence Modeling](https://arxiv.org/pdf/2106.01345) | Chen et al. | NeurIPS 2021 | Sequence modeling approach to control |
| 2021-06-17 | [Behavior Transformers: Cloning k Modes with Transformer-Based Policies](https://arxiv.org/pdf/2206.11251) | Shafiullah et al. | CoRL 2022 | Multimodal action prediction |
| 2021-05-26 | [Perceiver IO](https://arxiv.org/pdf/2107.14795) | Jaegle et al. | ICML 2021 | Important architecture for multimodal robotics |

---

# 🗂️ Suggested Reading Order

If you're new to VLA systems, a useful progression is:

1. **RT-1** → scalable robot transformers  
2. **RT-2** → adding web-scale VLM knowledge  
3. **Open X-Embodiment** → multi-robot datasets  
4. **OpenVLA** → open-source reproduction of VLA ideas  
5. **π0 / π0.5** → flow matching and modern action generation  

---

# 🔬 Important Research Directions

Current open problems in VLA research include:

- Cross-robot generalization
- Long-horizon planning
- Real-time action chunking
- Flow matching vs autoregressive control
- Robot data scaling laws
- Embodiment transfer
- Safety and reliability
- World models for robotics
- Test-time adaptation
- Sim-to-real transfer

---

# 🧩 How to Use

- Papers are grouped by research direction.
- Tables are sorted chronologically.
- The **Notes** column can be used for:
  - Key insights
  - Reproduction notes
  - Open questions
  - Implementation details
  - Interview preparation

Example note ideas:
- “Uses flow matching instead of diffusion”
- “Action chunk size = 50”
- “Trained on Open X-Embodiment”
- “Uses VLM backbone + action expert”

---

# 📌 Planned Additions

Future sections may include:

- World Models for Robotics
- Diffusion & Flow Matching Policies
- Embodied Chain-of-Thought
- Vision-Language Navigation
- Manipulation Benchmarks
- Robot Data Scaling Laws
- Simulators & Datasets
- Open-source Implementations

---

# 🧩 Contribution

Feel free to submit a pull request if you:
- Find a new VLA or robotics foundation model paper
- Want to fix metadata or links
- Add implementation notes
- Add benchmark results
- Add open-source repos or checkpoints

---

# ⭐ Acknowledgements

This repository is inspired by the rapid progress in:
- Vision-Language Models (VLMs)
- Robot Learning
- Foundation Models
- Diffusion & Flow Matching
- Embodied AI research communities

If you find this repository useful, consider starring ⭐ the repo.
