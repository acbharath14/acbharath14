# Bharath Arsikere Chandrashekar

QA Automation Architect with 15+ years in enterprise quality engineering across web, microservices, and mobile app development in regulated financial domains.

## Start Here
If you review only five repositories, review these:

1. [selenium-e2e-automation-framework](https://github.com/acbharath14/selenium-e2e-automation-framework): Selenium WebDriver 4 + Java 17 + JUnit 5 + Allure: 15 UI journeys on Swag Labs, 5 REST Assured API tests, with all 20 tests on Jenkins.
2. [enterprise-qa-automation-blueprint](https://github.com/acbharath14/enterprise-qa-automation-blueprint): Enterprise Playwright framework: BDD, DB validation, Pact contract tests, k6 performance, ZAP security, with 419 tests running in CI.
3. [appium-e2e-automation-framework](https://github.com/acbharath14/appium-e2e-automation-framework): Appium + Java 17 + JUnit 5: 15 native mobile tests on the Swag Labs app, Android emulator + iOS simulator, Allure reports, with 15 Android tests.
4. [karate-bdd-api-testing](https://github.com/acbharath14/karate-bdd-api-testing): Karate + Java 17 + JUnit 5: BDD API tests against the ReqRes API, 11 scenarios across 4 feature files.
5. [cypress-e2e-automation-framework](https://github.com/acbharath14/cypress-e2e-automation-framework): Cypress + JavaScript: Page Objects, fixtures, custom commands, UI + API specs, mochawesome and Allure reports.

Read in this order, they cover five areas: a proven automation framework, a full enterprise QA blueprint, native mobile automation, BDD API testing, and Cypress E2E automation.

## AI Quality Engineering

Beyond traditional test automation, this work covers AI systems, evaluation harnesses, and test generation with local models. Everything runs locally: no cloud model is called, and no test run leaves your machine:

- [sidekick-rag-assistant](https://github.com/acbharath14/sidekick-rag-assistant): enterprise RAG assistant (LangChain + FAISS): pluggable document sources, cited answers, React chat UI, MCP server, retrieval evals. No API keys needed.
- [crewai-scrum-team](https://github.com/acbharath14/crewai-scrum-team): a multi-agent Scrum team (PO/BA/SM/Developer/SDET) on CrewAI + local Ollama that plans, builds, and validates software.
- [llm-eval-harness](https://github.com/acbharath14/llm-eval-harness): 50 golden Q/A items, heuristic + LLM judges, drift detection (PSI), model comparison dashboard. It answers which model to ship, with evidence.
- [doc-extract-eval](https://github.com/acbharath14/doc-extract-eval): compares 5 PDF extraction engines (pypdf, pdfplumber, PyMuPDF, Tesseract, Mistral OCR) with ground-truth F1 scoring, then sends the winning extraction through an LLM for structured business summaries.
- [ollama-junit-demo](https://github.com/acbharath14/ollama-junit-demo): local Ollama drafts JUnit 5 unit tests for a small Java app. Drafts live in ai-generated/ until a human reviews and promotes them. Coverage via JaCoCo, execution reports via Allure.
- [ollama-jev-decision-demo](https://github.com/acbharath14/ollama-jev-decision-demo): typed decision models via Ollama (/v1/systemone): choice, yes/no, and score questions with calibrated probabilities.

## Skills To Repository Map

| Skill from profile | Repository | What to check | Proof artifact |
| --- | --- | --- | --- |
| E2E web automation frameworks | selenium-e2e-automation-framework | Selenium 4 Page Objects, 15 UI journeys + 5 API tests, Jenkins CI | All 20 tests passing on Jenkins + Allure report |
| Native mobile test automation | appium-e2e-automation-framework | Appium Page Objects, 15 tests on Android emulator + iOS simulator | All 15 Android tests passing; iOS 9 passed, 6 intentionally skipped |
| Enterprise QA strategy and test architecture | enterprise-qa-automation-blueprint | Playwright BDD, DB validation, Pact contract tests, k6 performance, ZAP security | 419 tests passing in CI |
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
- **AI-assisted quality:** evaluating LLM systems with evidence: golden datasets, LLM-as-judge scoring, drift detection across runs; AI-drafted Playwright and JUnit tests from local models, promoted only after human review
- **Platforms and tools:** Playwright, Selenium, Cucumber, TypeScript, Java, Python; performance testing (JMeter); mobile automation (Appium, Sauce Labs, LambdaTest)
- **Domain and team:** quality engineering across banking, financial services, credit lending/payments, and mortgage-backed securities; hands-on mentoring of junior SDETs in automation practices and code quality

## Connect

- LinkedIn: https://www.linkedin.com/in/acbharath14/
