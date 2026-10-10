# Liu Minghao / 刘明浩

**AI / LLM Application Engineer**

我专注于构建有证据、可测试、能够安全执行的 Agent 系统。主要使用
Python、FastAPI、RAG、工具调用、评测流水线和平台自动化；让确定性代码负责
高风险决策，让模型负责推理、协作与解释。

I build grounded, testable agent systems with explicit safety boundaries.
Deterministic code owns high-risk decisions; LLMs assist with reasoning,
orchestration, and explanation.

**[Personal portfolio / 个人作品集](https://lminghao233-tech.github.io)**

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
