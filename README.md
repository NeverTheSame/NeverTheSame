# 💫 About Me:
I build agentic LLM systems where autonomy is bounded by structure, not prompt etiquette — human-approval gates that are runtime interrupts, redaction that fails closed, invariants enforced by tests rather than written in comments. SRE roots: I still measure LLM systems like production infrastructure (recall floors, false-positive rates, p99s).<br>
By day I lead AI automation for Security & Compliance — incident resolution went from 30 days to 10 through RAG and automation. The repos below are the public half of that thinking.

# 🤖 Currently shipping (all public, all measured):
- 🔒 [**Hider**](https://github.com/NeverTheSame/Hider) — tiered redaction gateway for log bundles on their way to an LLM provider. Presidio patterns → local NER over the residue → an OpenAI-compatible proxy that refuses degraded requests unforwarded. 99.9% recall on shaped identifiers, 0.0% false-redactions, 130 tests.
- 🧠 [**llm-intelligence-layer**](https://github.com/NeverTheSame/llm-intelligence-layer) — multi-agent runtime with a real advisory/acting split: read traffic never constructs the tool graph; acting turns run plan → hold → tools → publish with human-approval holds as durable graph interrupts.
- 🛡️ [**AIssist**](https://github.com/NeverTheSame/AIssist) — production incident summarizer (Kusto → Azure OpenAI → DevOps) with a tiered PII guard at the client chokepoint, post-rehydration output validation, provider-tier data classification, and a PR-template security review teams complete themselves.
- ⚖️ [**Arbiter**](https://github.com/NeverTheSame/Arbiter) — fuses two security vendors' findings and ranks by blast radius in your estate; no suppression passes without a deterministic six-rule check the model cannot argue with.
- ✍️ [**beops.site**](https://beops.site) — writing on applied AI for operations: proxies, microbatching, evals, and what building these systems taught me the hard way.

# 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![LangGraph](https://img.shields.io/badge/langgraph-%23181717.svg?style=for-the-badge&logo=langchain&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) ![spaCy](https://img.shields.io/badge/spaCy-09A3D5.svg?style=for-the-badge) ![Presidio](https://img.shields.io/badge/MS%20Presidio-5C2D91?style=for-the-badge) ![OpenAI](https://img.shields.io/badge/openai-412991?style=for-the-badge&logo=openai&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white) ![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![GCP](https://img.shields.io/badge/GCP-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white) ![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white) ![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white) ![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE?style=for-the-badge&logo=powershell&logoColor=white) ![Bash](https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5?style=for-the-badge&logo=githubactions&logoColor=white)

# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api/top-langs/?username=NeverTheSame&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

---
[![](https://visitcount.itsvg.in/api?id=NeverTheSame&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
