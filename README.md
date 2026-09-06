# Hi, I'm Yudam Kim

**Applied AI & Backend Engineer** in Seoul, Korea.

I build reliable, cost-efficient LLM products — from workflow design and evaluation to backend, cloud deployment, and observability. I trace problems to the root cause, compare alternatives with evidence, and turn the result into a system that holds up in production.

## Now

Building **[InfoHelper](https://github.com/otteru/InfoHelper)** *(Jun 2026–Present)*  
Daily campus-notice agent: crawl university boards → RAG recommend by profile / interests / deadlines → email via SES. Infra and deploys with Pulumi + GitHub Actions. Personalization and auto-generated crawl rules are in progress.

## Selected work

### [Ling-Level](https://www.linglevel.com/) · AI Engineer
*Software Maestro 16th (MSIT) · Apr 2025–Nov 2025 · 3-person team*

English-learning app that rewrites content across CEFR levels. ~1,000 registered users, 700 peak MAU.

- Cut LLM cost per book from **$17.59 to $0.17 (99%)** after Playground vs API quality/cost diverged; re-benchmarked Bedrock models on the live API
- Designed a **9-level LangGraph** workflow with context preservation, LLM-as-judge, and auto-retry
- Added schema repair and language validation after malformed JSON / off-language outputs broke downstream jobs
- Daily job generates **8 articles** with no manual steps
- Replaced Datadog after container CPU hit 76–170%; shipped a LangChain wrapper for per-call / per-book cost and moved prompts to Langfuse so edits do not require an image rebuild
- Moved prompt-injection checks from Bedrock Guardrails to NeMo after per-token rail cost became the bottleneck; halt the workflow on detection
- Infra: S3 → Lambda → ECS Fargate batch → S3, provisioned with Pulumi

Code: [leveling pipeline](https://github.com/SWM16-ASAP/ai) · [article factory](https://github.com/SWM16-ASAP/article)

## Stack

**Applied AI & LLM** — LangGraph, LangChain, Langfuse, NeMo Guardrails, AWS Bedrock  
**Backend** — Python, FastAPI, Pydantic  
**Cloud & infra** — AWS (ECS Fargate, Lambda, S3), Docker, Pulumi

## Highlights

- **Outstanding Fellow**, AI·SW Maestro 16th / UC Berkeley SCET *(2025–Feb 2026)*
- **1st Place**, UC Berkeley SCET IR Pitch *(Team Lead)*
- **Grand Prize**, Seoul Big Data Campus Competition *(Team Lead, 2023)*
- C Programming Tutor, Konkuk University *(2023)*
- **B.E. in Computer Engineering**, Konkuk University *(Mar 2022–Expected Feb 2028)* · GPA 4.03/4.5 (Major 4.22) · Dean’s List (2 semesters)

## Contact

[linglevel.com](https://linglevel.com) · [Blog](https://otteru.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/yudam-kim-a23ab8283/) · [damdori3@gmail.com](mailto:damdori3@gmail.com)
