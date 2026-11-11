AICS-202 | Adversarial Machine Learning — Practical Lab Pack & Assessment DossierCourse Code: AICS-202Subject: Applied Adversarial Machine Learning & DefenseAuthor / Examiner: Yawukal Melaku FentawCurriculum Origin: Original training exercises designed by the International Cybersecurity and Digital Forensics Academy (ICDFA).📋 Table of ContentsOverviewRepository StructureEnvironment Setup & InstallationLaboratory Curriculum & SummaryLab Safety & Compliance NoticeEvidence Artifacts & DeliverablesAcknowledgments & Source Attribution🔭 1. OverviewThis repository hosts the complete practical lab pack, executable Jupyter notebooks, and formal technical assessment dossier for AICS-202: Adversarial Machine Learning.The course investigates security weaknesses, threat modeling, inference-time evasion vulnerabilities, training-time data integrity risks, and defense limits for machine learning classifiers using a controlled, offline local sandbox (scikit-learn digits dataset).📁 2. Repository StructureAICS-202-Adversarial-ML-Dossier/
├── notebooks/
│   ├── AICS202_Lab01_Baseline_Threat_Model.ipynb
│   ├── AICS202_Lab02_FGSM_Evasion.ipynb
│   ├── AICS202_Lab03_Poisoning_Data_Integrity.ipynb
│   └── AICS202_Lab04_Robustness_Defences.ipynb
├── report/
│   └── AICS202_Final_Assessment_Report.md
└── README.md
⚙️ 3. Environment Setup & InstallationThe code executes inside a local Python virtual environment (developed and tested in Ubuntu WSL). Follow these steps to configure your workspace:Clone the repository:git clone https://github.com/YawukalMelaku/AICS-202-Adversarial-ML-Dossier.git
cd AICS-202-Adversarial-ML-Dossier
Create and activate a virtual environment:python -m venv .venv
# On Linux / WSL:
source .venv/bin/activate
# On Windows (Command Prompt / PowerShell):
# .venv\Scripts\activate
Install dependencies:python -m pip install --upgrade pip
python -m pip install numpy scikit-learn matplotlib notebook
Launch Jupyter Notebook:python -m notebook
Work sequentially from Lab 01 to Lab 04. Each notebook is self-contained with no external dataset downloads required.🧪 4. Laboratory Curriculum & SummaryLab 01 – Baseline & Threat Modeling: Establishes a multi-class multinomial logistic regression baseline using offline $8 \times 8$ grayscale digit matrices ($\sim$96.22% clean accuracy) accompanied by a formal threat model worksheet.Lab 02 – FGSM Evasion: Implements white-box Fast Gradient Sign Method (FGSM) gradient attacks and measures accuracy degradation across increasing per-pixel perturbation budgets ($\epsilon = 0.00$ to $0.18$).Lab 03 – Training-Label Poisoning: Simulates data integrity compromise via random label corruption ($0\%$ to $20\%$ training set alteration) and establishes an upstream data governance control register.Lab 04 – Defensive Retraining & Adaptive Evaluation: Evaluates adversarial data augmentation against adaptive multi-step Projected Gradient Descent (PGD) attacks and provides a formal risk decision memo.🛡️ 5. Lab Safety & Compliance NoticeStrictly Educational Sandbox Use:Run these notebooks exclusively against your own locally trained models and the bundled scikit-learn digits dataset. Do not deploy or test adversarial attack scripts against real-world production systems, third-party services, or external APIs without explicit, written authorization.📊 6. Evidence Artifacts & DeliverablesAll lab sessions generate verifiable execution outputs, performance curves, confusion matrices, and risk notes. The final dossier report (report/AICS202_Final_Assessment_Report.md) compiles these findings for formal E-Campus submission.✍️ 7. Acknowledgments & Source AttributionExercises & Curriculum: Designed by the International Cybersecurity and Digital Forensics Academy (ICDFA).Execution & Dossier Preparation: Completed and documented by Yawukal Melaku Fentaw.
