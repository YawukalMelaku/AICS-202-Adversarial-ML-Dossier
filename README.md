# AICS-202 | Adversarial Machine Learning — Practical Lab Pack

Original ICDFA-designed training exercises, completed for the AICS-202 Adversarial Machine Learning program.

## Overview
This repository contains four self-contained Jupyter notebooks exploring machine learning security, vulnerability assessment, and defense mechanisms using a local offline dataset.

## Content
* **Lab 01:** Baseline model training and threat modeling worksheet.
* **Lab 02:** FGSM evasion testing on an offline 8x8 digit classifier.
* **Lab 03:** Training-label poisoning and data integrity controls.
* **Lab 04:** Defensive retraining and adaptive robustness evaluation.

## Setup
```bash
python -m venv .venv
# Activate .venv using your operating system instructions (e.g., source .venv/bin/activate)
python -m pip install -r requirements.txt
python -m notebook
