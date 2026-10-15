# AI-Powered Medical Image Analysis — Educational Demo

A beginner-friendly Python project demonstrating grayscale image preparation, normalization, feature extraction, classification, evaluation, and visualization.

## Medical safety note
The default project creates **synthetic grayscale patterns**, not real X-rays, MRI scans, CT scans, or patient data. Labels are **Pattern A** and **Pattern B**, not diseases. This model is not clinically validated and must never be used to diagnose, rule out, or guide treatment for a medical condition.

## Workflow
1. Generate synthetic grayscale patterns.
2. Normalize pixels to 0–1.
3. Extract HOG (Histogram of Oriented Gradients) features.
4. Train a baseline Logistic Regression classifier.
5. Evaluate using accuracy, classification report, and confusion matrix.
6. Save a model, reports, sample images, and plots.

## Folder structure
```text
AI-Powered-Medical-Image-Analysis/
├── data/synthetic_samples/
├── src/medical_image_demo.py
├── models/
├── outputs/
├── images/
├── docs/PROJECT_NOTES.md
├── main.py
├── requirements.txt
└── README.md
```

## Run on Windows
```powershell
py -m venv .venv
.venv\Scripts\activate
python -m pip install --upgrade pip
pip install -r requirements.txt
python main.py
```

## Run on macOS/Linux
```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
python main.py
```

<img width="720" height="1570" alt="WhatsApp Image 2026-10-15 at 19 38 49" src="https://github.com/user-attachments/assets/2c15eab9-b3af-4d4c-898e-fb94f0df4f38" />
