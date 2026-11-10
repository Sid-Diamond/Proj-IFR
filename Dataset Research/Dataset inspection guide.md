# Dataset inspection guide

## Purpose

Use this guide to discuss candidate datasets and build the [comparison table](<Dataset comparison.md>). Assess what each dataset could become after a preparation procedure similar to EuroSafeGuard's, using Sid's [data notes](<My actual notes.pdf>) and the paper's [Sections 4.1 and 4.2](<EuroSafeGuard.pdf>) as the methodological reference.

The [project proposal](<Project Proposal.pdf>) concerns adapting constitutional classifiers to value-related categories, such as gender bias and democratic versus authoritarian values. Borrow the data-building procedure without assuming that every dataset should use EuroSafeGuard's harm categories or harmful/benign labels. A short contents description and miscellaneous notes are enough to describe domain-specific issues for now.

## How to use it

- Sid directs which datasets to inspect. Work through candidates in discussion; this guide does not initiate a dataset search.
- Start with a preliminary review of the paper, dataset card and documentation. Record questions requiring actual sample inspection, downloads or experiments for a later deep dive.
- Treat the questions as loose prompts, not a scoring rubric or a fixed schema. Use numbers, brief bullets, explanations, links and caveats as appropriate. Combine or omit questions that do not fit a dataset.
- Assess potential after preparation. Distinguish what already exists from what we propose to generate, relabel or transform.
- A candidate may primarily support training or benchmarking. Discuss whether the other role is feasible and whether another dataset could complement it.
- Separate source claims, our assessment and unknowns. Include source locations where available. Missing information means unverified, not absent or satisfactory.
- Do not assume a large number of generated rows means broad coverage of independent behaviours. Keep counts appropriate to the dataset's structure.
- Generation, checking and augmentation are feasibility questions at this stage. Do not execute paid model calls without an explicit instruction to run them.

## Questions for the preliminary comparison

1. **Contents:** What does the dataset contain, and what does one item represent? Briefly describe the topic, task, format and available labels or responses.
2. **Possible roles:** What could it become for classifier training or benchmarking? Which is the stronger initial use, and how feasible is the other?
3. **Size and structure:** What counts matter here: behaviours, scenarios, questions, prompts, replies, pairs, annotations, sources or splits? What counts are known before and after filtering or expansion?
4. **Licensing and access:** What is permitted for training, creating derivatives and publishing the resulting training data or benchmark? Note access conditions, upstream restrictions and anything not verified.
5. **Collection and provenance:** Where did the data come from? How was it collected or generated, and what annotation, checking or human review is documented?
6. **Collection integrity:** What documented strengths, limitations or possible shortcuts affect trust in the data? Consider duplicates, source effects, generator style or collection artefacts where relevant.
7. **Reputation and scrutiny:** Who produced it? What research uses, independent validation, criticisms or known limitations are documented? Keep reputation separate from demonstrated quality.
8. **Taxonomy:** How could its existing categories or labels inform a constitution or task taxonomy? What is already usable, and what adaptation would be needed?
9. **Underlying behaviours:** Can we identify units to expand and hold out, such as behaviours, scenarios or questions? How much reconstruction or grouping would be necessary?
10. **Example generation:** Could those units produce useful new prompts and, where needed, replies? Could the relevant classes be represented across topics and generators without introducing obvious shortcuts?
11. **Checking:** How could existing and generated examples be checked against their intended labels? Note available rubrics, judges, human checks and the independence of any proposed checker.
12. **Paraphrasing:** Could paraphrases or natural variations expand the data while preserving the intended task and label? What checking would this require?
13. **Attack variants:** Could we construct useful adversarial or challenging variants? Which transformations fit this task, and could comparable transformations be applied across the relevant classes?
14. **Room for expansion:** What additional coverage might preparation provide, beyond increasing the row count? What limits, uncertainties or diminishing returns are foreseeable?
15. **Benchmark applicability and overlap:** What would a meaningful test measure? Could behaviours, scenarios, topics, sources, generators or attack methods be held out? Note overlap with possible training data and any complementary benchmark needed.
16. **Preparation effort:** What are the likely cleaning, conversion, generation, checking and manual-work requirements? Give rough costs or timings only where evidence supports them; otherwise describe bottlenecks qualitatively.
17. **Related datasets:** What alternatives or complements are mentioned in the sources or already known to us? Explain their relationship, possible overlap and how they might fill a training or benchmark gap.
18. **Pros, cons and miscellaneous:** What are the main advantages, drawbacks and unresolved points for this project? What should a later deep dive establish?

## Recording an inspection

Use one row per dataset in each part of the comparison table. The repeated dataset name links the parts; it does not represent separate candidates. Keep entries concise, using brief bullets or semicolon-separated notes as useful. Link to longer discussion notes only if needed.

The EuroSafeGuard entry is a reference description of the procedure and data already reported in Sid's notes. Future candidate entries should describe their potential and the work required, rather than assume that procedure has already been applied. Do not rank candidates automatically or require them to fulfil every category.
