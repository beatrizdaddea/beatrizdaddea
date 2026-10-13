# Beatriz Chieffi

**QA Automation | Quality Engineering | Software Development | API Testing**

I'm a software developer based in Brazil, with professional experience in technology since 2022. My current work combines **QA automation and N3 software development/support** for production applications.

I design test scenarios, automate functional and regression checks, validate REST APIs and relational data, and investigate defects using logs, SQL, and code analysis. I also work on applied research involving **LLM evaluation and AI-agent security**.

[LinkedIn](https://www.linkedin.com/in/beatriz-daddea) · [GitHub](https://github.com/beatrizdaddea) · [Email](mailto:beatrizchith@gmail.com)

## Quality engineering in production

My work involves complex municipal applications, including a permitting and licensing platform and a Geographic Information System (GIS).

| System | Automation scope | Tooling |
| --- | --- | --- |
| Permitting and licensing | **79 of approximately 81 eligible scenarios automated (~97.5%)**, in a system with **253 mapped functionalities** | Cypress, Allure Report |
| Geographic Information System | **142 automated tests**, in a system with **400 mapped functionalities** | Cypress, Allure Report |

The permitting-system percentage refers **only to scenarios eligible for automation**, not all 253 mapped functionalities. External authentication, APIs, and municipal integrations constrain which end-to-end flows can be automated reliably. These figures describe the automation work in the systems I support, not individual ownership of every test.

My responsibilities also include functional, integration, regression, and E2E testing; requirements and acceptance-criteria analysis; REST API validation with Postman; SQL-based data checks; production troubleshooting; and collaboration on CI/CD quality checks.

## Featured projects

### 01 — [Security QA: OWASP Juice Shop](https://github.com/beatrizdaddea/security-qa-juice-shop)

A security-focused QA portfolio for a deliberately vulnerable web application, with **Cypress + TypeScript** tests for UI and APIs.

- Bilingual test plan and **18 documented manual test cases**.
- Page Object Model, test traceability, defect templates, and execution-report structure.
- **Allure Report** integration and a local-only **OWASP ZAP** baseline workflow.
- **Docker Compose** to run the target application in a controlled environment.

**Stack:** [Cypress](https://docs.cypress.io/), [TypeScript](https://www.typescriptlang.org/), [Allure Report](https://allurereport.org/), [Docker](https://docs.docker.com/), [OWASP ZAP](https://www.zaproxy.org/).

**Status:** Test infrastructure and documentation are available. The repository's formal execution summary still needs final results; no pass rate is claimed here.

### 02 — [TaskBoard: Backend, APIs & Test Automation](https://github.com/beatrizdaddea/task-board)

A full-stack task management application with a **Django REST Framework API**, PostgreSQL, and a React frontend.

- JWT authentication with **HttpOnly cookies** and CSRF protection.
- Resource-level access control for private and shared tasks.
- Backend tests with **pytest** and critical browser flows with **Selenium**.
- **GitHub Actions** checks for backend, frontend, API schema, and Docker Compose; the backend pipeline enforces a **90% minimum coverage threshold**.
- OpenAPI documentation with **drf-spectacular**.

**Stack:** [Python](https://www.python.org/), [Django REST Framework](https://www.django-rest-framework.org/), [PostgreSQL](https://www.postgresql.org/), [React](https://react.dev/), [pytest](https://docs.pytest.org/), [Selenium](https://www.selenium.dev/), [GitHub Actions](https://docs.github.com/en/actions), [drf-spectacular](https://drf-spectacular.readthedocs.io/).

### 03 — [Agent Security Dojo](https://github.com/beatrizdaddea/Agent-Security-Dojo)

A local, simulated environment for studying **indirect prompt injection** in tool-using AI agents.

- Vulnerable and defensive modes, with simulated email, calendar, and document tools.
- Tool restrictions, untrusted-output handling, and guards on sensitive actions.
- Reproducible scenarios and evaluation metrics for attack success, tool misuse, and legitimate-task utility.
- Deterministic offline evaluation; optional LLM integration.

**Stack:** [Python](https://www.python.org/), [LangGraph](https://docs.langchain.com/oss/python/langgraph/overview), [Pydantic](https://docs.pydantic.dev/latest/), [pytest](https://docs.pytest.org/).

## Engineering techniques

- **Test design and traceability:** acceptance criteria, regression scenarios, reusable Page Objects, defect records, and Allure metadata.
- **Layered verification:** UI, REST API, and database checks to catch different classes of defects.
- **CI quality gates:** automated tests, coverage thresholds, linting, and API-schema validation.
- **Session security:** cookie-based JWT authentication and CSRF safeguards; see MDN's [HTTP cookies](https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/Cookies) and [Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch).
- **Concurrent request handling:** a shared token-refresh operation for simultaneous requests; see MDN's [JavaScript Promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise).
- **AI security evaluation:** controlled tool outputs, trust-boundary checks, defensive comparisons, and repeatable test cases.

## Technical stack

| Area | Technologies and practices |
| --- | --- |
| **QA & automation** | Cypress, Cucumber/Gherkin, Allure Report, Postman, Jest, pytest, Selenium; Playwright (proofs of concept) |
| **Languages** | JavaScript, TypeScript, Python, Java, SQL |
| **Backend & data** | Java/Spring Boot, Django REST Framework, REST/JSON, PostgreSQL, MySQL |
| **Delivery & diagnostics** | Git, GitHub Actions, Docker, CI/CD, SonarQube, production logs, root-cause analysis |
| **AI & security** | LangGraph, Pydantic, LLM evaluation, prompt-injection testing, OWASP ZAP |
| **Previous development work** | React, Vue.js, Ruby on Rails, cross-platform web/mobile applications |

## Education & research

- **Postgraduate Specialization in Artificial Intelligence** — UTFPR, completed 2026.
- **B.Sc. in Computer Science** — UNIP, completed 2024.
- **Applied AI research** — LLM evaluation, agent workflows, and security testing.
- **Languages:** Portuguese (native), English (B2).

## Contact

- **LinkedIn:** [linkedin.com/in/beatriz-daddea](https://www.linkedin.com/in/beatriz-daddea)
- **GitHub:** [github.com/beatrizdaddea](https://github.com/beatrizdaddea)
- **Email:** [beatrizchith@gmail.com](mailto:beatrizchith@gmail.com)
