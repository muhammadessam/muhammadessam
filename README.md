# Mohamed Saleh

**Electrical Engineer & Researcher · Hannover, Germany**

[![Email](https://img.shields.io/badge/Email-mohamed.saleh.de%40outlook.com-blue?style=flat-square&logo=microsoft-outlook)](mailto:mohamed.saleh.de@outlook.com)
[![arXiv](https://img.shields.io/badge/arXiv-2602.00701-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2602.00701)
[![GitHub](https://img.shields.io/badge/GitHub-control--systems101-181717?style=flat-square&logo=github)](https://github.com/control-systems101)
[![ResearchGate](https://img.shields.io/badge/ResearchGate-Profile-00CCBB?style=flat-square&logo=researchgate)](https://www.researchgate.net/profile/Mohamed-Saleh)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-%2B49%201627755198-25D366?style=flat-square&logo=whatsapp)](https://wa.me/+491627755198)

---

## About Me

I am a researcher working at the intersection of **control systems and machine learning** — two disciplines I have pursued in depth and am now driven to unify. My work spans real-time Model Predictive Control for unstable robotic systems and energy-efficient spiking neural architectures for multimodal perception, giving me a dual fluency in **optimization-grounded control theory** and **modern deep learning**.

My current research interest lies in **integrating predictive control with learned representations**, with applications in robotics, autonomous systems, and resource-constrained edge intelligence. I am actively seeking a PhD position to pursue this direction rigorously and at scale.

---

## Education

### M.Sc. in Electrical Engineering (Computer & Systems)
**Minia University, Faculty of Engineering** — Minia, Egypt · *2024*

- **Ranked 1st in Class** | Cumulative GPA: 85.17%
- **Thesis:** *Optimal Hybrid Control for Unstable Robotic Systems* · [[PDF](https://muedueg-my.sharepoint.com/:b:/g/personal/muhammad_essam_mu_edu_eg/ESSOphQX2ApEn1N4oOotgKABKByLNAQNmWKk8xV2fbcv7g?e=0YFazy)]
- **Focus Areas:** Optimization Theory, Nonlinear Modeling, Model Predictive Control (MPC), Grey-Box System Identification, Embedded Real-Time Control
- **Key Achievement:** Formulated and deployed constrained MPC (via Quadratic Programming) on physical hardware at 200 Hz, successfully bridging MATLAB/Simulink simulation to Raspberry Pi 4 in a closed-loop robotic control task.
- **Supervisors:** Prof. Mohammed Moness & Dr. Ahmed Mahmoud Moustafa (Minia University)

### B.Sc. in Computer and Systems Engineering
**Minia University, Faculty of Engineering** — Minia, Egypt · *2018*

- **Distinction with Honors · 89.3% · Ranked 1st in Class**
- **Graduation Project:** *Cooperative Control of Multi-Agent System for Industrial Internet of Robotic Things* — Awarded a competitive research fund by the Academy of Scientific Research and Technology (ASRT). **Grade: Distinction.** · [[Report](https://www.researchgate.net/publication/326446132_Cooperative_Control_of_Multi-agent_System_for_Industrial_Internet_of_Robotic_Things)]

---

## Research & Academic Experience

### Research Associate (Short-Term Contract)
**Peter L. Reichertz Institute for Medical Informatics (PLRI/MHH)** — Hannover, Germany · *Apr. 2025 – Oct. 2025*

*Supervised by Dr. rer. nat. Zahra Ahmadi (EMuLe & CAIMed, Junior Group Leader)*

- Independently identified multimodal audio-visual learning as an underexplored direction within energy-efficient SNNs and scoped the full research problem that became the **SNNergy** project.
- Designed the **Cross-Modal Query-Key Attention (CMQKA)** mechanism, reducing cross-modal attention complexity from O(N²) to O(N) through binary spike decomposition — enabling, for the first time, a deep hierarchical multimodal SNN architecture.
- Authored a neuromorphic hardware access proposal targeting Intel Loihi deployment of SNNergy, bridging algorithmic efficiency with real-time edge inference constraints.
- Co-authored a manuscript submitted to *Information Fusion* (Elsevier, 2026) and presented research outcomes at an institute-wide cross-group research exchange.
- Conducted a comprehensive literature review spanning spiking transformers, multimodal fusion strategies, and neuromorphic computing.

### Researcher & Teaching Assistant
**Minia University, Faculty of Engineering** — Minia, Egypt · *Feb. 2019 – Mar. 2024*

**Research:**
- Conducted M.Sc. research on real-time MPC, grey-box system identification, and hybrid modeling for nonlinear robotic platforms.
- Applied Dynamic Mode Decomposition with Control (DMDc) to extract linear state-space models from sensor data collected on a physical TWSBR, directly integrating the identified model into a closed-loop MPC framework.
- Published peer-reviewed research on nonlinear modeling and parameter estimation (see Publications).

**Teaching:**
- Independently delivered undergraduate courses in **Embedded Systems** and **Machine Learning** electives.
- Assisted senior faculty in **Digital Control Systems**, **Systems Analysis & Design**, and **Operations Research**.

**Mentorship:**
- Coached interdisciplinary student teams through the complete hardware/software lifecycle: from data preprocessing and algorithm design to embedded deployment and real-time validation of control algorithms.

**Service:**
- Presented research at departmental seminars; contributed to lab equipment management and exam supervision.

### Machine Learning Internship
**IBM Egypt** — Cairo, Egypt · *2017*

- Built and deployed a recommendation system using Flask and IBM Developer Cloud.
- Gained foundational experience in API development and production machine learning pipelines.

---

## Publications

1. **Mohamed Saleh**, Zahra Ahmadi. "Cross-Modal Binary Attention: An Energy-Efficient Fusion Framework for Audio-Visual Learning." *Submitted to Information Fusion* (Elsevier), 2026. · [[arXiv:2602.00701](https://arxiv.org/abs/2602.00701)]

2. **Muhammad Hassan**\*, Ahmed Mahmoud Moustafa, and Mohammed Moness. "Modeling and Parameters Estimation of a Self-Balancing Two-Wheeled Vehicle." *Journal of Advanced Engineering Trends*, 43.1 (2024): 373–381. · [[Link](https://www.researchgate.net/publication/382022584_Modeling_and_Parameters_Estimation_of_a_Self-Balancing_Two-Wheeled_Vehicle)]

> \* *Note: "Muhammad Hassan" is an alternative transliteration of my name (Mohamed Saleh) used in earlier publications.*

---

## Key Research Projects

### Real-Time MPC for a Two-Wheeled Self-Balancing Robot (TWSBR)
[![Video](https://img.shields.io/badge/Video-Demo-red?style=flat-square&logo=youtube)](https://youtu.be/wMrWURC7zU8)
[![Code](https://img.shields.io/badge/Code-GitHub-181717?style=flat-square&logo=github)](https://github.com/control-systems101/MPC)
[![Thesis](https://img.shields.io/badge/Thesis-PDF-orange?style=flat-square)](https://muedueg-my.sharepoint.com/:b:/g/personal/muhammad_essam_mu_edu_eg/ESSOphQX2ApEn1N4oOotgKABKByLNAQNmWKk8xV2fbcv7g?e=0YFazy)

*M.Sc. Thesis · Minia University · 2024*

- Derived a full nonlinear dynamic model via **Lagrangian mechanics**, capturing wheel-body coupling, friction, and actuator dynamics.
- Performed **grey-box parameter estimation** through a sensitivity-guided, two-stage successive optimization strategy to resolve physically ambiguous parameters (moments of inertia, viscous friction, CoG location) under limited measurement data.
- Applied **DMDc** to extract a linear state-space model directly from sensor data on the physical platform; integrated the identified model in a closed-loop predictive control framework — demonstrating the complete data-to-control pipeline.
- Formulated constrained MPC as a **Quadratic Programming (QP)** problem (prediction horizon N=20, control horizon N=5, T_s=5 ms) and deployed on **Raspberry Pi 4 at 200 Hz** using MATLAB/Simulink embedded code generation.
- Experimentally demonstrated that constraint-aware MPC eliminates actuator saturation and oscillations endemic to unconstrained formulations, with validated **Sim2Real transfer** on physical hardware.

---

### SNNergy: A Deep Hierarchical Multimodal Spiking Transformer Framework
[![Code](https://img.shields.io/badge/Code-GitHub-181717?style=flat-square&logo=github)](https://github.com/muhammadessam/linear_attention_res_learning)
[![arXiv](https://img.shields.io/badge/arXiv-2602.00701-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2602.00701)

*Research Associate · PLRI/MHH · 2025*

- Designed **CMQKA (Cross-Modal Query-Key Attention)**, reducing cross-modal attention complexity from **O(N²) to O(N)** through channel-aggregated binary spike decomposition, enabling the first deep hierarchical multimodal SNN architecture for audio-visual learning.
- Architected **SNNergy**, a three-stage hierarchical SNN framework (H/4 → H/8 → H/16) using SpikingJelly/PyTorch, trained on NVIDIA A100 GPUs with surrogate gradient BPTT.
- Achieved **state-of-the-art results** among SNN-based multimodal methods:

| Dataset | SNNergy | Prev. Best SNN | vs. Best ANN Baseline |
|---|---|---|---|
| CREMA-D | **78.38%** | 77.55% (TAAF-SNNs) | +1.92% over OGM-EG |
| AVE | **72.14%** | 70.65% (TAAF-SNNs) | +7.47% over OGM-EG |
| UrbanSound8K-AV | **99.66%** | 98.28% (CMCI) | Competitive |

- Proposed SNNergy as a target for deployment on **Intel Loihi neuromorphic hardware**, bridging algorithmic efficiency with real-time edge inference constraints in a hardware access proposal.
- Submitted to *Information Fusion* (Elsevier, 2026) · arXiv:2602.00701.

---

### Cooperative Control of Multi-Agent System for Industrial IoRT
[![Report](https://img.shields.io/badge/Report-ResearchGate-00CCBB?style=flat-square&logo=researchgate)](https://www.researchgate.net/publication/326446132_Cooperative_Control_of_Multi-agent_System_for_Industrial_Internet_of_Robotic_Things)

*B.Sc. Graduation Project · Minia University · 2018 · Funded by ASRT*

- Designed and built three autonomous mobile robots and implemented a **centralized feedback control algorithm** for multi-agent coordination in a simulated industrial environment.
- Awarded a competitive research grant by the **Academy of Scientific Research and Technology (ASRT)**, Egypt.
- Explored decentralized decision-making architectures as a research extension, establishing a foundation for multi-agent coordination challenges in connected production environments.

---

## Technical Skills

**Control & Optimization**
Model Predictive Control (Linear/Nonlinear/Robust), Quadratic Programming (QP), LQR/LQG, Optimal Control, Constraint Handling, Receding Horizon Control, Dynamic Mode Decomposition with Control (DMDc)

**Modeling & System Identification**
Nonlinear System Modeling, Grey-Box Identification, Sensitivity Analysis, Lagrangian Mechanics, State-Space Representations, EKF/UKF State Estimation

**Machine Learning & Deep Learning**
Spiking Neural Networks (SNNs), Transformer Architectures, Multimodal Fusion, Surrogate Gradient Training (BPTT), PyTorch, SpikingJelly, Deep Learning

**Simulation & Implementation**
MATLAB/Simulink (code generation, hardware deployment), Python (NumPy, SciPy, CasADi), Real-Time Control Loop Design, Hardware-in-the-Loop Validation, Sim2Real Transfer

**Embedded Systems & Hardware**
Raspberry Pi 4, Microcontroller Deployment, Sensor Fusion, H-Bridge Motor Control, IMU Integration

**Programming & Tools**
Python · C/C++ · MATLAB · Simulink · Git · Linux · Docker · LaTeX

**Languages**
Arabic (Native) · English (Professional/Academic) · German (Learning)

---

## Awards & Grants

- **Research Fund Award** — Academy of Scientific Research and Technology (ASRT), Egypt · *2018*
  Awarded competitive funding for the B.Sc. graduation project on cooperative control of multi-agent robotic systems.

- **M.Sc. Ranked 1st in Class** — Faculty of Engineering, Minia University · *2024*

- **B.Sc. Ranked 1st in Class, Distinction with Honors (89.3%)** — Faculty of Engineering, Minia University · *2018*

---

## References

**Dr. rer. nat. Zahra Ahmadi**
Junior Group Leader, EMuLe & CAIMed
Peter L. Reichertz Institute for Medical Informatics (PLRI), TU Braunschweig & Hannover Medical School
✉ [zahra.ahmadi@plri.de](mailto:zahra.ahmadi@plri.de)

**Dr. Ahmed M. Moustafa**
Head, Computer and Systems Engineering Department
Faculty of Engineering, Minia University, Egypt
✉ [ahmed.mahmoud@mu.edu.eg](mailto:ahmed.mahmoud@mu.edu.eg)

---

<div align="center">

*"I bridge the gap between what systems can predict and what they can learn."*

</div>
