# 🛡️ Safety and Execution Control

[![Back to collection](https://img.shields.io/badge/←_Collection-Awesome_Multi--Tool_Agents-f43f5e?style=flat)](../README.md)
![Indexed works](https://img.shields.io/badge/Indexed_works-30-f43f5e?style=flat)

Reliability, authorization, concurrency correctness, and security across dependent tool calls and shared state.

**Survey correspondence:** Section 5. **Indexed works:** 30.

The initial entries follow the [published survey corpus](../data/README.md), with a literature cutoff of **26 July 2026**. Years and publication status follow that snapshot. Cross-cutting works may appear on more than one topic page.

Reliability addresses execution failures; safety addresses harmful outcomes; security addresses adversarial compromise; authorization determines permitted actions; concurrency correctness concerns shared-state consistency.

<a id="overview"></a>
## 📂 Overview

| Paper | Year | Publication |
| --- | --- | --- |
| 📄 [A Survey on Agentic Security: Applications, Threats and Defenses](https://openreview.net/submissions?venue=ICLR.cc%2F2026%2FWorkshop%2FAIWILD) · [💻 GitHub](https://github.com/kagnlp/Awesome-Agentic-Security) | 2026 | ICLR 2026 Workshop on Agents in the Wild: Safety, Security, and Beyond (AIWILD) |
| 📄 [The Emerged Security and Privacy of LLM Agent: A Survey with Case Studies](https://doi.org/10.1145/3773080) | 2026 | ACM Computing Surveys |
| 📄 [Design Patterns for Securing LLM Agents against Prompt Injections](https://arxiv.org/abs/2506.08837) · [💻 GitHub](https://github.com/ReversecLabs/design-patterns-for-securing-llm-agents-code-samples) | 2025 | Preprint (arXiv) |
| 📄 [Prompt Flow Integrity to Prevent Privilege Escalation in LLM Agents](https://arxiv.org/abs/2503.15547) · [💻 GitHub](https://github.com/compsec-snu/pfi) | 2025 | Preprint (arXiv) |
| 📄 [AgentDojo: A Dynamic Environment to Evaluate Prompt Injection Attacks and Defenses for LLM Agents](https://doi.org/10.52202/079017-2636) · [💻 GitHub](https://github.com/ethz-spylab/agentdojo) | 2024 | Advances in Neural Information Processing Systems |
| 📄 [Identifying the Risks of LM Agents with an LM-Emulated Sandbox](https://proceedings.iclr.cc/paper_files/paper/2024/file/7274ed909a312d4d869cc328ad1c5f04-Paper-Conference.pdf) · [💻 GitHub](https://github.com/ryoungj/ToolEmu) | 2024 | ICLR 2024 |
| 📄 [Not What You've Signed Up For: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection](https://doi.org/10.1145/3605764.3623985) · [💻 GitHub](https://github.com/greshake/llm-security) | 2023 | Proceedings of the 16th ACM workshop on artificial intelligence and security |

<a id="risks-in-long-horizon-tool-chains"></a>
## 📂 Risks in Long-Horizon Tool Chains

| Paper | Year | Publication |
| --- | --- | --- |
| 📄 [AgentDoG: A Diagnostic Guardrail Framework for AI Agent Safety and Security](https://arxiv.org/abs/2601.18491) · [💻 GitHub](https://github.com/AI45Lab/AgentDoG) | 2026 | Preprint (arXiv) |
| 📄 [Les Dissonances: Cross-Tool Harvesting and Polluting in Pool-of-Tools Empowered LLM Agents](https://doi.org/10.14722/ndss.2026.240577) · [💻 GitHub](https://github.com/systemsecurity-uiuc/Chord) | 2026 | 33rd Annual Network and Distributed System Security Symposium, NDSS 2026 |
| 📄 [Think Twice Before You Act: Enhancing Agent Behavioral Safety with Thought Correction](https://jiangchangyue.github.io/publications/) · [💻 GitHub](https://github.com/WhitzardAgent/Thought-Aligner) | 2026 | ICML 2026 |
| 📄 [Advancing tool-augmented large language models via meta-verification and reflection learning](https://doi.org/10.1145/3711896.3736835) · [💻 GitHub](https://github.com/zhymma/Tool-MVR) | 2025 | Proceedings of the 31st ACM SIGKDD Conference on Knowledge Discovery and Data Mining V. 2 |
| 📄 [Agent Safety Alignment via Reinforcement Learning](https://arxiv.org/abs/2507.08270) | 2025 | Preprint (arXiv) |
| 📄 [Butterfly Effects in Toolchains: A Comprehensive Analysis of Failed Parameter Filling in LLM Tool-Agent Systems](https://doi.org/10.18653/v1/2025.findings-emnlp.907) · [💻 GitHub](https://github.com/xQianQ/toolagent-parameter-failure) | 2025 | Findings of the Association for Computational Linguistics: EMNLP 2025 |
| 📄 [Deep Research Brings Deeper Harm](https://arxiv.org/abs/2510.11851) · [💻 GitHub](https://github.com/chenxshuo/DeeperHarm) | 2025 | Preprint (arXiv) |
| 📄 [Memory Injection Attacks on LLM Agents via Query-Only Interaction](https://doi.org/10.52202/085713-1554) · [💻 GitHub](https://github.com/dsh3n77/MINJA) | 2025 | Advances in Neural Information Processing Systems |
| 📄 [ToolReflection: Improving Large Language Models for Real-World API Calls with Self-Generated Data](https://doi.org/10.18653/v1/2025.realm-1.14) · [💻 GitHub](https://github.com/polgrisha/ToolReflection) | 2025 | Proceedings of the 1st Workshop for Research on Agent Language Models (REALM 2025) |
| 📄 [Language Agent Tree Search Unifies Reasoning, Acting, and Planning in Language Models](https://proceedings.mlr.press/v235/zhou24r.html) · [💻 GitHub](https://github.com/andyz245/LanguageAgentTreeSearch) | 2024 | ICML 2024 |
| 📄 [Making Language Models Better Tool Learners with Execution Feedback](https://doi.org/10.18653/v1/2024.naacl-long.195) · [💻 GitHub](https://github.com/zjunlp/TRICE) | 2024 | Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies (Volume 1: Long Papers) |
| 📄 [Reflexion: language agents with verbal reinforcement learning](https://doi.org/10.52202/075280-0377) · [💻 GitHub](https://github.com/noahshinn/reflexion) | 2023 | Advances in Neural Information Processing Systems 36 (NeurIPS 2023) |

<a id="risks-in-parallel-execution"></a>
## 📂 Risks in Parallel Execution

| Paper | Year | Publication |
| --- | --- | --- |
| 📄 [Atomix: Timely, Transactional Tool Use for Reliable Agentic Workflows](https://arxiv.org/abs/2602.14849) · [💻 GitHub](https://github.com/mpi-dsg/atomix) | 2026 | Preprint (arXiv) |
| 📄 [Rethinking Stateful Tool Use in Multi-Turn Dialogues: Benchmarks and Challenges](https://doi.org/10.18653/v1/2025.findings-acl.284) | 2025 | Findings of the Association for Computational Linguistics: ACL 2025 |
| 📄 [SagaLLM: Context Management, Validation, and Transaction Guarantees for Multi-Agent LLM Planning](https://doi.org/10.14778/3750601.3750611) · [💻 GitHub](https://github.com/genglongling/SagaLLM) | 2025 | Proceedings of the VLDB Endowment |

<a id="risks-in-parallel-execution--pre-execution-controls"></a>
## 📂 Risks in Parallel Execution / Pre-execution Controls

| Paper | Year | Publication |
| --- | --- | --- |
| 📄 [AgentSpec: Customizable Runtime Enforcement for Safe and Reliable LLM Agents](https://doi.org/10.1145/3744916.3764546) · [💻 GitHub](https://github.com/haoyuwang99/AgentSpec) | 2026 | Proceedings of the 48th IEEE/ACM International Conference on Software Engineering |
| 📄 [Autonomous Action Runtime Management (AARM): A System Specification for Securing AI-Driven Actions at Runtime](https://arxiv.org/abs/2602.09433) · [💻 GitHub](https://github.com/herman-prod/aarm) | 2026 | Preprint (arXiv) |
| 📄 [World Modelling Improves Language Model Agents](https://arxiv.org/abs/2506.02918) | 2025 | Preprint (arXiv) |

<a id="risks-in-parallel-execution--in-execution-transaction-management"></a>
## 📂 Risks in Parallel Execution / In-execution Transaction Management

| Paper | Year | Publication |
| --- | --- | --- |
| 📄 [Generator-Assistant Stepwise Rollback Framework for Large Language Model Agent](https://doi.org/10.18653/v1/2025.emnlp-main.892) · [💻 GitHub](https://github.com/wisper12933/GA-Rollback) | 2025 | Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing |

<a id="risks-in-parallel-execution--post-execution-verification"></a>
## 📂 Risks in Parallel Execution / Post-execution Verification

| Paper | Year | Publication |
| --- | --- | --- |
| 📄 [Training Verifier to Assessing Complex Real-World Tool-Use Trajectories](https://doi.org/10.18653/v1/2026.findings-acl.1647) · [💻 GitHub](https://github.com/Aurora-slz/Tool-Verifier) | 2026 | Findings of the Association for Computational Linguistics: ACL 2026 |
| 📄 [Divide-Verify-Refine: Can LLMs Self-align with Complex Instructions?](https://doi.org/10.18653/v1/2025.findings-acl.709) · [💻 GitHub](https://github.com/Zood123/DVR_ACL25) | 2025 | Findings of the Association for Computational Linguistics: ACL 2025 |
| 📄 [VerifiAgent: a Unified Verification Agent in Language Model Reasoning](https://doi.org/10.18653/v1/2025.findings-emnlp.891) · [💻 GitHub](https://github.com/Jiuzhouh/VerifiAgent) | 2025 | Findings of the Association for Computational Linguistics: EMNLP 2025 |
| 📄 [CRITIC: Large Language Models Can Self-Correct with Tool-Interactive Critiquing](https://openreview.net/forum?id=Sx038qxjek) · [💻 GitHub](https://github.com/microsoft/ProphetNet/tree/master/CRITIC) | 2024 | ICLR 2024 |

<a id="related-resources"></a>
## 🔗 Related resources

[Survey paper](https://doi.org/10.1007/s10462-026-11700-9) · [All topic pages](../README.md#taxonomy) · [Suggest a resource](../CONTRIBUTING.md)
