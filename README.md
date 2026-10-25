# Bharath Arsikere Chandrashekar

QA Automation Architect with 15+ years in enterprise quality engineering across web, microservices, mobile apps development in regulated financial domains.

## Core Strengths

- **Quality architecture:** end-to-end automation strategy, CI/CD pipelines, quality gates, and release decisions grounded in test evidence
- **API and integration testing:** contract testing (Pact), service virtualization (WireMock), integration validation, REST Assured
- **AI-assisted quality:** LLM evaluation (golden datasets, LLM-as-judge, drift detection); AI-generated Playwright and JUnit tests from local models, human-reviewed before adoption
- **Platforms and tools:** Playwright, Selenium, TypeScript, Java, Python; performance testing (JMeter); mobile automation (Appium, Sauce Labs, LambdaTest)
- **Domain and team:** quality engineering for cloud based environments in regulated financial services; mentoring junior SDETs on automation best practices and code quality

## Start Here
If you review only three repositories, review these:

1. https://github.com/acbharath14/microservices-contract-and-integration-testing
2. https://github.com/acbharath14/cicd-quality-gates-reference-implementation
3. https://github.com/acbharath14/enterprise-qa-automation-blueprint

Read them in this order — they show how integration risk signals flow into release decisions.

## AI Quality Engineering

Beyond traditional test automation, I built an evaluation harness to compare models with evidence:

- **[llm-eval-harness](https://github.com/acbharath14/llm-eval-harness)** — 50 golden Q/A items, heuristic + LLM judges, drift detection (PSI), model comparison dashboard. Answers "which model should we ship?" with evidence.
- **[doc-extract-eval](https://github.com/acbharath14/doc-extract-eval)** — Compares 5 PDF extraction engines (pypdf, pdfplumber, PyMuPDF, Tesseract, Mistral OCR) with ground-truth F1 scoring, then pipes winners through an LLM for structured business summaries.

And I build AI-generated testing with local models — no cloud model, no test run leaves your machine:

- **[ai-playwright-framework](https://github.com/acbharath14/ai-playwright-framework)** — Playwright + local Ollama: drafts specs from ARIA snapshots, advises and audits locators, and applies fixes only on approval, with an HTML failure report on red runs.
- **[ollama-junit-demo](https://github.com/acbharath14/ollama-junit-demo)** — Local Ollama drafts JUnit 5 unit tests for a small Java app. Drafts live in ai-generated/ until a human reviews and promotes them. Coverage via JaCoCo, execution reports via Allure.

## Skills To Repository Map

| Skill from profile | Repository | What to check | Proof artifact |
| --- | --- | --- | --- |
| Contract testing and integration risk control | microservices-contract-and-integration-testing | Multi-service orchestration scenarios: happy-path, timeout-fallback, schema-drift. Pact consumer + provider verification, OpenAPI validation, WireMock virtualization | docs/evidence-suite.md |
| Release governance and CI/CD quality gates | cicd-quality-gates-reference-implementation | PASS, WARN, BLOCK decisions from metrics plus integration report input | docs/evidence-integration.md |
| Enterprise automation framework thinking | enterprise-qa-automation-blueprint | Playwright smoke flow tied to release-health UI signals | docs/evidence.md |
| LLM evaluation and model selection | llm-eval-harness | Golden dataset, judge agreement, drift detection, side-by-side model comparison | reports/ |
| Document AI evaluation | doc-extract-eval | Extractor comparison with ground-truth F1 scoring | reports/ |
| AI-generated end-to-end tests (Playwright + local LLM) | ai-playwright-framework | ARIA snapshot → drafted specs, locator advice and audit, approval-gated fixes, HTML failure report | tests/generated/ |
| AI-generated unit tests (local LLM) | ollama-junit-demo | Ollama drafts JUnit 5 tests for a Java app, human review before promotion | ai-generated/ |

## Connect

- GitHub: https://github.com/acbharath14
- LinkedIn: https://www.linkedin.com/in/acbharath14/
