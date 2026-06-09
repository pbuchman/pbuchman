# Piotr Buchman

Backend and platform engineer with 14+ years building distributed systems, APIs, and business-critical backend software.

Strongest in Java/Spring, event-driven systems, SQL/PostgreSQL, and turning ambiguous requirements into production systems that stay understandable under load. Recent public work focuses on AI-native tooling, multi-model orchestration, developer workflow automation, and practical software that solves real operational problems.

## Selected Public Work

### [IntexuraOS](https://github.com/pbuchman/intexuraos)

A WhatsApp voice note becomes a tested pull request. Gemini classifies it, the matching agent picks it up, a code worker ships the change, an independent audit reviews the session transcript, and a human only sees the PR.

Worker containers ship both Claude Code and OpenAI Codex CLIs in the same image, picking the runtime per task and dialing reasoning effort up when the task warrants it.

Every coding-agent PR ships with a compliance report from an independent provider auditing the full session transcript before any human reviews the diff.

Review findings get encoded as 50+ Claude Code hooks and 40+ CI verification scripts, so the same lesson never has to be reviewed twice.

### [claude-proxy](https://github.com/pbuchman/claude-proxy)
Smart routing proxy for Claude Code that preserves premium reasoning capacity and controls cost by delegating execution-heavy work to other models when it is safe to do so.

### [MotorScope](https://github.com/pbuchman/motorscope)
Chrome extension plus backend for extracting, tracking, and analyzing car listing data over time. A practical product with browser automation, AI-assisted extraction, and cloud deployment.

### [GitHub YOLO Review](https://github.com/pbuchman/github-yolo-review-extension)
Chrome extension that adds the one filter GitHub was too afraid to ship: hide the tests. One click and the diff shrinks 32-34%*. Built entirely by a frontier LLM. Methodology: vibes.

### [Holy Carp! Logs](https://github.com/pbuchman/holy-carp-logs)
Small but useful browser extension that turns Rancher's unreadable JSON logs into a filterable log viewer people can actually use.

## Certification

- [Anthropic Claude Certified Architect](https://verify.skilljar.com/c/trqoiwubm28i)

## Professional Context

Most of the production-scale work behind my profile comes from backend and platform roles across startups, scale-ups, and enterprise teams:

- built a 61-component AI platform with 400K+ lines of TypeScript, cross-LLM verification, and 100% branch coverage
- owned billing-critical backend systems on workloads around 100M events per day, including usage aggregation across 100 processing nodes
- currently build secure external APIs in a 35+ microservice platform, including OAuth2 security, contract-first design, and resilient integrations
- handled a zero-downtime migration of 10M+ records and built an event-driven workflow engine that became a platform foundation for third-party vendors
- worked on backend systems for remote monitoring and incident handling across 100,000+ vehicles and motorbikes
- moved into technical team leadership, led a 7-10 person team, and technically screened 50+ candidates during a major hiring phase
- built a Salesforce-integrated renewal workflow that saved work equivalent to 2 full-time roles

## Technologies I Reach For

Java, Spring Boot, Spring WebFlux, TypeScript, Node.js, Python, PostgreSQL, MySQL, Redis, Kafka, Docker, Kubernetes, Terraform, AWS, GCP, Azure.

## How I Like To Build

- clear contracts and explicit failure handling
- CI/CD, observability, and production ownership
- pragmatic architecture over theory-first debates
- AI as leverage, not as a replacement for engineering judgment

## Contact

- Email: [kontakt@pbuchman.com](mailto:kontakt@pbuchman.com)
- LinkedIn: [linkedin.com/in/piotrbuchman](https://www.linkedin.com/in/piotrbuchman/)

Less noise, more signal.
