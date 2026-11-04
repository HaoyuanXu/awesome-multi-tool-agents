# 🤝 Contributing

Contributions of papers, benchmarks, datasets, and official implementations are welcome.

## 🎯 Scope

Resources should address tool-mediated LLM agents, with a clear connection to dependent tool calls, stateful interaction, execution feedback, planning, training, recovery, safety, efficiency, toolset adaptation, evaluation, or an application workflow. Foundational single-call work belongs in the foundations page when it helps explain the development of orchestration.

## ➕ Add a Resource

Choose the relevant subsection in a [topic catalog](README.md#taxonomy). Add the full title, publication year, venue or preprint status, and a direct link to the paper. Include an official code or project link when available. Keep entries ordered by year, newest first, then alphabetically within a year.

Follow the existing table format. For example:

```markdown
| [An LLM Compiler for Parallel Function Calling](https://proceedings.mlr.press/v235/kim24y.html) · [Code](https://github.com/SqueezeAILab/LLMCompiler) | 2024 | ICML 2024 |
```

In the pull request or issue, add one sentence explaining the resource's connection to the chosen subsection. Cross-cutting work can be linked from another relevant page. Prefer one entry per underlying study within a page, using the published version when available and labeling preprints clearly.

## ✏️ Corrections and New Work

For a metadata correction, include a link to the canonical publication or author-maintained project. Keep the [published corpus CSV](data/survey-corpus.csv) as the original survey snapshot; update the reading catalogs to reflect subsequent publications and new work. The homepage's 240-work count refers to that snapshot.

Homepage starting points are a small reading guide. Most additions belong in the topic catalogs.
