# Research Workflow

**Purpose:** Standardize research processes and documentation practices in the AI Research Lab.

---

## Overview

This document outlines the workflow for conducting research, documenting findings, and maintaining the repository. Follow these guidelines to ensure consistency and quality.

## 🔄 Research Cycle

### 1. Idea Generation
- Capture ideas in `/ideas/` using `idea-template.md`
- Document motivation, feasibility, and architecture connections
- Link to related research

### 2. Literature Review
- Read papers and create summaries in `/papers/` using `paper-summary-template.md`
- Extract key insights and architecture implications
- Create concise summaries in `/notes/paper-summaries/` for quick reference
- Document experiment proposals inspired by papers

### 3. Architecture Design
- Create architecture proposals in `/systems-design/[module]/` using `architecture-proposal-template.md`
- Update `architecture-overview.md` with new designs
- Create module-specific overviews as needed
- Document integration points and interfaces

### 4. Experiment Planning
- Design experiments in `/experiments/` using `experiment-template.md`
- Define hypotheses, methodology, and metrics
- Link to related papers and notes
- Get feedback before implementation

### 5. Implementation
- Implement prototypes in `/models/` (code)
- Document implementation decisions
- Track challenges and solutions
- Update architecture docs as needed

### 6. Documentation
- Create research notes in `/notes/` using `research-note-template.md`
- Document findings, insights, and implications
- Link to experiments, papers, and architecture
- Update relevant overview documents

### 7. Logging
- Maintain research logs in `/research-log/` using `research-log-template.md`
- Document daily/weekly discoveries
- Track connections between ideas
- Note next steps and priorities

## 📁 File Organization

### Where to Put What

| Content Type | Location | Template |
|-------------|----------|----------|
| Raw ideas | `/ideas/` | `idea-template.md` |
| Paper reviews | `/papers/` | `paper-summary-template.md` |
| Paper summaries | `/notes/paper-summaries/` | `paper-summary-template.md` (condensed) |
| Book summaries | `/notes/book-summaries/` | Custom format |
| Research notes | `/notes/` | `research-note-template.md` |
| Architecture designs | `/systems-design/[module]/` | `architecture-proposal-template.md` |
| Experiments | `/experiments/` | `experiment-template.md` |
| Daily logs | `/research-log/` | `research-log-template.md` |

## 🔗 Linking & Cross-References

### Always Link To:
- Related papers (in `/papers/`)
- Related notes (in `/notes/`)
- Related experiments (in `/experiments/`)
- Architecture modules (in `/systems-design/`)
- Research logs (in `/research-log/`)

### Link Format
Use relative paths: `[Link Text](../papers/paper-name.md)`

## 📝 Naming Conventions

Follow the guidelines in `docs/naming-conventions.md`:
- Use lowercase with hyphens
- Be descriptive and specific
- Include dates for time-sensitive content
- Use consistent prefixes for related files

## ✅ Quality Checklist

Before committing any document:

- [ ] Used appropriate template
- [ ] Followed naming conventions
- [ ] Linked to related documents
- [ ] Included architecture implications
- [ ] Added relevant diagrams (if applicable)
- [ ] Checked spelling and grammar
- [ ] Included references and citations

## 🔄 Review Process

### Self-Review
- Review your own documents before committing
- Ensure clarity and completeness
- Check links and references

### Peer Review (if applicable)
- Request feedback on major architecture decisions
- Review experiment designs before implementation
- Get input on research directions

## 📊 Progress Tracking

### Weekly
- Update research log
- Review progress against roadmap
- Identify blockers and next steps

### Monthly
- Review roadmap and adjust if needed
- Consolidate findings
- Plan next month's priorities

### Quarterly
- Major roadmap review
- Architecture evolution assessment
- Research direction evaluation

## 🎯 Best Practices

1. **Document Early** - Write notes as you research, not after
2. **Link Everything** - Connect related concepts and documents
3. **Be Specific** - Use concrete examples and details
4. **Update Regularly** - Keep documents current
5. **Think Architecture** - Always consider AI Brain implications
6. **Experiment First** - Test ideas before full implementation
7. **Learn Continuously** - Update knowledge base regularly

## 🚨 Common Mistakes to Avoid

- ❌ Creating files without templates
- ❌ Using inconsistent naming
- ❌ Forgetting to link related documents
- ❌ Not updating architecture overview
- ❌ Skipping research logs
- ❌ Creating duplicate content
- ❌ Not documenting decisions

## 📚 Resources

- Templates: `/templates/`
- Naming conventions: `docs/naming-conventions.md`
- Roadmap: `docs/roadmap.md`
- Architecture overview: `systems-design/architecture-overview.md`
- Contributing guide: `CONTRIBUTING.md`

---

**Last Updated:** November 2024

