# Measure the Disorder Field First

**A pre-experimental heuristic for the graphene–ferroelectric photonic-memory stack**

A working paper. Nils Haaland, May 2026.

---

## What this is, in one paragraph

Silicon photonics already has a mature framework for predicting circuit yield from
wafer-scale fabrication variability — spatial variation modeled as a correlated random
field, decomposed by length scale, propagated to yield (Bogaerts and co-workers,
2015–2019). That framework, not single-cell "hero" metrics, is the right tool for asking
whether a graphene–ferroelectric photonic-memory array can be manufactured. **This paper
does not reinvent it, and does not claim it is deficient.** No working cell exists and the
standard model has not been tried against one, so there is no demonstrated gap. What the
paper offers is narrower and more honest: a **measurement heuristic** — which quantity to
characterize *first*, before committing an expensive wafer — plus one **falsifiable
hypothesis** about what that measurement might reveal.

## The ask (the useful part)

Measure a spatial carrier-density correlation length **L_corr**, **decomposed** into its
sources, **before and after a switching cycle**. This is a Monday-morning experiment for
any group with KPFM / piezoresponse / scanning-photocurrent metrology — the imec /
Graphene Flagship and CamGraPhIC groups already have both the wafer-scale process and the
variability tooling. Nobody has reported L_corr for this stack at all.

## The hypothesis (and its most likely fate)

The paper raises — but does **not** assert — the possibility that graphene transfer
wrinkles mechanically pin ferroelectric domain walls, so that part of the carrier-density
disorder is re-imprinted on every write cycle (a term a static wafer map cannot capture).
**The most probable outcome of the proposed measurement is null:** if the disorder is
short-correlated and the pre/post-switch maps match, the existing framework needs no
change and the hypothesis is simply wrong. That null result is still worth publishing,
because the measurement has never been made.

## Contents

- [`index.html`](index.html) — web version (enable GitHub Pages to view rendered)
- [`Haaland_MissingDisorderTerm_2026.pdf`](Haaland_MissingDisorderTerm_2026.pdf) — typeset PDF
- `Haaland_MissingDisorderTerm_2026.tex` — LaTeX source

## Status & honesty notes

This is a **working paper**, not a peer-reviewed result. No working graphene-gated
ferroelectric photonic memory cell has been demonstrated; the quality thresholds are
hypotheses for a 64×64 tile that has not been built, and the route bands are
order-of-magnitude inferences, not yield predictions. Reference DOIs and venues are being
verified against originals before any formal submission.

The paper was developed through adversarial review across several independent model
critiques. An earlier draft over-claimed — it titled itself around a "missing disorder
term" as though the gap were established. A reviewer correctly called this "a premature
solution looking for a problem"; that criticism is credited in the Acknowledgements and is
directly responsible for the present, demoted framing. The method note explains why
agreement was treated as a liability rather than a signal.

## License

[CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) — public domain
