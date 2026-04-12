# Agent2Agent Protocol Archive

This repository is a forked/archive copy of Agent2Agent (A2A) protocol material: documentation, specifications, and generated types.

## Project Status

This repository is being open sourced as-is. It may or may not be in working condition. Most of the work here came from vibe-coding experiments by an engineer with very little coding experience, so expect rough edges, stale assumptions, and incomplete maintenance.

## What Is Here

- Protocol documentation and specs under `docs/` and `specification/`
- A MkDocs site definition in `mkdocs.yml`
- Type-generation helpers under `types/`

## Local Use

This repo is not an end-user application. The most realistic local workflow is browsing or serving the docs.

### Docs Site

Requirements:
- Python 3.11+
- `pip`

Commands:

```bash
python -m venv .venv
. .venv/bin/activate
pip install -r requirements-docs.txt
mkdocs serve
```

### Type Generation

Requirements:
- Node.js 20+
- npm

Commands:

```bash
cd types
npm install
npm run generate
```

## Notes

- If you only want to read the content, no runtime dependencies are required.
- The repo is best treated as a protocol/spec archive, not a supported product.
