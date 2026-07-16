# Replication Package

## Psychological Safety and Interactional Behaviors in Pair Programming

This repository contains the replication package supporting the study submitted to **SBQS 2026** on psychological safety and interactional behaviors in pair programming.

The package provides the coding scheme, coded analytical data, qualitative coding examples, aggregated results, and supporting documentation used in the study.

The original pair programming transcripts are not redistributed in this repository because they belong to the third-party **PP-ind dataset**. Researchers interested in accessing the complete transcripts should consult the original PP-ind repository.

> **Review status:** This repository is intended to support anonymous peer review. Author names, affiliations, contact information, and other identifying information are intentionally omitted.

---

## Overview

The study investigates how interpersonal risk-taking behaviors emerge during pair programming and how these behaviors are received by the programming partner.

The analysis considers four main dimensions:

1. interpersonal risk-taking behavior;
2. partner response;
3. task impact;
4. psychological safety indicator.

The replication package was designed to support:

- inspection of the coding scheme;
- verification of the operational definitions;
- examination of worked coding examples;
- inspection of the final coding matrix;
- verification of the aggregated frequencies;
- traceability between the coded data and the results reported in the paper.

---

## Repository structure

```text
psychological-safety-pair-programming/
├── README.md
├── data/
│   ├── CODEBOOK.md
│   ├── CODEBOOK.md.docx
│   ├── CODING_EXAMPLES.md
│   ├── CODING_EXAMPLES.md.docx
│   ├── coded_episodes_without_excerpts.xlsx
│   └── coding_matrix.xlsx
├── documentation/
│   ├── ORIGINAL_DATASET.md
│   └── SBQS_Codebook_Psychological_Safety_Pair_Programming_v1.0.pdf
└── results/
    ├── README.md
    ├── behavior_by_ps_indicator.csv
    ├── behavior_by_response.csv
    ├── behavior_by_task_impact.csv
    ├── ps_indicator_frequencies.csv
    └── response_frequencies.csv