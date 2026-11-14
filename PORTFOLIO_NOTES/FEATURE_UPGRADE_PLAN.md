# DSPy Fork — Feature and Research Plan

## Objective

Demonstrate a reproducible, metric-driven language-model program using the upstream DSPy framework, then contribute focused improvements through the upstream process.

## P0 — learn and establish a baseline

- [ ] Study the upstream architecture and keep a short local map of modules and supported public APIs.
- [ ] Build a small reproducible DSPy program with a public/licensed dataset and a task-specific metric.
- [ ] Compare a baseline prompt/program with one DSPy optimizer under fixed seeds and budget.

## P1 — useful experiments

- [ ] Add a small example with typed inputs/outputs, explicit metric and deterministic evaluation set.
- [ ] Record optimizer settings, model/provider, budget, seeds and result variance.
- [ ] Explain failure cases and where DSPy abstractions help or hurt.

## P2 — upstream contributions

- [ ] Add local benchmark scripts or examples only in clearly separated portfolio paths; avoid broad rewrites of upstream code.
- [ ] For upstream fixes, create focused patches and follow the upstream contribution process.

## Definition of done

- [ ] Examples run from a fresh environment.
- [ ] Evaluation set and licence are documented.
- [ ] Results compare against a simple baseline under equal budgets.
- [ ] Local changes are isolated from upstream-maintained code.
- [ ] Upstream PRs are separately linked and their status is exact.
