# Liu Minghao

AI/LLM application engineer focused on building agent systems that are
grounded, testable, and safe to operate.

I work mainly with Python, FastAPI, retrieval-augmented generation, tool
calling, evaluation pipelines, and platform automation. My projects keep
safety-critical decisions in deterministic code while using LLMs for
reasoning and explanation.

## Featured projects

### [CrossBorder AI Support Agent](https://github.com/lminghao233-tech/CrossBorder-AI-SaaS-Optimization)

A multilingual customer-support workflow for Chinese, English, and Korean
requests.

- Manager-style agent orchestration with specialized triage, retrieval, and
  action tools
- Hybrid BM25 and vector retrieval with citations and grounded-answer checks
- Risk-aware routing, prompt-injection defense, PII redaction, and
  human-in-the-loop escalation
- FastAPI service, SQLite audit trail, Docker packaging, CI, and offline
  evaluation
- 42 automated tests with 90% branch coverage; controlled agent evaluation
  passes 6/6 cases

### [OpsPreflight](https://github.com/lminghao233-tech/OpsPreflight)

An evidence-driven Terraform review agent for safer infrastructure changes.

- Deterministic policy engine for PASS, WARN, BLOCK, and REVIEW decisions
- Runbook RAG with traceable evidence and confidence-aware recommendations
- Prompt-injection defense, approval gates, immutable audit events, and
  provider abstraction
- REST API, CLI, Docker Compose demo, CI, and repeatable evaluation suites
- 59 automated tests with 96% branch coverage; policy evaluation passes 8/8
  and agent/RAG evaluation passes 5/5 cases

## Engineering principles

- Evidence over demos: claims are backed by tests, evaluation artifacts, and
  reproducible commands.
- Deterministic safety: hard controls stay outside probabilistic model output.
- Offline reproducibility: core workflows run without paid external services.
- Replaceable providers: LLM and embedding integrations sit behind explicit
  interfaces.
- Honest metrics: evaluation results describe controlled test sets, not
  production traffic.

## Stack

`Python` · `FastAPI` · `OpenAI Agents SDK` · `RAG` · `Terraform` · `SQLite` ·
`Docker` · `GitHub Actions`
