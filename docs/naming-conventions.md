# Naming Conventions

This document outlines naming conventions for files, folders, and content in the AI Research Lab repository.

## File Naming

### General Rules
- Use **lowercase** letters
- Separate words with **hyphens** (`-`)
- Be **descriptive** and **specific**
- Avoid abbreviations unless widely understood

### Examples
- ✅ `episodic-memory-design.md`
- ✅ `reasoning-engine-architecture.md`
- ✅ `2024-11-24-research-log.md`
- ❌ `episodic_memory.md` (use hyphens, not underscores)
- ❌ `EMD.md` (too abbreviated)
- ❌ `memory.md` (too generic)

## Folder Naming

- Use **lowercase** with **hyphens**
- Keep names **short** but **clear**
- Examples: `paper-summaries`, `book-summaries`, `systems-design`

## Document Types

### Research Logs
Format: `YYYY-MM-DD-research-log.md` or `YYYY-MM-DD-weekly-log.md`
- Example: `2024-11-24-research-log.md`

### Research Notes
Format: `[topic]-[descriptor].md`
- Example: `memory-consolidation-mechanisms.md`
- Example: `reasoning-symbolic-neural-hybrid.md`

### Paper Summaries
Format: `[first-author-lastname]-[year]-[short-title].md` or `[paper-short-title].md`
- Example: `vaswani-2017-attention.md`
- Example: `attention-is-all-you-need.md`

### Experiments
Format: `[experiment-name]-[descriptor].md`
- Example: `hierarchical-planning-evaluation.md`
- Example: `memory-consolidation-test.md`

### Architecture Proposals
Format: `[module]-[proposal-name].md`
- Example: `memory-vector-db-integration.md`
- Example: `reasoning-causal-inference-module.md`

### Ideas
Format: `[idea-name]-[descriptor].md`
- Example: `temporal-memory-idea.md`
- Example: `multi-agent-coordination-concept.md`

## Code Files

### Python
- Use `snake_case` for files and modules
- Example: `memory_manager.py`, `reasoning_engine.py`

### Configuration Files
- Use lowercase with hyphens or underscores as appropriate
- Example: `config.yaml`, `model_config.json`

## Versioning

For documents that evolve:
- Use dates in filenames: `memory-design-2024-11.md`
- Or version numbers: `architecture-v2.md`

## Best Practices

1. **Be consistent** - Follow these conventions across the repository
2. **Be searchable** - Use terms that make files easy to find
3. **Be specific** - Avoid generic names like `notes.md` or `ideas.md`
4. **Date when relevant** - Include dates for time-sensitive content
5. **Group related files** - Use consistent prefixes for related documents

## Examples by Category

### Notes
- `memory-episodic-architecture.md`
- `reasoning-causal-inference.md`
- `planning-hierarchical-decomposition.md`

### Papers
- `deepmind-world-models.md`
- `openai-gpt-4-technical-report.md`
- `anthropic-constitutional-ai.md`

### Experiments
- `memory-retrieval-speed-test.md`
- `reasoning-chain-of-thought-eval.md`
- `planning-horizon-scaling.md`

### Systems Design
- `memory-overview.md`
- `reasoning-core.md`
- `safety-framework.md`

