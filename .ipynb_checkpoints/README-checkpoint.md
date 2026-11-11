# ICDFA AICS-202 - Practical Lab Pack

Original ICDFA-designed training exercises, dated October 2026.

## Content
- Lab 01 - Baseline and threat model
- Lab 02 - FGSM on an offline 8x8 digit classifier
- Lab 03 - Training-label poisoning and data integrity
- Lab 04 - Defensive retraining and adaptive robustness evaluation

## Setup
```bash
python -m venv .venv
# Activate .venv using your operating system instructions
python -m pip install -r requirements.txt
python -m notebook
```

Work sequentially from Lab 01 to 04. Each notebook is self-contained. No external dataset downloads are needed.

## Lab safety
Run the notebooks only against your own locally trained classifiers and the bundled scikit-learn digits dataset. Do not test real-world systems without written authorization.

## Evidence
Keep notebook outputs, screenshots, short risk analyses and a reproducible run record.

## Authors / source acknowledgements
ICDFA-created notebooks. External technical sources are cited in the accompanying laboratory guide; source code here is originally written for training.
