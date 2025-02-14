# LLM Architecture Patterns

A practical guide and reference implementation of architecture patterns for building with Large Language Models (LLMs). This repository focuses on native implementations without relying on frameworks, demonstrating how to build both simple workflows and complex autonomous agents.

## Overview

This repository provides:

- 🏗️ Reference architectures for common LLM patterns
- 💻 Example implementations using native LLM APIs
- 📚 Practical guides and best practices
- 🛠️ Templates for quick starts

## Architecture Patterns

### Building Blocks

- **Augmented LLM**: Basic LLM integration with retrieval, tools, and memory
- **Tool Integration**: Patterns for designing and implementing LLM tools

### Workflows

- **Prompt Chaining**: Sequential LLM calls with intermediate processing
- **Routing**: Input classification and specialized handling
- **Parallelization**: Concurrent LLM processing with sectioning and voting
- **Orchestrator-Workers**: Dynamic task decomposition and delegation
- **Evaluator-Optimizer**: Iterative improvement through feedback loops

### Agents

- **Autonomous Agents**: Self-directed systems with planning and execution
- **Domain-Specific Agents**: Implementations for customer support, coding, etc.

## Getting Started

Each pattern includes:

- Architectural overview
- Implementation examples using different LLM providers:
  - Anthropic Claude
  - OpenAI GPT
  - Google Vertex AI
  - Azure OpenAI
- Test cases and example outputs
- Best practices and common pitfalls

## Usage

Navigate to the specific pattern you're interested in:

```bash
examples/
  workflows/prompt-chaining/  # For prompt chaining examples
  agents/autonomous-agent/    # For autonomous agent examples
```

Each example contains a standalone implementation that you can run with your API keys.

## Prerequisites:

- Python 3.8+
- API keys for the LLM provider(s) you want to use

## Contributing

We welcome contributions! Please see our Contributing Guide for details.

## Why Native Implementations?

While frameworks like LangChain can be useful, we believe building directly with LLM APIs provides:

- Better understanding of core concepts
- More control over implementation details
- Easier debugging and maintenance
- Lower overhead and dependencies

## Resources

- Architecture Decision Records
- Pattern Documentation
- Implementation Guides
