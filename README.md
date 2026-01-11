# Adversarial Prompting for Sycophancy Detection

**Apart Research AI Manipulation Hackathon (January 2026)**

This repository contains code and data for detecting social sycophancy in LLM outputs using adversarial span annotation. 

## Overview

Our hackathon project presents two complementary methods for sycophancy detection:
1. **Adversarial span annotation** — generating sycophantic, antagonistic, and "ground truth" response variants, then using LLM span labeling to identify and quantify sycophantic text
2. **Multi-turn analysis** — examining how models shift positions under adversarial pressure - by Pranati Modomudi.  This is code available at [github.com/pranmod01/anti-syco-detect](https://github.com/pranmod01/anti-syco-detect)


## Repository Contents

- `sycomatic.py` — Backend for the interactive prototype (highlights sycophantic spans in real-time)
- `Sycomatic - Hackathon Data Generation.ipynb` — Google Colab notebook for running evaluation pipeline ([View on Colab](https://colab.research.google.com/drive/1FbdFc1S0XPdLmxZsBEfcrIyBnlYIrShs?usp=sharing))
- JSON results from evaluation runs on 150 ELEPHANT prompts + 50 hand-curated prompts

## Interactive Demo

[Link to live demo](https://jolly-otter-heals-k3ptbg.solve.it.com/) (available during evaluation period)

## Citation

If you use this work, please cite our hackathon report.