# 🔐 AI and Cybersecurity

A free, self-updating hub on **both sides of AI security**: using AI to defend systems, and securing AI systems themselves (LLMs, agents, models and data). Frameworks, platforms, research and learning material.
Research and code lists refresh every day from arXiv and GitHub. Curated resources are hand-picked and free.

<!-- STAMP:START -->
_Lists fill in after the first daily refresh._
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
_Loading on first refresh._
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
_Loading on first refresh._
<!-- DEF:END -->

## 🧨 Security of AI (red teaming, prompt injection, guardrails)
Most-starred GitHub repositories updated in the last 12 months.

<!-- SAFE:START -->
_Loading on first refresh._
<!-- SAFE:END -->

## 🧰 Open-source AI security platforms and tools
Most-starred GitHub repositories updated in the last 12 months.

<!-- PLAT:START -->
_Loading on first refresh._
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
