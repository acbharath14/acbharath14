# Bharath Arsikere Chandrashekar

QA Automation Architect with 15+ years in enterprise quality engineering across web, microservices, mobile apps development in regulated financial domains.

## Start Here
If you review only five repositories, review these:

1. [selenium-e2e-automation-framework](https://github.com/acbharath14/selenium-e2e-automation-framework) — Selenium WebDriver 4 + Java 17 + JUnit 5 + Allure: 15 UI journeys on Swag Labs, 5 REST Assured API tests. Jenkins pipeline green 20/20.
2. [sidekick-rag-assistant](https://github.com/acbharath14/sidekick-rag-assistant) — enterprise RAG assistant (LangChain + FAISS): pluggable document sources, cited answers, Streamlit chat UI, MCP server, retrieval evals. No API keys needed.
3. [crewai-scrum-team](https://github.com/acbharath14/crewai-scrum-team) — a multi-agent Scrum team (PO/BA/SM/Developer/SDET) on CrewAI + local Ollama that plans, builds, and validates software.
4. [enterprise-qa-automation-blueprint](https://github.com/acbharath14/enterprise-qa-automation-blueprint) — enterprise Playwright framework: BDD, DB validation, Pact contract tests, k6 performance, ZAP security. CI green, 419 passed.
5. [appium-e2e-automation-framework](https://github.com/acbharath14/appium-e2e-automation-framework) — Appium + Java 17 + JUnit 5: 15 native mobile tests on the Swag Labs app, Android emulator + iOS simulator, Allure reports. Android 15/15 green.

Read them in this order — they show the range: a proven automation framework, an enterprise knowledge system, multi-agent AI engineering, a full enterprise QA blueprint, and native mobile automation.

## AI Quality Engineering

Beyond traditional test automation, I build evaluation harnesses and generate tests with local models — no cloud model, no test run leaves your machine:

- [llm-eval-harness](https://github.com/acbharath14/llm-eval-harness) — 50 golden Q/A items, heuristic + LLM judges, drift detection (PSI), model comparison dashboard. Answers "which model should we ship?" with evidence.
- [doc-extract-eval](https://github.com/acbharath14/doc-extract-eval) — compares 5 PDF extraction engines (pypdf, pdfplumber, PyMuPDF, Tesseract, Mistral OCR) with ground-truth F1 scoring, then pipes winners through an LLM for structured business summaries.
- [ollama-junit-demo](https://github.com/acbharath14/ollama-junit-demo) — local Ollama drafts JUnit 5 unit tests for a small Java app. Drafts live in ai-generated/ until a human reviews and promotes them. Coverage via JaCoCo, execution reports via Allure.
- [ollama-jev-decision-demo](https://github.com/acbharath14/ollama-jev-decision-demo) — typed decision models via Ollama (/v1/systemone): choice, yes/no, and score questions with calibrated probabilities. Stdlib-only Python.

## Skills To Repository Map

| Skill from profile | Repository | What to check | Proof artifact |
| --- | --- | --- | --- |
| E2E web automation frameworks | selenium-e2e-automation-framework | Selenium 4 Page Objects, 15 UI journeys + 5 API tests, Jenkins CI | Jenkins pipeline green 20/20 + Allure report |
| Native mobile test automation | appium-e2e-automation-framework | Appium Page Objects, 15 tests on Android emulator + iOS simulator | Android 15/15 green; iOS 9 passed / 6 intentionally skipped |
| Enterprise QA strategy and test architecture | enterprise-qa-automation-blueprint | Playwright BDD, DB validation, Pact contract tests, k6 performance, ZAP security | CI green, 419 passed |
| Cypress E2E automation | cypress-e2e-automation-framework | Page Objects, fixtures, custom commands, UI + API specs | mochawesome-report/ + allure-results/ per run (CI template in ci/) |
| Contract testing and integration risk control | microservices-contract-and-integration-testing | Multi-service orchestration scenarios: happy-path, timeout-fallback, schema-drift. Pact consumer + provider verification, OpenAPI validation, WireMock virtualization | docs/evidence-suite.md |
| Release governance and CI/CD quality gates | cicd-quality-gates-reference-implementation | PASS, WARN, BLOCK decisions from metrics plus integration report input | docs/evidence-integration.md |
| Multi-agent AI engineering | crewai-scrum-team | Five-agent Scrum team on local Ollama: planning gates, ATDD acceptance tests, validation against the original spec | outputs/validation_report.md |
| Enterprise RAG systems | sidekick-rag-assistant | Cited answers, permission-aware retrieval, hybrid mode, retrieval evals | evals/ regression suite |
| LLM evaluation and model selection | llm-eval-harness | Golden dataset, judge agreement, drift detection, side-by-side model comparison | reports/ |
| Document AI evaluation | doc-extract-eval | Extractor comparison with ground-truth F1 scoring | reports/ |
| AI-generated unit tests (local LLM) | ollama-junit-demo | Ollama drafts JUnit 5 tests for a Java app, human review before promotion | ai-generated/ |

## Core Strengths

- **Quality architecture:** end-to-end automation strategy, CI/CD pipelines, quality gates, and release decisions grounded in test evidence
- **API and integration testing:** contract testing (Pact), service virtualization (WireMock), integration validation, REST Assured
- **AI-assisted quality:** evaluating LLM systems with evidence — golden datasets, LLM-as-judge scoring, drift detection across runs; AI-drafted Playwright and JUnit tests from local models, promoted only after human review
- **Platforms and tools:** Playwright, Selenium, Cucumber, TypeScript, Java, Python; performance testing (JMeter); mobile automation (Appium, Sauce Labs, LambdaTest)
- **Domain and team:** quality engineering across banking, financial services, credit lending/payments, and mortgage-backed securities; hands-on mentoring of junior SDETs in automation practices and code quality

## Connect

- LinkedIn: https://www.linkedin.com/in/acbharath14/
