# Dmitri Tsjornoi

Integration engineer. I build the machinery that decides whether a language model's output is allowed to reach production.

## What I build

**Agent harnesses.** The interesting part of an LLM system is not the prompt. It is everything around it: what context the model is allowed to see, which tools it can call, what checks its output, and when it is permitted to stop. Right now that is a mapping-automation pipeline that generates XSLT transformations and refuses to put any of them in front of a reviewer until they pass a golden-pair correctness oracle. The model writes the code. The harness decides whether that code ships.

**MCP servers.** Custom servers for GitLab, Jira and internal knowledge systems, and one that drives live WordPress and Elementor sites over a bridge plugin. Designing tools for an agent is API design for a consumer that will not read your documentation and will not ask you a question when it gets confused — so the schema, the error messages and the defaults have to carry all of it.

**Integration systems.** EDI and API pipelines moving high volumes of business data across global supply chains: EDIFACT, ANSI X12, XML/XSLT/XSD, AS2, SFTP. This is the domain that taught me to care about verification. A wrong transformation is not a failing test, it is a wrong invoice.

**Developer tooling.** A VS Code extension on the Language Model API with two execution paths — a deterministic one-shot and a separate agentic loop — plus the observability needed to tell which of them failed, and why.

## Things I believe about this work

- Correctness has to be machine-checkable, or the agent is just producing confident text.
- Context is a budget. Most agent failures are retrieval and scope failures wearing a reasoning costume.
- A verification loop nobody can read is not verification.

## Stack

- **Languages** — TypeScript, Python, Rust, PHP, Bash, SQL, XSLT
- **Agents & AI** — MCP, VS Code LM API, LangChain (Deep Agents), CrewAI, AutoGen, Langfuse
- **Integration** — EDIFACT, ANSI X12, XML/XSD, REST, AS2, SFTP
- **Web** — React, NestJS, Node.js, WordPress, WooCommerce
- **Infrastructure** — Linux, nginx, MySQL, Cloudflare, Plesk, AWS, GitHub Actions
- **Quality & observability** — golden-pair validation, XSLT unit testing, SonarQube, Elasticsearch, Kibana, Grafana

## Elsewhere

Freelance web and automation work through [websculpt.ee](https://websculpt.ee). Arduino and small hardware projects when I want a problem that fails visibly.

Based in Tallinn. Always up for a conversation with engineers working where systems integration meets AI automation.
