# A Missing Disorder Term

**Extending photonic variability-yield models to the graphene–ferroelectric memory stack**

A pre-experimental working paper. Nils Haaland, May 2026.

---

## The claim, in one paragraph

Silicon photonics already has a mature framework for predicting circuit yield from wafer-scale fabrication variability — spatial variation modeled as a correlated random field, decomposed by length scale, propagated to yield (Bogaerts and co-workers, 2015–2019). That framework, not single-cell "hero" metrics, is the right tool for asking whether a graphene–ferroelectric photonic-memory array can be manufactured. This paper does not reinvent it. It argues the framework is missing **one term** for this material system: because graphene transfer artifacts can mechanically pin ferroelectric domain walls, part of the carrier-density disorder is **re-imprinted on every write cycle** — an active, switch-coupled term with no analog in silicon geometric variability, invisible to a static wafer map. The paper names the measurement that would parameterize it.

## The measurement (the ask)

A spatial carrier-density correlation length **L_corr**, measured **before and after a switching cycle** and **decomposed** into its sources (ferroelectric texture vs. graphene transfer morphology). This is a Monday-morning experiment for any group with KPFM / piezoresponse / scanning-photocurrent metrology — the imec / Graphene Flagship and CamGraPhIC groups already have both the wafer-scale process and the variability tooling.

The paper is built to be **falsified**: if short-scale disorder dominates L_corr and the pre/post-switch maps are identical, the existing static-map framework suffices unmodified and the central premise is wrong. That is the intended outcome of Experiment 1 if the switch-coupled term turns out to be negligible.

## Contents

- [`index.html`](index.html) — web version (GitHub Pages)
- [`Haaland_MissingDisorderTerm_2026.pdf`](Haaland_MissingDisorderTerm_2026.pdf) — typeset PDF
- `Haaland_MissingDisorderTerm_2026.tex` — LaTeX source

## Status & honesty notes

This is a **working paper**, not a peer-reviewed result. No working graphene-gated ferroelectric photonic memory cell has been demonstrated; the quality thresholds are hypotheses for a 64×64 tile that has not been built, and the route bands are order-of-magnitude inferences, not yield predictions. Reference DOIs and venues are being verified against originals before any formal submission.

Developed through adversarial review across multiple independent model critiques; the method note in the paper explains how, and why agreement was treated as a liability rather than a signal.

## License

[CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) — public domain. Use freely, no attribution required.
