# Amplifier

AI-powered modular development assistant framework.

## Tech Stack
- Python 3.11+
- UV package manager
- Modular plugin architecture

## Development
```bash
pip install -e ".[dev]"
python -m pytest
```

## Structure
Amplifier is the core framework — a small kernel with a modular userspace for AI agents. Modules provide tools, providers, loops, hooks, and context management.

## Conventions
- Follow existing code patterns
- Include type hints
- Write docstrings for public functions
- Respect the module boundary contracts
