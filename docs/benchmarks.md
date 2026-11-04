# 🧪 Benchmarks and Evaluation

[![Back to collection](https://img.shields.io/badge/←_Collection-Awesome_Multi--Tool_Agents-8b5cf6?style=flat)](../README.md)
![Indexed works](https://img.shields.io/badge/Indexed_works-49-8b5cf6?style=flat)

Evaluation of dependency structure, interaction horizon, changing environments, persistent state, recovery, and execution control.

**Survey correspondence:** Section 8. **Indexed works:** 49.

The initial entries follow the [published survey corpus](../data/README.md), with a literature cutoff of **26 July 2026**. Years and publication status follow that snapshot. Cross-cutting works may appear on more than one topic page.

A benchmark may test several dimensions; its entry is placed under one main reading category here. ToolSandbox and AppWorld, listed under dynamic environments, also test persistent state. Safety benchmarks have a separate group. The categories support benchmark selection; they do not define a shared leaderboard.

<a id="general-tool-use-evaluation-and-data"></a>
## 📂 General Tool-Use Evaluation and Data

| Paper | Year | Publication |
| --- | --- | --- |
| 📄 [MetaTool Benchmark for Large Language Models: Deciding Whether to Use Tools and Which to Use](https://proceedings.iclr.cc/paper_files/paper/2024/hash/bc12914d66b41b6bfc2d3a5decdb498b-Abstract-Conference.html) · [💻 GitHub](https://github.com/HowieHwong/MetaTool) | 2024 | The Twelfth International Conference on Learning Representations (ICLR 2024) |
| 📄 [API-Bank: A Comprehensive Benchmark for Tool-Augmented LLMs](https://doi.org/10.18653/v1/2023.emnlp-main.187) · [💻 GitHub](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/api-bank) | 2023 | Proceedings of the 2023 conference on empirical methods in natural language processing |

<a id="topological-complexity"></a>
## 📂 Topological Complexity

| Paper | Year | Publication |
| --- | --- | --- |
| 📄 [Towards Reliable Benchmarking: A Contamination Free, Controllable Evaluation Framework for Multi-step LLM Function Calling](https://openreview.net/forum?id=UKYCJixSFt) · [💻 GitHub](https://github.com/megagonlabs/FuncBenchGen) | 2026 | ICLR 2026 |
| 📄 [TRAJECT-Bench: A Trajectory-Aware Benchmark for Evaluating Agentic Tool Use](https://iclr.cc/virtual/2026/poster/10009304) · [💻 GitHub](https://github.com/PengfeiHePower/TRAJECT-Bench) | 2026 | ICLR 2026 |
| 📄 [$M^3$-Bench: Multi-Modal, Multi-Hop, Multi-Threaded Tool-Using MLLM Agent Benchmark](https://arxiv.org/abs/2511.17729) · [💻 GitHub](https://github.com/EtaYang10th/Open-M3-Bench) | 2025 | Preprint (arXiv) |
| 📄 [ComplexFuncBench: Exploring Multi-Step and Constrained Function Calling under Long-Context Scenario](https://arxiv.org/abs/2501.10132) · [💻 GitHub](https://github.com/zai-org/ComplexFuncBench) | 2025 | Preprint (arXiv) |
| 📄 [DICE-BENCH: Evaluating the Tool-Use Capabilities of Large Language Models in Multi-Round, Multi-Party Dialogues](https://doi.org/10.18653/v1/2025.findings-acl.1375) · [💻 GitHub](https://github.com/snuhcc/DICE-Bench) | 2025 | Findings of the Association for Computational Linguistics: ACL 2025 |
| 📄 [ELT-Bench: An End-to-End Benchmark for Evaluating AI Agents on ELT Pipelines](https://doi.org/10.14778/3773749.3773750) · [💻 GitHub](https://github.com/uiuc-kang-lab/ELT-Bench) | 2025 | Proceedings of the VLDB Endowment |
| 📄 [NESTFUL: A Benchmark for Evaluating LLMs on Nested Sequences of API Calls](https://doi.org/10.18653/v1/2025.emnlp-main.1702) · [💻 GitHub](https://github.com/IBM/NESTFUL) | 2025 | Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing |
| 📄 [ToolComp: A Multi-Tool Reasoning & Process Supervision Benchmark](https://arxiv.org/abs/2501.01290) · [💻 GitHub](https://github.com/vaskar-nath/toolcomp) | 2025 | Preprint (arXiv) |
| 📄 [ToolHop: A Query-Driven Benchmark for Evaluating Large Language Models in Multi-Hop Tool Use](https://doi.org/10.18653/v1/2025.acl-long.150) | 2025 | Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers) |
| 📄 [m&m's: A Benchmark to Evaluate Tool-Use for Multi-Step Multi-Modal Tasks](https://doi.org/10.1007/978-3-031-72684-2_2) · [💻 GitHub](https://github.com/RAIVNLab/mnms) | 2024 | European Conference on Computer Vision |
| 📄 [Seal-Tools: Self-instruct Tool Learning Dataset for Agent Tuning and Detailed Benchmark](https://doi.org/10.1007/978-981-97-9434-8_29) · [💻 GitHub](https://github.com/fairyshine/Seal-Tools) | 2024 | CCF International Conference on Natural Language Processing and Chinese Computing |
| 📄 [TaskBench: Benchmarking Large Language Models for Task Automation](https://doi.org/10.52202/079017-0148) · [💻 GitHub](https://github.com/microsoft/JARVIS/tree/main/taskbench) | 2024 | Advances in Neural Information Processing Systems 37 (NeurIPS 2024) |
| 📄 [ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs](https://proceedings.iclr.cc/paper_files/paper/2024/file/28e50ee5b72e90b50e7196fde8ea260e-Paper-Conference.pdf) · [💻 GitHub](https://github.com/OpenBMB/ToolBench) | 2024 | ICLR 2024 |

<a id="temporal-scale"></a>
## 📂 Temporal Scale

| Paper | Year | Publication |
| --- | --- | --- |
| 📄 [AgentLongBench: A Controllable Long Benchmark For Long-Contexts Agents via Environment Rollouts](https://arxiv.org/abs/2601.20730) · [💻 GitHub](https://github.com/euReKa025/AgentLongBench) | 2026 | Preprint (arXiv) |
| 📄 [CostBench: Evaluating Multi-Turn Cost-Optimal Planning and Adaptation in Dynamic Environments for LLM Tool-Use Agents](https://doi.org/10.18653/v1/2026.acl-long.584) · [💻 GitHub](https://github.com/JiayuJeff/CostBench) | 2026 | Proceedings of the 64th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers) |
| 📄 [DeepPlanning: Benchmarking Long-Horizon Agentic Planning with Verifiable Constraints](https://doi.org/10.18653/v1/2026.acl-long.335) · [💻 GitHub](https://github.com/QwenLM/Qwen-Agent/tree/main/benchmark/deepplanning) | 2026 | Proceedings of the 64th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers) |
| 📄 [The Tool Decathlon: Benchmarking Language Agents for Diverse, Realistic, and Long-Horizon Task Execution](https://openreview.net/forum?id=z53s5p0qhf) · [💻 GitHub](https://github.com/hkust-nlp/Toolathlon) | 2026 | ICLR 2026 |
| 📄 [TRIP-Bench: A Benchmark for Long-Horizon Interactive Agents in Real-World Scenarios](https://arxiv.org/abs/2602.01675) | 2026 | Preprint (arXiv) |
| 📄 [UltraHorizon: Benchmarking LLM-Agent Capabilities in Ultra Long-Horizon Scenarios](https://openreview.net/forum?id=qRNtMWrTvo) · [💻 GitHub](https://github.com/StarDewXXX/UltraHorizon) | 2026 | ICML 2026 |
| 📄 [HammerBench: Fine-Grained Function-Calling Evaluation in Real Mobile Assistant Scenarios](https://doi.org/10.18653/v1/2025.findings-acl.175) · [💻 GitHub](https://github.com/MadeAgents/HammerBench) | 2025 | Findings of the Association for Computational Linguistics: ACL 2025 |
| 📄 [ShortcutsBench: A Large-Scale Real-world Benchmark for API-based Agents](https://proceedings.iclr.cc/paper_files/paper/2025/file/c16a99558b0b4f6b10966ca9bdb98ade-Paper-Conference.pdf) · [💻 GitHub](https://github.com/EachSheep/ShortcutsBench) | 2025 | ICLR 2025 |

<a id="dynamic-environments"></a>
## 📂 Dynamic Environments

| Paper | Year | Publication |
| --- | --- | --- |
| 📄 [$\tau^2$-Bench: Evaluating Conversational Agents in a Dual-Control Environment](https://openreview.net/forum?id=OC2z7iSQKa) · [💻 GitHub](https://github.com/sierra-research/tau2-bench) | 2026 | ICML 2026 |
| 📄 [Benchmarking LLM Tool-Use in the Wild](https://proceedings.iclr.cc/paper_files/paper/2026/file/4fb6b4482e4e24a33a3de5b01a011eb0-Paper-Conference.pdf) · [💻 GitHub](https://github.com/yupeijei1997/WildToolBench) | 2026 | ICLR 2026 |
| 📄 [C-World: A Computer Use Agent Environment Creator](https://doi.org/10.18653/v1/2026.acl-long.2001) · [💻 GitHub](https://github.com/Ziqiao-git/C-World) | 2026 | Proceedings of the 64th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers) |
| 📄 [RealWebAssist: A Benchmark for Long-Horizon Web Assistance with Real-World Users](https://doi.org/10.1609/aaai.v40i40.40742) · [💻 GitHub](https://github.com/SCAI-JHU/RealWebAssist) | 2026 | Proceedings of the AAAI Conference on Artificial Intelligence |
| 📄 [VitaBench: Benchmarking LLM Agents with Versatile Interactive Tasks in Real-world Applications](https://proceedings.iclr.cc/paper_files/paper/2026/file/93fab021315170101c92e8330a56fbdb-Paper-Conference.pdf) · [💻 GitHub](https://github.com/meituan-longcat/vitabench) | 2026 | ICLR 2026 |
| 📄 [$\tau$-bench: A Benchmark for Tool-Agent-User Interaction in Real-World Domains](https://proceedings.iclr.cc/paper_files/paper/2025/file/1b126cc38b8638e07bef37e7b2bb72bf-Paper-Conference.pdf) · [💻 GitHub](https://github.com/sierra-research/tau-bench) | 2025 | ICLR 2025 |
| 📄 [AndroidWorld: A Dynamic Benchmarking Environment for Autonomous Agents](https://proceedings.iclr.cc/paper_files/paper/2025/file/01a83bc2f2732a58e6aa731e659e7101-Paper-Conference.pdf) · [💻 GitHub](https://github.com/google-research/android_world) | 2025 | ICLR 2025 |
| 📄 [COMPASS: Benchmarking Constrained Optimization in LLM Agents](https://arxiv.org/abs/2510.07043) | 2025 | Preprint (arXiv) |
| 📄 [MTU-Bench: A Multi-granularity Tool-Use Benchmark for Large Language Models](https://proceedings.iclr.cc/paper_files/paper/2025/file/4d13b2d99519c5415661dad44ab7edcd-Paper-Conference.pdf) · [💻 GitHub](https://github.com/MTU-Bench-Team/MTU-Bench) | 2025 | ICLR 2025 |
| 📄 [T1: A Tool-Oriented Conversational Dataset for Multi-Turn Agentic Planning](https://doi.org/10.52202/085713-3479) · [💻 GitHub](https://github.com/CapitalOne-Research/T1) | 2025 | Advances in Neural Information Processing Systems 38 (NeurIPS 2025) |
| 📄 [The BrowserGym Ecosystem for Web Agent Research](https://openreview.net/forum?id=5298fKGmv3) · [💻 GitHub](https://github.com/ServiceNow/BrowserGym) | 2025 | Trans. Mach. Learn. Res. |
| 📄 [TheAgentCompany: Benchmarking LLM Agents on Consequential Real World Tasks](https://doi.org/10.52202/085713-0315) · [💻 GitHub](https://github.com/TheAgentCompany/TheAgentCompany) | 2025 | Advances in Neural Information Processing Systems |
| 📄 [ToolSandbox: A Stateful, Conversational, Interactive Evaluation Benchmark for LLM Tool Use Capabilities](https://doi.org/10.18653/v1/2025.findings-naacl.65) · [💻 GitHub](https://github.com/apple-aiml-research/ToolSandbox) | 2025 | Findings of the Association for Computational Linguistics: NAACL 2025 |
| 📄 [Windows Agent Arena: Evaluating Multi-Modal OS Agents at Scale](https://proceedings.mlr.press/v267/bonatti25a.html) · [💻 GitHub](https://github.com/microsoft/WindowsAgentArena) | 2025 | ICML 2025 |
| 📄 [AppWorld: A Controllable World of Apps and People for Benchmarking Interactive Coding Agents](https://doi.org/10.18653/v1/2024.acl-long.850) · [💻 GitHub](https://github.com/StonyBrookNLP/appworld) | 2024 | Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers) |
| 📄 [GTA: A Benchmark for General Tool Agents](https://doi.org/10.52202/079017-2412) · [💻 GitHub](https://github.com/open-compass/GTA) | 2024 | Advances in Neural Information Processing Systems |
| 📄 [Mobile-Bench: An Evaluation Benchmark for LLM-based Mobile Agents](https://doi.org/10.18653/v1/2024.acl-long.478) · [💻 GitHub](https://github.com/XiaoMi/MobileBench) | 2024 | Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers) |
| 📄 [OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments](https://doi.org/10.52202/079017-1650) · [💻 GitHub](https://github.com/xlang-ai/OSWorld) | 2024 | Advances in Neural Information Processing Systems 37 (NeurIPS 2024) |
| 📄 [StableToolBench: Towards Stable Large-Scale Benchmarking on Tool Learning of Large Language Models](https://doi.org/10.18653/v1/2024.findings-acl.664) · [💻 GitHub](https://github.com/THUNLP-MT/StableToolBench) | 2024 | Findings of the Association for Computational Linguistics: ACL 2024 |

<a id="state-persistence-and-self-correction"></a>
## 📂 State Persistence and Self-Correction

| Paper | Year | Publication |
| --- | --- | --- |
| 📄 [ASTRA-bench: Evaluating Tool-Use Agent Reasoning and Action Planning with Personal User Context](https://arxiv.org/abs/2603.01357) · [💻 GitHub](https://github.com/apple-aiml-research/ml-astra) | 2026 | Preprint (arXiv) |
| 📄 [ColorBench: Benchmarking Mobile Agents with Graph-Structured Framework for Complex Long-Horizon Tasks](https://doi.org/10.1145/3774904.3792215) · [💻 GitHub](https://github.com/MadeAgents/ColorBench) | 2026 | Proceedings of the ACM Web Conference 2026 |
| 📄 [CRITICTOOL: Evaluating Self-Critique Capabilities of Large Language Models in Tool-Calling Error Scenarios](https://doi.org/10.18653/v1/2025.emnlp-main.1355) · [💻 GitHub](https://github.com/Shellorley0513/CriticTool) | 2025 | Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing |
| 📄 [OdysseyBench: Evaluating LLM Agents on Long-Horizon Complex Office Application Workflows](https://arxiv.org/abs/2508.09124) · [💻 GitHub](https://github.com/microsoft/OdysseyBench) | 2025 | Preprint (arXiv) |

<a id="safety-and-robustness-evaluation"></a>
## 📂 Safety and Robustness Evaluation

| Paper | Year | Publication |
| --- | --- | --- |
| 📄 [AgentDojo: A Dynamic Environment to Evaluate Prompt Injection Attacks and Defenses for LLM Agents](https://doi.org/10.52202/079017-2636) · [💻 GitHub](https://github.com/ethz-spylab/agentdojo) | 2024 | Advances in Neural Information Processing Systems |
| 📄 [RoTBench: A Multi-Level Benchmark for Evaluating the Robustness of Large Language Models in Tool Learning](https://doi.org/10.18653/v1/2024.emnlp-main.19) · [💻 GitHub](https://github.com/Junjie-Ye/RoTBench) | 2024 | Proceedings of the 2024 conference on empirical methods in natural language processing |
| 📄 [ToolSword: Unveiling Safety Issues of Large Language Models in Tool Learning Across Three Stages](https://doi.org/10.18653/v1/2024.acl-long.119) · [💻 GitHub](https://github.com/Junjie-Ye/ToolSword) | 2024 | Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers) |

<a id="related-resources"></a>
## 🔗 Related resources

[Survey paper](https://doi.org/10.1007/s10462-026-11700-9) · [All topic pages](../README.md#taxonomy) · [Suggest a resource](../CONTRIBUTING.md)
