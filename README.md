# Medical-Imaging-Segmentation-AI

AI-Driven Sacroiliitis Detection & Segmentation 🏥 🧠
This project leverages State-of-the-Art (SOTA) Computer Vision to assist in the diagnosis of Sacroiliitis. Developed as part of a research initiative at the University of São Paulo (USP), the system uses the YOLO architecture implemented in PyTorch to identify and segment inflammatory lesions in medical imaging.

 Overview
Early diagnosis of sacroiliitis is a clinical challenge, often delayed by years due to the subtlety of initial findings. This project aims to:

Automate the detection of inflammatory markers.

Segment affected areas to quantify disease progression.

Support clinical decision-making, reducing the "time-to-diagnosis" for patients.

 Technical Stack
Language: Python

Deep Learning Framework: PyTorch

Model Architecture: YOLO (You Only Look Once) for real-time instance segmentation.

Data Processing: OpenCV, NumPy, Pandas.

 Methodology
Data Acquisition: Images sourced from University of São Paulo (USP) medical databases (fully anonymized).

Labeling: Precise manual annotation of sacroiliac joint lesions.

Training: Hyperparameter tuning of YOLO models to handle the high class imbalance and low contrast typical of medical images.

Evaluation: Models are evaluated using mAP (mean Average Precision), Dice Coefficient, and clinical validation.

 Project Structure
Plaintext

├── notebooks/          # Training logs and exploratory data analysis
├── src/                # Preprocessing and inference scripts
├── weights/            # Model checkpoints (omitted)
└── requirements.txt    # Environment dependencies
 About the Author
[Henrique lima]

Medical Student at the University of São Paulo (USP).

Researcher with a PUB-USP Grant (Unified Scholarship Program).

Focusing on the intersection of Healthcare & Deep Learning to create scalable diagnostic tools for Brazil.
