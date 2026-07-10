# Unique Prototype Algorithm

## Algorithm

**HoffmanFailureFirstComputerVisionDistillLoop** (`P017-Hoffman-ComputerVision`)

## Professor Alignment

- Professor: Judy Hoffman
- Research area: Computer vision + ML, domain adaptation, robustness, fairness
- Focus terms: Computer vision, domain adaptation, robustness, fairness

## Core Mechanism

This prototype prioritizes severe open violations and repair regressions for red-team follow-up.

## Decision Rule

Rank seed cases by trustworthy-specific priority score with Hoffman-aligned focus term 'Computer vision'.

## What The Code Adds

- A unique algorithm spec in `src/proposed_method.py`.
- A scoring function for the repo's `trustworthy` data schema.
- A ranked list of cases that should be reviewed, repaired, reproduced, or expanded first.
- Integration into `src/value_add.py`, so demo output includes the proposed method.

## Honest Status

This is a runnable algorithmic prototype. It is not a validated contribution to Judy Hoffman's published work until the seed data is replaced with real public/lab-relevant data and the resulting claims are evaluated.

## Run

```bash
python src/proposed_method.py
python src/value_add.py --write-report reports/demo_results.json
python -m unittest discover -s tests
```
