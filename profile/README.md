# Agentic Workflow Library (AWL)

**AWL** is an open-source framework and curated library of intelligent, agent-driven scientific workflows.
We are building a future where every bioinformatics workflow is not just executable—but *agentic*: aware of its purpose, capable of answering questions, and ready to collaborate.

> ✨ Built by and for the bioinformatics and AI community.
> 🧜‍♂️ Focused on reproducible, intelligent, and scalable analysis.

---

## 🔍 What Is AWL?

AWL is both a **framework** and a **collection of reusable agents** designed to modernize scientific workflows through automation, intelligence, and collaboration.

It consists of:

* 🧱 A modular agent framework (runtime, CLI, schema, dev tools)
* 🤖 Prebuilt domain-specific agents (e.g., RNA-seq, SV-calling)
* 📚 A growing community catalog of shareable workflows and tools
* ↻ A human-in-the-loop design: agents that work *with* researchers

Think: the power of CWL or Nextflow, but with an **LLM-aware assistant behind every step**.

---

## 🧬 Why Agentic Workflows?

Traditional workflows are rigid and opaque.
**Agentic workflows are flexible, self-documenting, and interactive.**

AWL agents:

* Understand their domain (e.g., RNA-seq, GWAS, variant calling)
* Know their tools (via CWL, Docker, environment metadata)
* Respond to prompts (LLM integration)
* Validate inputs, run tests, and explain decisions
* Coordinate across projects with a project manager agent

---

## 🧠 Key Components

```
agentic-workflow-language/
├── awl-core/          # The runtime engine and orchestration layer
├── awl-cli/           # Command-line tool for managing agents
├── awl-spec/          # YAML schemas and AWL definitions
├── awl-catalog/       # Shared library of agent metadata and tools
├── awl-handbook/      # Community docs and onboarding
├── sv-agent/          # Example: agent for structural variant workflows
├── rnaseq-agent/      # Example: agent for RNA-seq pipelines
└── example-workflows/ # Publicly available test pipelines
```

---

## 🚀 Getting Started

```bash
# Install CLI (coming soon)
pip install awl

# Clone an example agent
git clone https://github.com/agentic-workflow-language/sv-agent.git

# Run interactively
awl run sv-agent --chat

# Or run headlessly
awl run sv-agent --input config.yaml
```

---

## 🧋 Built on Open Standards

AWL leverages and extends:

* [Common Workflow Language (CWL)](https://www.commonwl.org/)
* Docker and Conda environments
* JSON/YAML schema validation
* LLMs like GPT-4, Claude, and Ollama for interpretability
* Vector databases (optional) for retrieval-augmented prompting

---

## 🤝 Community

We believe bioinformatics workflows should be:

* **Reusable**
* **Understandable**
* **Auditable**
* **Promptable**

Join us in building agentic infrastructure for the next generation of scientific computing.

📬 [hello@awl.is](mailto:hello@awl.is)  
🌐 [awl.is](https://awl.is)  
📣 [GitHub Discussions](https://github.com/orgs/agentic-workflow-language/discussions) *(coming soon)*  
💬 Chat with us via [Matrix](https://matrix.to/#/#awl:matrix.org) *(coming soon)*

---

## 🛠️ Contributing

We welcome contributions from researchers, developers, and toolmakers.
Whether you're wrapping CWL tools, building new agents, writing docs, or just testing things—your help is valuable.

Start here:

```bash
git clone https://github.com/agentic-workflow-language/awl-handbook.git
cd awl-handbook
```

See [`CONTRIBUTING.md`](https://github.com/agentic-workflow-language/awl-handbook/blob/main/CONTRIBUTING.md) for guidelines.

---

## 📜 License

AWL is released under the [Apache 2.0 License](LICENSE).
Open, extensible, and free for all.

---

## 🔭 Vision

We believe in a future where:

* Scientists **collaborate with their workflows** like they would with a lab technician
* Agents evolve with new data, methods, and tools
* Workflows are not just pipelines—but peers in the discovery process

Let’s build that future together.

**— The AWL Team**
