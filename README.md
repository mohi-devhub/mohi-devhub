I work on LLM inference, evaluation and post-training, mostly measuring how serving systems actually behave and building tools around what I find.

[Portfolio](https://mohith.xyz) · [LinkedIn](https://www.linkedin.com/in/m-mohith-6b217b291/) · [X](https://x.com/MohithAchu) · [ORCID](https://orcid.org/0009-0003-2978-3045)

### Research

- **[Reload or Recompute?](https://github.com/mohi-devhub/reload-or-recompute)** ([preprint](https://doi.org/10.5281/zenodo.24026972)): a break-even rule for when a resumed conversation should reload its KV cache instead of recomputing it, tested on L4, A10 and A10G with predictions frozen in advance.
- **[Leaderboard Noise](https://github.com/mohi-devhub/leaderboard-noise)**: "deterministic" greedy decoding changed 2.0–4.6% of answers across GPUs and reversed a near-tied ranking.
- **[Grammar vs Bits](https://github.com/mohi-devhub/grammar-vs-bits)** ([preprint](https://doi.org/10.5281/zenodo.23926882)): strict grammar decoding gave no clear recovery of what 4-bit quantization loses in tool calling; the output format mattered far more.

### Post-training

- **[Pixel Miser](https://github.com/mohi-devhub/pixel-miser)** ([write-up](https://www.mohith.xyz/blog/teaching-inkling-to-stop-overthinking)): post-trained Inkling 2 Small on Tinker to stop over-thinking. Output tokens fell from 3,109 to 74 and finish rate rose from 49% to 99%.
- **Nightly** (in progress): a coding agent that retrains on its own test-verified attempts each night, with hidden-test graders red-teamed against cheating.

### Projects

- **[Kestrel](https://github.com/mohi-devhub/kestrel)**: multi-tenant GPU compute platform on Kubernetes with quotas, GPU-second metering and autoscaling.
- **[kea](https://github.com/mohi-devhub/kea)**: real-time incident root-cause engine. 1st place, OpenAI Codex Community Hackathon.
- **[AntiVibe](https://github.com/mohi-devhub/antivibe)**: Claude Code skill that explains AI-written code. 1,100+ stars, Mintlify OSS Program.
- **[SentinelLM](https://github.com/mohi-devhub/SentinelLM)**: LLM proxy with a concurrent safety-evaluation pipeline.

### Experience

- **Google Summer of Code 2026, [RUXAILAB](https://github.com/ruxailab)**: built the Focus Group Management and Analysis Module (24 merged PRs).
- **Koncepts**: Product Developer Intern, 165+ PRs to an AI EdTech platform serving 200K+ learners.
- **India Builds with Claude**: 1 of 6 presenters selected from 2,300+ applicants.

### Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-30A2FF?style=flat-square)
![Tinker](https://img.shields.io/badge/Tinker-111111?style=flat-square)
![Modal](https://img.shields.io/badge/Modal-7FEE64?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
