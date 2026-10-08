> **Archived 2026-10-08.** No further development; this work continues in a private repository.

# GraphRAG Buddhism Project

A GraphRAG implementation for analyzing Buddhist texts, specifically focusing on the Heart Sutra.

## Project Structure

```
graphRAG_buddism/
├── ragtest/          # Main RAG implementation
│   ├── input/        # Input documents (Buddhist texts)
│   ├── output/       # Generated outputs and indexes
│   ├── cache/        # Cache files
│   ├── prompts/      # Prompt templates
│   └── settings.yaml # Configuration settings
└── .venv/           # Python virtual environment
```

## Setup

1. Clone the repository
2. Create a virtual environment: `python -m venv .venv`
3. Activate the environment: `source .venv/bin/activate`
4. Install dependencies (if requirements.txt exists)

## Usage

Configure your settings in `ragtest/settings.yaml` and place input documents in `ragtest/input/`.

## License

MIT