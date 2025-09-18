# 🔗 PromptLinker

**An opinionated, developer-first application for building and hosting "headless" AI agents. It provides a robust, code-first alternative to drag-and-drop agent builders by embracing the "Agents-as-Code" paradigm.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Project Status: Active](https://img.shields.io/badge/status-active-brightgreen.svg)](#)
[![code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

---

## The Vision: Professional AI Agents, Defined as Code

The current AI agent ecosystem presents a difficult choice for developers:

1.  **Drag-and-Drop UIs:** These are great for rapid prototyping, but agent logic becomes trapped in opaque JSON files that are difficult to version control, review, and test with the rigor of a true software development lifecycle.
2.  **Raw Agentic Frameworks:** These libraries (like LangGraph) offer infinite power, but require developers to build the entire application infrastructure—the web server, API layer, configuration, and deployment—from scratch for every project.

`PromptLinker` is being built to bridge this gap. It provides the **pre-built, professional application infrastructure** so developers can focus on what matters: defining an agent's logic and tools in clean, version-controllable, and testable Python.

It is designed to be the de facto open-source server for running production-grade, "headless" AI agents, with an initial focus on supercharging the next generation of AI coding assistants.

## The "Agents-as-Code" Philosophy

`PromptLinker` is an **opinionated** application built on a few core principles that will guide its development:

*   **Logic in Code, Not UIs:** An agent's reasoning, tools, and workflows should live in version-controllable Python files. This enables code reviews, automated testing, and a robust CI/CD process for your agents.
*   **A Professional Foundation:** The project will provide the boilerplate so you don't have to. The FastAPI server, OpenAI-compatible endpoint, Docker packaging, and configuration system are core features.
*   **Extensible by Convention:** Adding new capabilities should be simple and intuitive. The goal is a convention-based plugin system that is powerful without being complex.
*   **Model Agnostic:** `PromptLinker` will be a universal gateway, allowing you to route requests to a wide variety of local and commercial LLM providers.

## 🗺️ Project Status & Roadmap

This project is in the initial design and development phase. The immediate focus is on building the core server and a foundational, convention-based tool-loading system.

- [ ] Core server with an OpenAI-compatible API endpoint.
- [ ] A basic LangGraph agent for routing and state management.
- [ ] A clean, convention-based tool-loading system.
- [ ] The first reference tool: A remote GitHub file reader.
- [ ] A robust testing framework for tools.

## 🤝 Contributing

This is a new project with a big vision. If you believe in the "Agents-as-Code" paradigm and want to help shape the future of professional, reliable AI systems, your contributions are welcome.

Please see our `CONTRIBUTING.md` guide for our development philosophy and how to get started once the foundational code is in place. All contributors are expected to follow our `CODE_OF_CONDUCT.md`.

## 📜 License

`PromptLinker` is licensed under the [MIT License](./LICENSE).

```
