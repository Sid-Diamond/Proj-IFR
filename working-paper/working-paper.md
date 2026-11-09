# Working paper

This document collects the evolving paper outline and agreed or verified facts. Record sources and experimental provenance, and distinguish established findings from hypotheses or open questions.

## Research direction

The project aims to produce a technical AI safety paper on monitoring the robustness of constitutional classifiers to adversarial attacks. The precise research question remains open.

## Verified facts and evidence

- EuroSafeGuard uses REDACT to expand 4,858 BELLS-O constitution entries into 17,903 accepted prompts, which feed its training data rather than forming a separate evaluation set. Appendix D includes these prompts and their augmentations (about 98k rows), alongside CeSIA's distinct 26,979-prompt constitution-input set, within 540,536 gate-training prompts. Its BELLS-O supervision evaluation instead uses the content-moderation input set (1,100 harmful and 300 benign prompts). Source: `literature/Constitional Classifiers/EuroSafeGuard.pdf`, printed pp. 7, 9 and 35, Sections 4.2, 5 and Appendix D.

## Open questions

- Which classifiers, attacks, monitoring methods and evaluation metrics should be studied?
