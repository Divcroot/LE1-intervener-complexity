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

Treebanks are NOT included in this repo due to file size.
Download the following UD v2.x training splits

| File | Language |
|------|----------|
| en_ewt-ud-train.conllu | English |
| de_gsd-ud-train.conllu | German |
| es_gsd-ud-train.conllu | Spanish |
| ru_syntagrus-ud-train.conllu | Russian |
| ar_padt-ud-train.conllu | Arabic |
| hi_hdtb-ud-train.conllu | Hindi |
| tr_boun-ud-train.conllu | Turkish |
| fi_tdt-ud-train.conllu | Finnish |
| ja_gsd-ud-train.conllu | Japanese |
| zh_gsd-ud-train.conllu | Chinese |
| eu_bdt-ud-train.conllu | Basque |
| grc_proiel-ud-train.conllu | Ancient Greek |

## Files
- `LE1_analysis.ipynb` — main analysis notebook
- `conditional_distribution.csv` — calculated conditional prob
- `summary_table.csv` — per-language summary statistics
