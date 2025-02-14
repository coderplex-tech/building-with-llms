# Augmented LLM Pattern

This pattern demonstrates how to enhance a base LLM with essential capabilities like retrieval, tools, and memory. It serves as the foundation for more complex patterns.

![Augmented LLMs Pattern](./images/diagram)

## Core Components

1. **Base LLM Integration**: Direct API calls to LLM providers
2. **Retrieval Augmentation**: Adding context from external sources
3. **Tool Usage**: Basic tool definition and execution
4. **Memory Management**: Maintaining conversation state

## Implementation Examples

Each example demonstrates the pattern using different LLM providers while maintaining similar architecture:

```python
├── examples/
|   ├── anthropic_example.py
|   └── openai_example.py
├── tools/
│   ├── search_tool.py
│   └── calculator_tool.py
├── memory/
│   └── conversation_memory.py
└── retrieval/
    └── vector_store.py
```

## Running the Examples

1. Set up your environment:

```bash
python -m venv venv
source venv/bin/activate  # or `venv\Scripts\activate` on Windows
pip install -r requirements.txt
```

2. Set up your API keys in a .env file:
   bash

```bash
ANTHROPIC_API_KEY=your_anthropic_key_here
OPENAI_API_KEY=your_openai_key_here
```

3. Run the examples:

```bash
# Run Anthropic example
python examples/anthropic_example.py

# Run OpenAI example
python examples/openai_example.py
```
