# 🔐 AI and Cybersecurity

A free, self-updating hub on **both sides of AI security**: using AI to defend systems, and securing AI systems themselves (LLMs, agents, models and data). Frameworks, platforms, research and learning material.
Research and code lists refresh every day from arXiv and GitHub. Curated resources are hand-picked and free.

<!-- STAMP:START -->
_Last refreshed: 2026-10-08 15:39 UTC_
<!-- STAMP:END -->

## Contents
- [Latest research](#-latest-research)
- [Frameworks everyone uses](#-frameworks-everyone-uses)
- [Platforms and tools](#-platforms-and-tools)
- [Papers that shaped the field](#-papers-that-shaped-the-field)
- [AI for security (detection, SOC, threat intel)](#-ai-for-security-detection-soc-threat-intel)
- [Security of AI (red teaming, prompt injection, guardrails)](#-security-of-ai-red-teaming-prompt-injection-guardrails)
- [Open-source AI security platforms and tools](#-open-source-ai-security-platforms-and-tools)
- [Free learning resources](#-free-learning-resources)
- [How this repo stays fresh](#-how-this-repo-stays-fresh)

## 📄 Latest research
Newest papers on arXiv for this topic, newest first.

<!-- ARXIV:START -->
| Date | Paper | Authors |
|---|---|---|
| 2026-10-07 | [SLDR: Defending Against Malicious Fine-tuning via Selective Layers Recovery and Dynamic Routing](https://arxiv.org/abs/2610.10345) | Hui Zhang et al. |
| 2026-10-07 | [On the Reliability of LLM-Based Vulnerability Patching Benchmarks](https://arxiv.org/abs/2610.10150) | Dang K Le et al. |
| 2026-10-07 | [Constrained-Action AI Remediation for SIEM/XDR via a NeMo-Guardrails Proxy](https://arxiv.org/abs/2610.09906) | Georgios Koutidis et al. |
| 2026-10-07 | [Formal Runtime Verification for Tool-Using LLM Agents: An Offline Same-Benchmark Study on AgentDojo and STAC](https://arxiv.org/abs/2610.09793) | Nikolaos Kekatos et al. |
| 2026-10-07 | [Pareto-optimal quantum kernel selection for unsupervised anomaly detection on real malware beaconing data](https://arxiv.org/abs/2610.09717) | Boaz Micah et al. |
| 2026-10-07 | [Correct Answers, Unsupported Findings: Evidence Binding in Forensic Reconstruction of LLM Agent Logs](https://arxiv.org/abs/2610.09581) | Taehyeon Yun et al. |
| 2026-10-07 | [MARS: Malware Analysis with Rule-Based Scoring of LLM Claims](https://arxiv.org/abs/2610.09553) | Hyeongjun Choi |
| 2026-10-07 | [Constitution-Guided Watermarking](https://arxiv.org/abs/2610.09552) | Toluwani Aremu et al. |
<!-- ARXIV:END -->

## 🗺️ Frameworks everyone uses

| Framework | What it gives you |
|---|---|
| [OWASP Top 10 for LLM Applications](https://genai.owasp.org/) | The top risks for LLM apps, with mitigations |
| [MITRE ATLAS](https://atlas.mitre.org/) | Attack tactics and techniques against AI systems, with case studies |
| [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework) | Govern, map, measure and manage AI risk |
| [Google Secure AI Framework (SAIF)](https://saif.google/) | Google's controls for securing AI |
| [Microsoft AI Red Team guidance](https://learn.microsoft.com/security/ai-red-team/) | How Microsoft red-teams AI systems |

## 🧰 Platforms and tools

| Tool | Use |
|---|---|
| [NVIDIA garak](https://github.com/NVIDIA/garak) | LLM vulnerability scanner |
| [PyRIT (Microsoft)](https://github.com/Azure/PyRIT) | Automated red teaming for generative AI |
| [Adversarial Robustness Toolbox](https://github.com/Trusted-AI/adversarial-robustness-toolbox) | Attacks and defenses for ML models |
| [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) | Programmable guardrails for LLM apps |

## 📄 Papers that shaped the field

- [Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572) (2014)
- [Extracting Training Data from Large Language Models](https://arxiv.org/abs/2012.07805) (2020)
- [Indirect Prompt Injection: Not What You've Signed Up For](https://arxiv.org/abs/2302.12173) (2023)
- [Poisoning Web-Scale Training Datasets is Practical](https://arxiv.org/abs/2302.10149) (2023)
- [Universal and Transferable Adversarial Attacks on Aligned Language Models](https://arxiv.org/abs/2307.15043) (2023)

## 🛡️ AI for security (detection, SOC, threat intel)
Most-starred GitHub repositories updated in the last 12 months.

<!-- DEF:START -->
| Repository | What it is | Language | Stars | Last update |
|---|---|---|---|---|
| [beenuar/AiSOC](https://github.com/beenuar/AiSOC) | Open-source AI Security Operations Center: alert fusion, LLM-agent triage, MITRE ATT&CK investigation, and a replayable decision ledger for  | Python | 2,390 | 2026-10-08 |
| [uber/ADR](https://github.com/uber/ADR) | ADR secures enterprise AI agents through observability, security benchmarking, and threat detection. Deployed at Uber. | Python | 1,947 | 2026-10-08 |
| [JoasASantos/NeuroSploit](https://github.com/JoasASantos/NeuroSploit) | NeuroSploit is an advanced, AI-powered penetration testing framework designed to automate and augment various aspects of offensive security  | Rust | 1,423 | 2026-10-06 |
| [FunnyWolf/agentic-soc-platform](https://github.com/FunnyWolf/agentic-soc-platform) | Agentic SOC Platform: A powerful, flexible, open-source, and agent-centric automated security operations platform (AI SOC) | Python | 1,204 | 2026-09-29 |
| [Western-OC2-Lab/Intrusion-Detection-System-Using-Machine-Learning](https://github.com/Western-OC2-Lab/Intrusion-Detection-System-Using-Machine-Learning) | Code for IDS-ML: intrusion detection system development using machine learning algorithms (Decision tree, random forest, extra trees, XGBoos | Jupyter Notebook | 598 | 2026-04-01 |
| [Masriyan/Claude-Code-CyberSecurity-Skill](https://github.com/Masriyan/Claude-Code-CyberSecurity-Skill) | 22 production-quality Claude Code Skills for cybersecurity professionals — covering offensive security, defensive operations, reverse engine | Python | 468 | 2026-09-07 |
<!-- DEF:END -->

## 🧨 Security of AI (red teaming, prompt injection, guardrails)
Most-starred GitHub repositories updated in the last 12 months.

<!-- SAFE:START -->
| Repository | What it is | Language | Stars | Last update |
|---|---|---|---|---|
| [BerriAI/litellm](https://github.com/BerriAI/litellm) | The fastest, litest AI Gateway. Rust core with Python SDK. Call 100+ LLM APIs in OpenAI (or native) format with cost tracking, guardrails, l | Python | 60,371 | 2026-10-08 |
| [promptfoo/promptfoo](https://github.com/promptfoo/promptfoo) | Test your prompts, agents, and RAGs. Red teaming/pentesting/vulnerability scanning for AI. Compare performance of GPT, Claude, Gemini, DeepS | TypeScript | 25,816 | 2026-10-08 |
| [NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector) | Security scanner for AI agent skills. Detect vulnerabilities, malicious patterns, security risks, prompt injection, data exfiltration, and s | Python | 19,692 | 2026-10-08 |
| [Portkey-AI/gateway](https://github.com/Portkey-AI/gateway) | A blazing fast AI Gateway with integrated guardrails. Route to 1,600+ LLMs, 50+ AI Guardrails with 1 fast & friendly API. | TypeScript | 13,148 | 2026-05-25 |
| [LouisShark/chatgpt_system_prompt](https://github.com/LouisShark/chatgpt_system_prompt) | A collection of GPT system prompts and various prompt injection/leaking knowledge. | HTML | 10,801 | 2026-10-08 |
| [BoundaryML/baml](https://github.com/BoundaryML/baml) | The programming language for agents | Rust | 9,385 | 2026-10-07 |
<!-- SAFE:END -->

## 🧰 Open-source AI security platforms and tools
Most-starred GitHub repositories updated in the last 12 months.

<!-- PLAT:START -->
| Repository | What it is | Language | Stars | Last update |
|---|---|---|---|---|
| [NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector) | Security scanner for AI agent skills. Detect vulnerabilities, malicious patterns, security risks, prompt injection, data exfiltration, and s | Python | 19,692 | 2026-10-08 |
| [NVIDIA/garak](https://github.com/NVIDIA/garak) | the LLM vulnerability scanner | Python | 9,501 | 2026-10-07 |
| [We5ter/Scanners-Box](https://github.com/We5ter/Scanners-Box) | The Ultimate Open-Source Security Arsenal for Hackers, Enterprises, and AI Agents——面向极客、企业与 AI 智能体的全域开源网络安全工具矩阵 |  | 9,088 | 2026-09-28 |
| [Tencent/AI-Infra-Guard](https://github.com/Tencent/AI-Infra-Guard) | A full-stack AI Red Teaming platform securing AI ecosystems via Agent Scan, Skills Scan, MCP scan, AI Infra scan and LLM jailbreak evaluatio | Python | 6,789 | 2026-10-08 |
| [Trusted-AI/adversarial-robustness-toolbox](https://github.com/Trusted-AI/adversarial-robustness-toolbox) | Adversarial Robustness Toolbox (ART) - Python Library for Machine Learning Security - Evasion, Poisoning, Extraction, Inference - Red and Bl | Python | 6,262 | 2026-10-08 |
| [snyk/agent-scan](https://github.com/snyk/agent-scan) | Security scanner for AI agents, MCP servers and agent skills. | Python | 3,125 | 2026-10-06 |
<!-- PLAT:END -->

## 📚 Free learning resources

| Resource | Why it's useful |
|---|---|
| [OWASP GenAI Security Project](https://genai.owasp.org/) | Free guides, checklists and the LLM Top 10 |
| [MITRE ATLAS](https://atlas.mitre.org/) | Free knowledge base of attacks on AI |
| [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework) | The baseline security framework |
| [Microsoft Learn: security](https://learn.microsoft.com/training/browse/?subjects=security) | Free security learning paths |
| [Google Cybersecurity resources](https://cloud.google.com/security/resources) | Free reports and guides |

## 🔄 How this repo stays fresh
A GitHub Action runs every day. It queries the public arXiv API for new papers and the GitHub search API for active, popular repositories, then rewrites the lists above. The code is in [`scripts/hub_refresh.py`](scripts/hub_refresh.py) and the search terms are in [`hub.json`](hub.json).

Inclusion in a list is automatic and is not an endorsement. Check each project's license before reuse.

---
Curated by [Mohammad Alrashed](https://github.com/DatariusAI). Part of a series of free AI hubs: see the [profile page](https://github.com/DatariusAI) for industry, cloud and mathematics hubs. Contributions welcome by pull request.
