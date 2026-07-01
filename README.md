# Joël M. — QA Automation & AI Engineering

<div align="center">

[![QA Automation](https://img.shields.io/badge/QA%20Automation-Expert-4A90D9?style=flat-square&logo=playwright&logoColor=white)](https://github.com/JoelMaMu/QA-Automation-Engineer)
[![AI Engineering](https://img.shields.io/badge/AI%20Engineering-Building-10B981?style=flat-square&logo=openai&logoColor=white)](https://github.com/JoelMaMu/Compliance_Ai)
[![LangGraph](https://img.shields.io/badge/LangGraph-Multi--Agent-7C3AED?style=flat-square)](https://github.com/JoelMaMu/Compliance_Ai)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)]()
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)]()

</div>

---

## About

QA Automation Engineer with solid experience building E2E, API, and performance test suites, now transitioning into AI Engineering.

I bring engineering rigour into AI system design: traceability, evaluation, human oversight, and test discipline applied to multi-agent pipelines. This combination is still rare in the field, and it shows in the way I approach production AI systems.

Currently building multi-agent pipelines, RAG architectures, and security automation tools.

---

## Featured Projects

### AI Engineering

| Project | Stack | What it does |
|---------|-------|-------------|
| [**QA Agents for OWASP WebGoat**](https://github.com/JoelMaMu/QA_Ai_Agents) | LangGraph · Claude · Playwright · CVSS v3.1 | Multi-agent pipeline that automates the full security QA lifecycle: generates Gherkin requirements per vulnerability class, scores each module with a CVSS v3.1 risk report, and produces Playwright test skeletons. A human approval gate controls what reaches the executable test suite. |
| [**Compliance AI**](https://github.com/JoelMaMu/Compliance_Ai) | LangGraph · RAG · Mistral 7B · Qdrant · PostgreSQL | Multi-agent system that analyses internal documents against regulatory corpora (DORA, GDPR, AI Act, Basel IV), flags non-compliance, routes uncertain findings to human review, and generates a full traceable audit report. |
| [**AI Agent**](https://github.com/JoelMaMu/Ai_agent) | LangGraph · Claude Sonnet · ReAct | Conversational CLI agent with tool-use via LangGraph's ReAct architecture and streaming responses. |

### QA Automation

| Project | Stack | What it does |
|---------|-------|-------------|
| [**QA Automation Portfolio**](https://github.com/JoelMaMu/QA-Automation-Engineer) | Playwright · TypeScript · Cucumber.js · k6 · Docker | E2E, API, BDD and performance test suites for a banking dashboard covering authentication, accounts, transfers, and KYC, with UI/database cross-checks and CI integration. |

---

## Stack

**AI & Agents**
`LangGraph` `LangChain` `RAG` `Qdrant` `Ollama / Mistral 7B` `Claude (Anthropic)` `RAGAS` `Python`

**Security & Testing**
`Playwright` `TypeScript` `Cucumber.js` `Gherkin` `Selenium` `k6` `pytest` `Allure` `Axios` `CVSS v3.1`

**Infrastructure**
`PostgreSQL` `Docker / docker-compose` `GitHub Actions` `structlog`

---

## Approach

Coming from QA, I design AI systems the same way I design test suites.

Every agent decision is traceable: each step logs its reasoning, inputs, and model output before handing off to the next stage. Human oversight is built into the pipeline, not added as an afterthought. In the QA Agents project for instance, no generated test file can reach the executable suite without an explicit approval flag, even when the full pipeline runs successfully. And when a system has known limitations, I document them in the code rather than hide them behind optimistic demos.

---

<div align="center">

![GitHub stats](https://github-readme-stats.vercel.app/api?username=JoelMaMu&show_icons=true&theme=default&hide_border=true&count_private=true)

</div>
