# Impact First Residency: Constitutional Classifier Robustness

Research code and shared materials for an Impact First Residency project at Arcadia Impact. The project aims to produce a technical AI safety paper on monitoring the robustness of constitutional classifiers to adversarial attacks.

The project is supervised by Samuel Simko and James Teal and involves four residents. The target deadline is around 15 December 2026.

## Research scope

The classifiers, attacks, monitoring approaches and evaluation metrics are still to be determined. A forthcoming literature document will help scope the work. See [PROJECT_CONTEXT.md](Codex%20Md%20Files/PROJECT_CONTEXT.md) for the current context and open questions.

## Repository layout

- `research/` — project code and experiments.
- `literature/` — preliminary papers and shared literature materials.
- `AGENTS.md` — guidance for AI coding agents working in this repository.
- `Codex Md Files/` — detailed agent working rules and project context.
- `working-paper.md` — evolving paper outline and verified facts.

Create `project-logs/` for session history as it is needed.

## Getting started

Python is the expected primary language. This repository uses [uv](https://docs.astral.sh/uv/) provisionally; the team can adjust the tooling after confirming Samuel's preference.

Install uv and a supported Python interpreter, then run:

```sh
uv sync
```

As experiments and dependencies are added, document how to run and reproduce them here. Keep API keys and other credentials in local environment variables or an untracked `.env` file.

Put local datasets in `data/` and experiment outputs in `outputs/`; both directories are ignored by Git because they may contain sensitive or large files. Agree on a suitable sharing method before adding datasets or results to the repository.

## Shared reference material

Literature files are intended to be shared, subject to copyright and any applicable access restrictions. Git does not automatically track the contents of nested Git clones. For useful external projects, the team can share links or decide whether to add Git submodules.
