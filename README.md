# LE1 — Asymmetric Intervener Complexity in Dependency Structures

**Authors:** Jatin Madan (220475) & Divyanshu Chauhan (220380)

## Overview
Analysis of intervener POS composition across 12 languages using
Universal Dependencies treebanks. Tests three hypotheses about how
head type, dependency direction, and distance shape intervener composition.

## Languages
English, German, Spanish, Russian, Arabic, Hindi, Turkish,
Finnish, Japanese, Chinese, Basque, Ancient Greek

## Requirements
```bash
pip install pandas numpy scipy matplotlib seaborn conllu
```

## Data
Download UD treebanks from https://universaldependencies.org/

## Files
- `LE1_analysis.ipynb` — main analysis notebook
- `interveners_enhanced.csv` — extracted intervener dataset
- `summary_table.csv` — per-language summary statistics
