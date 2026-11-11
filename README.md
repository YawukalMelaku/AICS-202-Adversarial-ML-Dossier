Original ICDFA-designed training exercises, completed for the AICS-202 Adversarial Machine Learning program.

Overview
This repository contains four self-contained Jupyter notebooks exploring machine learning security, vulnerability assessment, and defense mechanisms using a local offline dataset.

Content
Lab 01: Baseline model training and threat modeling worksheet.
Lab 02: FGSM evasion testing on an offline 8x8 digit classifier.
Lab 03: Training-label poisoning and data integrity controls.
Lab 04: Defensive retraining and adaptive robustness evaluation.

Setup
python -m venv .venv
# Activate .venv using your operating system instructions (e.g., source .venv/bin/activate)
python -m pip install -r requirements.txt
python -m notebook

Work sequentially from Lab 01 to 04. Each notebook is self-contained and uses only the bundled scikit-learn digits dataset; no external dataset downloads are required.

Lab Safety
Run the notebooks only against your own locally trained classifiers and the bundled scikit-learn digits dataset. Do not test real-world systems without written authorization.

Evidence
Includes notebook execution outputs, performance curves, risk analyses, and the final assessment dossier report.

Authors / Source Acknowledgments
Exercises designed by the International Cybersecurity and Digital Forensics Academy (ICDFA)[cite: 1]. Completed and documented by Yawukal Melaku Fentaw.
