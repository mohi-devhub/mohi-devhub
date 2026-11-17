<table>
<tr>
<td>

**LLM inference & evaluation.** I measure and build the systems that serve LLMs.

</td>
<td>

[Portfolio](https://mohith.xyz) · [LinkedIn](https://www.linkedin.com/in/m-mohith-6b217b291/) · [X](https://x.com/MohithAchu) · [ORCID](https://orcid.org/0009-0003-2978-3045)

</td>
</tr>
</table>

Final-year CS student and independent researcher, graduating May 2027. I work on LLM serving, eval reliability and post-training, and I like results I can measure and reproduce.

### Research

- **[Reload or Recompute?](https://github.com/mohi-devhub/reload-or-recompute)**: when should a resumed conversation reload its KV cache instead of recomputing it? A break-even rule with predictions frozen before testing on L4, A10 and A10G · [preprint](https://doi.org/10.5281/zenodo.24026972)
- **[Leaderboard Noise](https://github.com/mohi-devhub/leaderboard-noise)**: "deterministic" greedy decoding changed 2.0–4.6% of answers across GPUs and flipped a near-tied ranking. Batch-invariant decoding fixed it at a 32–60% throughput cost
- **[Grammar vs Bits](https://github.com/mohi-devhub/grammar-vs-bits)**: does strict grammar decoding recover what 4-bit quantization loses in small-model tool calling? Not really. The output format mattered far more · [preprint](https://doi.org/10.5281/zenodo.23926882)

### Post-training

- **[Pixel Miser](https://github.com/mohi-devhub/pixel-miser)**: post-trained Thinking Machines' Inkling 2 Small on Tinker to stop over-thinking. Output tokens 3,109 to 74, finish rate 49% to 99%, faithful drawings 40% to 68% · [write-up](https://www.mohith.xyz/blog/teaching-inkling-to-stop-overthinking)
- **Nightly** *(in progress)*: a coding agent that retrains on its own test-verified attempts each night, with hidden-test graders red-teamed against cheating patches

### Projects

- **[Kestrel](https://github.com/mohi-devhub/kestrel)**: multi-tenant GPU compute platform on Kubernetes with Kueue admission, per-tenant quotas, pluggable placement policies, GPU-second metering and a scale-to-zero autoscaler
- **[kea](https://github.com/mohi-devhub/kea)**: real-time incident root-cause engine. A deterministic engine ranks causes over a live service graph and the LLM only explains · 🏆 1st place, OpenAI Codex Community Hackathon
- **[AntiVibe](https://github.com/mohi-devhub/antivibe)**: Claude Code skill that explains AI-written code · 1,100+ stars, [Mintlify OSS Program](https://mintlify.com)
- **[SentinelLM](https://github.com/mohi-devhub/SentinelLM)**: open-source LLM proxy with a 7-stage concurrent safety evaluation pipeline

### Experience

- **GSoC 2026, [RUXAILAB](https://github.com/ruxailab)**: built the Focus Group Management and Analysis Module (LiveKit sessions, NLP-assisted thematic analysis) · 30 PRs, 24 merged
- **Product Developer Intern, [Koncepts](https://koncepts.school/)**: 165+ PRs to an AI EdTech platform serving 200K+ learners
- **1 of 6 presenters** at India Builds with Claude (Anthropic × Razorpay), from 2,300+ applicants
- Founding Chair, IEEE Oceanic Engineering Society Student Chapter @ CVV (2024–2026)

### Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-30A2FF?style=flat-square)
![Tinker](https://img.shields.io/badge/Tinker-111111?style=flat-square)
![Modal](https://img.shields.io/badge/Modal-7FEE64?style=flat-square&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
