# Dmitri Tsjornoi

**IT Integration Engineer — Tallinn, Estonia**

Over 6 years at a leading global logistics provider, building and maintaining the EDI and API integration systems that move high volumes of business data across global supply chains. Most of my time goes into the part that is actually hard: turning ambiguous business requirements into something that runs reliably in production and keeps running when the data does not cooperate.

## Harness engineering

Over the past year I moved from experimenting with AI to shipping it. The work is best described as harness engineering: building the scaffolding around a language model that decides what context it sees, which tools it can call, how its output is verified, and when it is allowed to stop. The model writes the code. The harness decides whether that code ships.

In practice this is an AI-assisted mapping automation pipeline. It takes a logical mapping specification and produces a generated XSLT transformation that has to pass a golden-pair correctness oracle before a human reviews anything, then moves through the delivery workflow the team already uses — Jira, Git, MR-based approval. Around that pipeline I have built custom MCP servers for GitLab, Jira and internal knowledge systems, a VS Code extension on the Language Model API with a deterministic one-shot path and a separate agentic loop, and the observability needed to see which one is failing and why.

My interest is deliberately narrow: agentic architectures applied to enterprise integration, where correctness is machine-checkable and a wrong transformation has a real cost attached to it.

## Skills and technologies

- **EDI systems** — design, deployment and management
- **Interface data formats** — JSON, XML/XSLT/XSD, EDIFACT, ANSI X12
- **Communication protocols** — SFTP, AS2, HTTPS, REST APIs
- **Scripting & DB** — UNIX/Python scripts, SQL
- **Agent harness engineering** — verification loops, context management, tool interfaces, custom MCP servers, VS Code LM API
- **Agent frameworks** — LangChain (Deep Agents), CrewAI, AutoGen
- **Web & app development** — TypeScript, React, Python, Rust
- **Quality & performance** — XSLT unit testing, golden-pair validation, SonarQube
- **Observability** — Elasticsearch, Kibana, Grafana, Langfuse

## Outside the day job

Through [websculpt.ee](https://websculpt.ee) I build and run websites and online stores for small businesses — WordPress and WooCommerce development, migrations between hosts without downtime, DNS, Cloudflare and certificates, and the automation that removes the weekly manual work. Custom React and NestJS applications when an off-the-shelf plugin is not the answer. Also Arduino and small hardware projects, purely for fun.

---

Always open to connecting with engineers working at the intersection of systems integration and AI automation.
