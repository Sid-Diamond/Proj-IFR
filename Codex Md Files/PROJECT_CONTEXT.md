# Project context

## Purpose

The Impact First Residency at Arcadia Impact is a fellowship programme. This project aims to produce a technical AI safety paper on monitoring the robustness of constitutional classifiers to adversarial attacks.

The project is supervised by Samuel Simko and James Teal. Four residents will use this repository to develop code and share research materials. The target deadline is around 15 December 2026.

## Current status

- The specific classifiers, adversarial attacks, monitoring methods and evaluation metrics are not yet selected.
- Preliminary papers are in `literature/`; a literature document will be added to help scope the research.
- When discussing EuroSafeGuard, consult the local repository `EuroSafeGuard/` and the paper in `literature/Constitional Classifiers/EuroSafeGuard.pdf` or `EuroSafeGuard/paper/EuroSafeGuard.pdf` before searching online. Use online sources only when the needed information is unavailable locally or the user requests an online search.
- Python is expected to be the main language. uv is a provisional tooling choice, pending confirmation of the team's preference.
- Literature and useful reference repositories are intended to be shared with the residents, subject to applicable permissions.
- The project may use private datasets, API keys and large experiment outputs. Local `data/` and `outputs/` directories and `.env` files are ignored by Git.
- `working-paper/working-paper.md` collects the paper outline and verified facts; `project-logs/` holds session history. Agents need an explicit instruction before running paid model API calls.

## Open questions

- Which threat models, classifiers and monitoring methods should the work focus on?
- What datasets, baselines and metrics will support the evaluation?
- What compute and model access are available, and are there restrictions on sharing results or data?
- How should the team share external reference repositories and any large research artifacts?
- What milestones lead up to the target paper deadline?
