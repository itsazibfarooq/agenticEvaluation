<div align="center">

# Evaluating and Regulating Agentic AI
### A Study of Benchmarks, Metrics, and Regulation

[![Journal](https://img.shields.io/badge/Journal-Information%20Fusion-blue?style=for-the-badge)](https://www.sciencedirect.com/journal/information-fusion)
[![TechRxiv](https://img.shields.io/badge/TechRxiv-Preprint-orange?style=for-the-badge)](https://www.techrxiv.org/doi/full/10.36227/techrxiv.176186841.18883348/v1)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github)](https://github.com/itsazibfarooq/agenticEvaluation)
[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey?style=for-the-badge)](http://creativecommons.org/licenses/by-sa/4.0/)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge)](CONTRIBUTING.md)

<br/>

**[Azib Farooq](https://github.com/itsazibfarooq)<sup>1†</sup> · [Shaina Raza](https://vectorinstitute.ai/)<sup>2†</sup> · Nazmul Karim<sup>1</sup> · Hasan Iqbal<sup>3</sup> · Athanasios V. Vasilakos<sup>4‡</sup> · Christos Emmanouilidis<sup>5‡</sup>**

<sup>1</sup>University of Central Florida · <sup>2</sup>Vector Institute, Toronto · <sup>3</sup>Rocket Companies · <sup>4</sup>University of Agder (UiA) · <sup>5</sup>University of Groningen

<sup>†</sup>Equal Contribution · <sup>‡</sup>Senior Authors

<br/>

[📄 Paper](https://www.techrxiv.org/doi/full/10.36227/techrxiv.176186841.18883348/v1) · [💻 Code](https://github.com/itsazibfarooq/agenticEvaluation) · [🌐 Website](#)

</div>

---

## Abstract

> Agentic AI represents a new generation of AI systems capable of **perceiving, reasoning, planning, and acting** toward achieving goals with a degree of autonomy. Unlike traditional AI models that merely generate outputs, these systems maintain memory, interact with their environment, and adapt over time. However, evaluating such interactive and evolving behavior remains a significant challenge.
>
> This survey addresses that gap by reviewing recent progress in the evaluation and assessment of agentic AI, focusing on **three core dimensions: benchmarks, metrics, and governance**. We analyze how current evaluation frameworks capture reasoning, planning, collaboration, and ethical alignment across single- and multi-agent systems. Ultimately, this study aims to establish a unified foundation for building **trustworthy, auditable, and human-aligned AI agents**.

**Keywords:** `Agentic AI` · `Autonomous Agents` · `Responsible AI` · `Evaluation Frameworks` · `Benchmarks` · `Metrics` · `Governance` · `Trustworthiness` · `Human Alignment` · `Multi-Agent Systems`

---

## Overview

### Timeline of Agentic AI (2023–2025)

<div align="center">
  <img src="static/images/timeline.png" alt="Agentic AI Timeline" width="90%"/>
  <br/>
  <em>Illustrative timeline of representative agentic AI systems from 2023 to 2025, highlighting major architectural paradigms and emerging research directions.</em>
</div>

<br/>

### Agentic AI Pipeline

<div align="center">
  <img src="static/images/agentic_pipeline.png" alt="Agentic AI Pipeline" width="85%"/>
  <br/>
  <em>High-level overview of the agentic AI system pipeline, including perception, reasoning, planning, memory, and action components.</em>
</div>

---

## Key Contributions

This survey makes four primary contributions to the field of agentic AI evaluation:

| # | Contribution | Description |
|---|---|---|
| 1 | **Comprehensive Taxonomy** | A structured review of benchmarks and evaluation metrics for agentic AI, organized by lifecycle stages — mapping benchmark types, evaluation dimensions, and performance indicators |
| 2 | **Literature Analysis** | In-depth analysis of emerging trends, methodological gaps, and open challenges in the evaluation of agentic AI across 200+ surveyed papers |
| 3 | **Novel Evaluation Framework** | A unified, lifecycle-aware framework integrating: (1) Benchmark Validity Audit, (2) Gaming Detection Layer, (3) Contamination-Adjusted Scoring, and (4) Validity Compliance SLOs aligned with NIST AI RMF and ISO/IEC 42001 |
| 4 | **Governance Analysis** | Examination of governance dimensions and regulatory alignment with respect to trust, accountability, and compliance standards |

### Benchmark Taxonomy

<div align="center">
  <img src="static/images/bench_taxo.png" alt="Benchmark Taxonomy" width="85%"/>
  <br/>
  <em>Taxonomy of benchmarks for agentic AI evaluation, organized across domains: web, desktop, software, embodied, multi-agent, planning, and specialized settings.</em>
</div>

<br/>

### Metrics Taxonomy

<div align="center">
  <img src="static/images/metric_taxo.png" alt="Metrics Taxonomy" width="85%"/>
  <br/>
  <em>Taxonomy of evaluation metrics for agentic AI systems, covering quantitative and qualitative dimensions for measuring performance, reliability, and human alignment.</em>
</div>

<br/>

### Governance & Alignment Framework

<div align="center">
  <img src="static/images/alignment.png" alt="Governance Alignment" width="85%"/>
  <br/>
  <em>Overview of governance, policy, and alignment dimensions mapped against current agentic AI evaluation frameworks and regulatory standards.</em>
</div>

---

## Paper Organization

| Section | Title | Description |
|---------|-------|-------------|
| §1 | Introduction | Motivation, research questions, and main contributions |
| §2 | Literature Review Methodology | Search strategy, inclusion/exclusion criteria, thematic synthesis |
| §3 | Background | LLMs, VLMs, RAG, LLM-based agents, and multi-agent systems |
| §4 | Evaluation Framework | Novel lifecycle-aware unified evaluation framework |
| §5 | Benchmarks & Datasets | Comprehensive review of benchmarks across all major domains |
| §6 | Evaluation Metrics | Quantitative and qualitative dimensions for measuring performance |
| §7 | Governance & Regulation | Policy, audit frameworks, and regulatory compliance |
| §8 | Contamination & Benchmark Gaming | Evaluation loopholes and benchmark evolution |
| §9 | Discussion | Open challenges and future directions |
| §10 | Conclusion | Unified evaluation and governance frameworks |

---

## Complete Bibliography

This repository serves as a **living, community-maintained reference** for research on agentic AI evaluation. Below is the comprehensive, categorized bibliography from our paper.

> **Note:** This list is actively maintained. Community contributions are welcome — see the [Contributing](#contributing) section.

<details>
<summary><strong>🤖 Agentic AI & MAS — Surveys & General Concepts (12 papers)</strong></summary>

<br/>

| Authors | Year | Title | Venue |
|---------|------|-------|-------|
| Acharya, D. B., et al. | 2025 | _Agentic AI: Autonomous Intelligence for Complex Goals — A Comprehensive Survey_ | IEEE Access |
| Bandi, A., et al. | 2025 | _The Rise of Agentic AI: A Review of Definitions, Frameworks, Architectures, Applications, Evaluation Metrics, and Challenges_ | Future Internet |
| Chowa, S. S., et al. | 2025 | _From Language to Action: A Review of Large Language Models as Autonomous Agents and Tool Users_ | arXiv |
| Guo, T., et al. | 2024 | _Large Language Model Based Multi-Agents: A Survey of Progress and Challenges_ | arXiv |
| Hughes, L., et al. | 2025 | _AI Agents and Agentic Systems: A Multi-Expert Analysis_ | J. Computer Information Systems |
| Nisa, U., et al. | 2025 | _Agentic AI: The Age of Reasoning — A Review_ | J. Automation and Intelligence |
| Piccialli, F., et al. | 2025 | _AgentAI: A Comprehensive Survey on Autonomous Agents in Distributed AI for Industry 4.0_ | Expert Systems with Applications |
| Plaat, A., et al. | 2025 | _Agentic Large Language Models, a Survey_ | arXiv |
| Qu, X., et al. | 2025 | _A Comprehensive Review of AI Agents: Transforming Possibilities in Technology and Beyond_ | arXiv |
| Russell, S. J. & Norvig, P. | 2021 | _Artificial Intelligence: A Modern Approach_ (4th ed.) | Pearson |
| Wang, L., et al. | 2024 | _A Survey on Large Language Model Based Autonomous Agents_ | Frontiers of Computer Science |
| Wooldridge, M. | 2009 | _An Introduction to MultiAgent Systems_ (2nd ed.) | Wiley |

</details>

<details>
<summary><strong>🏗️ Agent Architectures, Reasoning & Frameworks (26 papers)</strong></summary>

<br/>

| Authors | Year | Title | Venue |
|---------|------|-------|-------|
| Ahn, M., et al. | 2022 | _Do As I Can, Not As I Say: Grounding Language in Robotic Affordances_ | arXiv |
| Belcak, P., et al. | 2025 | _Small Language Models are the Future of Agentic AI_ | arXiv |
| Bran, A. M., et al. | 2023 | _ChemCrow: Augmenting Large-Language Models with Chemistry Tools_ | arXiv |
| Chen, G., et al. | 2023 | _AutoAgents: A Framework for Automatic Agent Generation_ | arXiv |
| Chen, W., et al. | 2023 | _Program of Thoughts Prompting: Disentangling Computation from Reasoning for Numerical Reasoning Tasks_ | arXiv |
| Derouiche, H., et al. | 2025 | _Agentic AI Frameworks: Architectures, Protocols, and Design Challenges_ | arXiv |
| Feng, K. J., et al. | 2025 | _Levels of Autonomy for AI Agents_ | Knight First Amendment Institute |
| Haase, J. & Pokutta, S. | 2025 | _Beyond Static Responses: Multi-Agent LLM Systems as a New Paradigm for Social Science Research_ | arXiv |
| Hong, S., et al. | 2024 | _MetaGPT: Meta Programming for a Multi-Agent Collaborative Framework_ | ICLR |
| Lewis, P., et al. | 2020 | _Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks_ | NeurIPS |
| Li, D., et al. | 2025 | _SMoA: Improving Multi-Agent Large Language Models with Sparse Mixture-of-Agents_ | PAKDD |
| Li, G., et al. | 2023 | _CAMEL: Communicative Agents for "Mind" Exploration of Large Language Model Society_ | NeurIPS |
| Nakajima, Y. | 2023 | _BabyAGI: An Autonomous Task Management System_ | GitHub |
| Ouyang, L., et al. | 2022 | _Training Language Models to Follow Instructions with Human Feedback_ | NeurIPS |
| Park, J. S., et al. | 2023 | _Generative Agents: Interactive Simulacra of Human Behavior_ | UIST |
| Schick, T., et al. | 2023 | _Toolformer: Language Models Can Teach Themselves to Use Tools_ | arXiv |
| Shinn, N., et al. | 2023 | _Reflexion: Language Agents with Verbal Reinforcement Learning_ | NeurIPS |
| Talebirad, Y. & Nadiri, A. | 2023 | _Multi-Agent Collaboration: Harnessing the Power of Intelligent LLM Agents_ | arXiv |
| Wang, F., et al. | 2025 | _RAG+: Enhancing Retrieval-Augmented Generation with Application-Aware Reasoning_ | arXiv |
| Wang, G., et al. | 2023 | _Voyager: An Open-Ended Embodied Agent with Large Language Models_ | arXiv |
| Wang, J., et al. | 2024 | _Mixture-of-Agents Enhances Large Language Model Capabilities_ | arXiv |
| Wang, X., et al. | 2022 | _Self-Consistency Improves Chain of Thought Reasoning in Language Models_ | arXiv |
| Wu, X., et al. | 2024 | _Can Graph Learning Improve Planning in LLM-Based Agents?_ | NeurIPS |
| Yang, H., et al. | 2023 | _Auto-GPT for Online Decision Making: Benchmarks and Additional Opinions_ | arXiv |
| Yao, S., et al. | 2023 | _ReAct: Synergizing Reasoning and Acting in Language Models_ | ICLR |

</details>

<details>
<summary><strong>🔒 Governance, Risk, Security & Safety (27 papers)</strong></summary>

<br/>

| Authors | Year | Title | Venue |
|---------|------|-------|-------|
| Ahmed, S. Q. | 2025 | _Agentic AI: A Governance Wake-Up Call_ | NACD Directorship Magazine |
| Andriushchenko, M., et al. | 2024 | _AgentHarm: A Benchmark for Measuring Harmfulness of LLM Agents_ | arXiv |
| Anthropic | 2025 | _Responsible Scaling Policy, Version 2.1_ | Anthropic |
| Debenedetti, E., et al. | 2024 | _AgentDojo: A Dynamic Environment to Evaluate Prompt Injection Attacks and Defenses for LLM Agents_ | NeurIPS |
| Dong, Y., et al. | 2024 | _Building Guardrails for Large Language Models_ | arXiv |
| European Union | 2024 | _Regulation (EU) 2024/1689 — Artificial Intelligence Act_ | Official Journal of the EU |
| ISO & IEC | 2023 | _ISO/IEC 42001:2023 — Artificial Intelligence Management System_ | ISO |
| Levy, I., et al. | 2024 | _ST-WebAgentBench: A Benchmark for Evaluating Safety and Trustworthiness in Web Agents_ | arXiv |
| Lu, X., et al. | 2025 | _IS-Bench: Evaluating Interactive Safety of VLM-Driven Embodied Agents in Daily Household Tasks_ | arXiv |
| Marks, S., et al. | 2025 | _Auditing Language Models for Hidden Objectives_ | arXiv |
| Marks, S., et al. | 2025 | _Building and Evaluating Alignment Auditing Agents_ | AI Alignment Forum |
| MITRE Corporation | 2025 | _ATLAS: Adversarial Threat Landscape for Artificial-Intelligence Systems_ | MITRE |
| NIST | 2020 | _Zero Trust Architecture_ (SP 800-207) | NIST |
| NIST | 2023 | _Artificial Intelligence Risk Management Framework (AI RMF 1.0)_ (NIST AI 100-1) | NIST |
| NTIA | 2021 | _The Minimum Elements for a Software Bill of Materials (SBOM)_ | NTIA |
| Open Policy Agent Project | 2024 | _Open Policy Agent: Policy as Code_ | OPA |
| OWASP Foundation | 2025 | _OWASP Top 10 for Large Language Model Applications (2025)_ | OWASP |
| Raza, S., et al. | 2025 | _TRiSM for Agentic AI: A Review of Trust, Risk, and Security Management_ | arXiv |
| Ruan, Y., et al. | 2023 | _Identifying the Risks of LM Agents with an LM-Emulated Sandbox_ | arXiv |
| Sherman, E., et al. | 2025 | _From Assistant to Agent: Navigating the Governance Challenges of Increasingly Autonomous AI_ | Credo AI |
| Shukla, M. | 2025 | _Adaptive Monitoring and Real-World Evaluation of Agentic AI Systems_ | arXiv |
| SLSA Community | 2023 | _SLSA Specification v1.0_ | SLSA |
| Thurgood, S., et al. | 2018 | _Example Error Budget Policy_ | Google SRE |
| Torres-Arias, S., et al. | 2019 | _in-toto: Providing Farm-to-Table Guarantees for Bits and Bytes_ | USENIX Security |
| Verifiable Credentials WG | 2025 | _Verifiable Credentials Data Model 2.0_ | W3C |
| Wang, N., et al. | 2025 | _Advancing Embodied Agent Security: From Safety Benchmarks to Input Moderation_ | arXiv |
| Yin, S., et al. | 2024 | _SafeAgentBench: A Benchmark for Safe Task Planning of Embodied LLM Agents_ | arXiv |
| Yu, M., et al. | 2025 | _A Survey on Trustworthy LLM Agents: Threats and Countermeasures_ | KDD |

</details>

<details>
<summary><strong>⚖️ Responsible AI, Bias & Human-in-the-Loop (7 papers)</strong></summary>

<br/>

| Authors | Year | Title | Venue |
|---------|------|-------|-------|
| Mosqueira-Rey, E., et al. | 2023 | _Human-in-the-Loop Machine Learning: A State of the Art_ | Artificial Intelligence Review |
| Raza, S., et al. | 2024 | _Exploring Bias and Prediction Metrics to Characterise the Fairness of Machine Learning_ | IEEE Access |
| Raza, S., et al. | 2025 | _Developing Safe and Responsible Large Language Model: Can We Balance Bias Reduction and Language Understanding?_ | Machine Learning |
| Raza, S., et al. | 2025 | _HumaniBench: A Human-Centric Framework for Large Multimodal Models Evaluation_ | arXiv |
| Raza, S., et al. | 2025 | _Responsible Agentic Reasoning and AI Agents: A Critical Survey_ | Authorea Preprints |
| Raza, S., et al. | 2025 | _ViLBias: Detecting and Reasoning about Bias in Multimodal Content_ | arXiv |
| Raza, S., et al. | 2025 | _Who is Responsible? The Data, Models, Users or Regulations? A Comprehensive Survey_ | arXiv |

</details>

<details>
<summary><strong>🧠 Agent Memory (5 papers)</strong></summary>

<br/>

| Authors | Year | Title | Venue |
|---------|------|-------|-------|
| Cherepanov, E., et al. | 2025 | _Memory, Benchmark & Robots: A Benchmark for Solving Complex Tasks_ | arXiv |
| Pasukonis, J., et al. | 2022 | _Evaluating Long-Term Memory in 3D Mazes_ | arXiv |
| Wang, F., et al. | 2025 | _Text2Mem: A Unified Memory Operation Language for Memory Operating System_ | arXiv |
| Xia, M., et al. | 2025 | _Minerva: A Programmable Memory Test Benchmark for Language Models_ | arXiv |
| Xu, W., et al. | 2025 | _A-MEM: Agentic Memory for LLM Agents_ | arXiv |

</details>

<details>
<summary><strong>📊 Benchmarking: General & Multi-Domain (18 papers)</strong></summary>

<br/>

| Authors | Year | Title | Venue |
|---------|------|-------|-------|
| Chang, M., et al. | 2024 | _AgentBoard: An Analytical Evaluation Board of Multi-Turn LLM Agents_ | NeurIPS |
| Gioacchini, L., et al. | 2024 | _AgentQuest: A Modular Benchmark Framework to Measure Progress and Improve LLM Agents_ | arXiv |
| IBM | 2025 | _Agentic AI Evaluation_ | IBM Docs |
| Li, M., et al. | 2023 | _API-Bank: A Comprehensive Benchmark for Tool-Augmented LLMs_ | arXiv |
| Liu, X., et al. | 2023 | _AgentBench: Evaluating LLMs as Agents_ | arXiv |
| Mialon, G., et al. | 2023 | _GAIA: A Benchmark for General AI Assistants_ | ICLR |
| Mohammadi, M., et al. | 2025 | _Evaluation and Benchmarking of LLM Agents: A Survey_ | KDD |
| Nath, V., et al. | 2025 | _ToolComp: A Multi-Tool Reasoning & Process Supervision Benchmark_ | arXiv |
| Patil, S. G., et al. | 2024 | _Gorilla: Large Language Model Connected with Massive APIs_ | NeurIPS |
| Qin, Y., et al. | 2023 | _ToolLLM: Facilitating Large Language Models to Master 16000+ Real-World APIs_ | arXiv |
| Shen, Y., et al. | 2024 | _TaskBench: Benchmarking Large Language Models for Task Automation_ | NeurIPS |
| Uchendu, I., et al. | 2025 | _A2Perf: Real-World Autonomous Agents Benchmark_ | arXiv |
| Wang, X., et al. | 2023 | _MINT: Evaluating LLMs in Multi-Turn Interaction with Tools and Language Feedback_ | arXiv |
| Wu, C. K., et al. | 2024 | _StreamBench: Towards Benchmarking Continuous Improvement of Language Agents_ | NeurIPS |
| Xu, F. F., et al. | 2024 | _TheAgentCompany: Benchmarking LLM Agents on Consequential Real World Tasks_ | arXiv |
| Xu, Q., et al. | 2023 | _On the Tool Manipulation Capability of Open-Source Large Language Models_ | arXiv |
| Yao, S., et al. | 2024 | _τ-Bench: A Benchmark for Tool-Agent-User Interaction in Real-World Domains_ | arXiv |
| Yehudai, A., et al. | 2025 | _Survey on Evaluation of LLM-Based Agents_ | arXiv |

</details>

<details>
<summary><strong>🌐 Benchmarking: Web, Desktop & UI Agents (17 papers)</strong></summary>

<br/>

| Authors | Year | Title | Venue |
|---------|------|-------|-------|
| Chen, J., et al. | 2024 | _SPA-Bench: A Comprehensive Benchmark for Smartphone Agent Evaluation_ | NeurIPS Workshop |
| Chezelles, D., et al. | 2024 | _The BrowserGym Ecosystem for Web Agent Research_ | arXiv |
| Deng, X., et al. | 2023 | _Mind2Web: Towards a Generalist Agent for the Web_ | NeurIPS |
| Gou, B., et al. | 2025 | _Mind2Web 2: Evaluating Agentic Search with Agent-as-a-Judge_ | arXiv |
| Kapoor, R., et al. | 2024 | _OmniACT: A Dataset and Benchmark for Enabling Multimodal Generalist Autonomous Agents_ | ECCV |
| Koh, J. Y., et al. | 2024 | _VisualWebArena: Evaluating Multimodal Agents on Realistic Visual Web Tasks_ | arXiv |
| Pan, Y., et al. | 2024 | _WebCanvas: Benchmarking Web Agents in Online Environments_ | arXiv |
| Peeters, R., et al. | 2025 | _WebMall — A Multi-Shop Benchmark for Evaluating Web Agents_ | arXiv |
| Tian, S., et al. | 2024 | _MMInA: Benchmarking Multihop Multimodal Internet Agents_ | arXiv |
| Trivedi, H., et al. | 2024 | _AppWorld: A Controllable World of Apps and People for Benchmarking Interactive Coding Agents_ | arXiv |
| Wang, H., et al. | 2025 | _UI-TARS-2 Technical Report: Advancing GUI Agent with Multi-Turn Reinforcement Learning_ | arXiv |
| Wang, J., et al. | 2024 | _HammerBench: Fine-Grained Function-Calling Evaluation in Real Mobile Device Scenarios_ | arXiv |
| Xie, T., et al. | 2024 | _OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments_ | NeurIPS |
| Xing, M., et al. | 2024 | _Understanding the Weakness of Large Language Model Agents within a Complex Android Environment_ | KDD |
| Yao, S., et al. | 2022 | _WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents_ | NeurIPS |
| Yoran, O., et al. | 2024 | _AssistantBench: Can Web Agents Solve Realistic and Time-Consuming Tasks?_ | arXiv |
| Zhou, S., et al. | 2023 | _WebArena: A Realistic Web Environment for Building Autonomous Agents_ | arXiv |

</details>

<details>
<summary><strong>💻 Benchmarking: Software, ML & Data Science (15 papers)</strong></summary>

<br/>

| Authors | Year | Title | Venue |
|---------|------|-------|-------|
| Bogin, B., et al. | 2024 | _SUPER: Evaluating Agents on Setting Up and Executing Tasks from Research Repositories_ | arXiv |
| Chan, J. S., et al. | 2024 | _MLE-Bench: Evaluating Machine Learning Agents on Machine Learning Engineering_ | arXiv |
| Deshpande, D., et al. | 2025 | _TRAIL: Trace Reasoning and Agentic Issue Localization_ | arXiv |
| Huang, B., et al. | 2025 | _DCA-Bench: A Benchmark for Dataset Curation Agents_ | KDD |
| Huang, Q., et al. | 2023 | _MLAgentBench: Evaluating Language Agents on Machine Learning Experimentation_ | arXiv |
| Jha, S., et al. | 2025 | _ITBench: Evaluating AI Agents Across Diverse Real-World IT Automation Tasks_ | arXiv |
| Jimenez, C. E., et al. | 2023 | _SWE-Bench: Can Language Models Resolve Real-World GitHub Issues?_ | arXiv |
| Li, K., et al. | 2025 | _DatasetResearch: Benchmarking Agent Systems for Demand-Driven Dataset Discovery_ | arXiv |
| Miserendino, S., et al. | 2025 | _SWE-Lancer: Can Frontier LLMs Earn $1 Million from Real-World Freelance Software Engineering?_ | arXiv |
| Padigela, H., et al. | 2025 | _ML-Dev-Bench: Comparative Analysis of AI Agents on ML Development Workflows_ | arXiv |
| Rashid, M. S., et al. | 2025 | _SWE-PolyBench: A Multi-Language Benchmark for Repository Level Evaluation of Coding Agents_ | arXiv |
| Rein, D., et al. | 2025 | _HCAST: Human-Calibrated Autonomy Software Tasks_ | arXiv |
| Siegel, Z. S., et al. | 2024 | _CORE-Bench: Fostering the Credibility of Published Research through a Computational Reproducibility Agent Benchmark_ | arXiv |
| Starace, G., et al. | 2025 | _PaperBench: Evaluating AI's Ability to Replicate AI Research_ | arXiv |
| Wijk, H., et al. | 2024 | _RE-Bench: Evaluating Frontier AI R&D Capabilities of Language Model Agents_ | arXiv |

</details>

<details>
<summary><strong>🤝 Benchmarking: Multi-Agent & Collaboration (13 papers)</strong></summary>

<br/>

| Authors | Year | Title | Venue |
|---------|------|-------|-------|
| Agashe, S., et al. | 2023 | _LLM-Coordination: Evaluating and Analyzing Multi-Agent Coordination Abilities_ | arXiv |
| Chen, J., et al. | 2024 | _LLMArena: Assessing Capabilities of Large Language Models in Dynamic Multi-Agent Environments_ | arXiv |
| Chen, H., et al. | 2024 | _SocialBench: Sociality Evaluation of Role-Playing Conversational Agents_ | arXiv |
| Dong, Y., et al. | 2024 | _VillagerAgent: A Graph-Based Multi-Agent Framework for Coordinating Complex Task Dependencies_ | arXiv |
| Gong, R., et al. | 2023 | _MindAgent: Emergent Gaming Interaction_ | arXiv |
| Hyun, J., et al. | 2025 | _CREW-WILDFIRE: Benchmarking Agentic Multi-Agent Collaborations at Scale_ | arXiv |
| Mandi, Z., et al. | 2024 | _RoCo: Dialectic Multi-Robot Collaboration with Large Language Models_ | ICRA |
| Qi, S., et al. | 2024 | _CivRealm: A Learning and Reasoning Odyssey in Civilization for Decision-Making Agents_ | arXiv |
| Sun, H., et al. | 2025 | _Collab-Overcooked: Benchmarking and Evaluating Large Language Models as Collaborative Agents_ | arXiv |
| Wang, W., et al. | 2024 | _BattleAgentBench: A Benchmark for Evaluating Cooperation and Competition Capabilities_ | arXiv |
| Zhou, X., et al. | 2023 | _SOTOPIA: Interactive Evaluation for Social Intelligence in Language Agents_ | arXiv |
| Zhou, Y., et al. | 2025 | _Sweet-RL: Training Multi-Turn LLM Agents on Collaborative Reasoning Tasks_ | arXiv |
| Zhu, K., et al. | 2025 | _MultiAgentBench: Evaluating the Collaboration and Competition of LLM Agents_ | arXiv |

</details>

<details>
<summary><strong>🧩 Benchmarking: Planning & Reasoning (11 papers)</strong></summary>

<br/>

| Authors | Year | Title | Venue |
|---------|------|-------|-------|
| Bogavelli, T., et al. | 2025 | _AgentArch: A Comprehensive Benchmark to Evaluate Agent Architectures in Enterprise_ | arXiv |
| Chen, L., et al. | 2024 | _MindBench: A Comprehensive Benchmark for Mind Map Structure Recognition and Analysis_ | arXiv |
| Geng, L. & Chang, E. Y. | 2025 | _REALM-Bench: A Real-World Planning Benchmark for LLMs and Multi-Agent Systems_ | arXiv |
| Kokel, H., et al. | 2025 | _ACPBench: Reasoning about Action, Change, and Planning_ | AAAI |
| Li, L., et al. | 2024 | _Reflection-Bench: Evaluating Epistemic Agency in Large Language Models_ | arXiv |
| Liu, Y., et al. | 2024 | _Tool-Planner: Task Planning with Clusters Across Multiple Tools_ | arXiv |
| Stein, K., et al. | 2023 | _AutoPlanBench: Automatically Generating Benchmarks for LLM Planners from PDDL_ | arXiv |
| Valmeekam, K., et al. | 2023 | _PlanBench: An Extensible Benchmark for Evaluating Large Language Models on Planning_ | NeurIPS |
| Xiao, R., et al. | 2024 | _FlowBench: Revisiting and Benchmarking Workflow-Guided Planning for LLM-Based Agents_ | arXiv |
| Zhang, Y., et al. | 2024 | _TimeArena: Shaping Efficient Multitasking Language Agents in a Time-Aware Simulation_ | arXiv |
| Zheng, H. S., et al. | 2024 | _Natural Plan: Benchmarking LLMs on Natural Language Planning_ | arXiv |

</details>

<details>
<summary><strong>👁️ Benchmarking: Embodied, Vision & Multimodal (5 papers)</strong></summary>

<br/>

| Authors | Year | Title | Venue |
|---------|------|-------|-------|
| Huang, J., et al. | 2024 | _MMEvalPro: Calibrating Multimodal Benchmarks Towards Trustworthy and Efficient Evaluation_ | arXiv |
| Li, M., et al. | 2024 | _Embodied Agent Interface: Benchmarking LLMs for Embodied Decision Making_ | NeurIPS |
| Ma, Z., et al. | 2024 | _M&M's: A Benchmark to Evaluate Tool-Use for Multi-Step Multi-Modal Tasks_ | ECCV |
| Shridhar, M., et al. | 2020 | _ALFWorld: Aligning Text and Embodied Environments for Interactive Learning_ | arXiv |
| Yang, R., et al. | 2025 | _EmbodiedBench: Comprehensive Benchmarking Multi-Modal Large Language Models for Vision-Driven Embodied Agents_ | arXiv |

</details>

<details>
<summary><strong>🔬 Benchmarking: Specialized Domains (5 papers)</strong></summary>

<br/>

| Authors | Year | Title | Venue |
|---------|------|-------|-------|
| Achim, T., et al. | 2025 | _Aristotle: IMO-Level Automated Theorem Proving_ | arXiv |
| Chen, L., et al. | 2025 | _SEED-Prover: Deep and Broad Reasoning for Automated Theorem Proving_ | arXiv |
| Chen, Z., et al. | 2024 | _ScienceAgentBench: Toward Rigorous Assessment of Language Agents for Data-Driven Scientific Discovery_ | arXiv |
| Moteki, A., et al. | 2025 | _FieldWorkArena: Agentic AI Benchmark for Real Field Work Tasks_ | arXiv |
| Zhang, X., et al. | 2025 | _EduPlanner: LLM-Based Multi-Agent Systems for Customized and Intelligent Instructional Design_ | IEEE Trans. on Learning Technologies |

</details>

<details>
<summary><strong>⚙️ Core Technologies & Foundational Datasets (9 papers)</strong></summary>

<br/>

| Authors | Year | Title | Venue |
|---------|------|-------|-------|
| Artacho, B. & Savakis, A. | 2021 | _OmniPose: A Multi-Scale Framework for Multi-Person Pose Estimation_ | arXiv |
| Bordes, F., et al. | 2024 | _An Introduction to Vision-Language Modeling_ | arXiv |
| Huang, C., et al. | 2025 | _R-Zero: Self-Evolving Reasoning LLM from Zero Data_ | arXiv |
| Kumar, S., et al. | 2024 | _The Need for a Big World Simulator: A Scientific Challenge for Continual Learning_ | arXiv |
| Lin, J., et al. | 2024 | _CT-GLIP: 3D Grounded Language-Image Pretraining with CT Scans and Radiology Reports_ | arXiv |
| Yang, Z., et al. | 2018 | _HotpotQA: A Dataset for Diverse, Explainable Multi-Hop Question Answering_ | arXiv |
| Ye, D., et al. | 2025 | _YAN: Foundational Interactive Video Generation_ | arXiv |
| Zhang, T., et al. | 2021 | _C-Planning: An Automatic Curriculum for Learning Goal-Reaching Tasks_ | arXiv |
| Zhang, Z., et al. | 2025 | _RoboAct-CLIP: Video-Driven Pre-training of Atomic Action Understanding for Robotics_ | arXiv |

</details>

---

## Citation

If you find this work useful in your research, please cite our paper:

```bibtex
@article{farooq2025agentic,
  title     = {Evaluating and Regulating Agentic AI: A Study of Benchmarks, Metrics, and Regulation},
  author    = {Farooq, Azib and Raza, Shaina and Karim, Nazmul and Iqbal, Hasan and Vasilakos, Athanasios V. and Emmanouilidis, Christos},
  journal   = {Information Fusion},
  year      = {2025},
  note      = {TechRxiv preprint: \url{https://www.techrxiv.org/doi/full/10.36227/techrxiv.176186841.18883348/v1}}
}
```

---

## Contributing

We welcome contributions from the community! This bibliography is intended to be a living resource for researchers working on agentic AI evaluation. Here's how you can help:

### Ways to Contribute

| Contribution Type | Description |
|---|---|
| **New Papers** | Add recently published papers on agentic AI benchmarks, metrics, or governance |
| **Missing Papers** | Flag papers that belong in an existing category but are not listed |
| **Corrections** | Fix errors in author names, titles, venues, or years |
| **New Categories** | Propose new thematic categories as the field evolves |
| **Discussion** | Open an issue to discuss the taxonomy or scope of the bibliography |

### Contribution Guidelines

1. **Fork** the repository and create a new branch: `git checkout -b add/paper-name`
2. **Edit** the `README.md` file, adding the paper to the most appropriate category section
3. **Follow the format** used in the existing tables:
   ```
   | Authors, et al. | Year | _Title of the Paper_ | Venue |
   ```
4. **Verify** that the paper is peer-reviewed or a well-known preprint in the field
5. **Open a Pull Request** with a brief description of the added paper(s)

### Paper Inclusion Criteria

- The paper must be **directly relevant** to agentic AI evaluation, benchmarking, governance, or closely related foundational work
- Preprints are accepted if they have had **significant community impact** (e.g., high citation count or broad adoption)
- Papers should be **publicly accessible** (open access, arXiv, or institutional repository)

### Opening Issues

Use [GitHub Issues](https://github.com/itsazibfarooq/agenticEvaluation/issues) to:
- Suggest papers to add
- Report errors or outdated information
- Propose structural improvements to the bibliography
- Ask questions about the paper or scope

We appreciate every contribution, no matter how small. Together, we can build the most comprehensive reference for agentic AI evaluation research.

---

<div align="center">

**If you find this resource helpful, please consider giving it a ⭐ star!**

[![Star History](https://img.shields.io/github/stars/itsazibfarooq/agenticEvaluation?style=social)](https://github.com/itsazibfarooq/agenticEvaluation)

<br/>

Licensed under [CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/) · © 2025 Azib Farooq, Shaina Raza, et al.

</div>
