# NH-project-for-Software-Technology1
Any projects or assignments for Software Technology1.

# UC Programming Lab Submissions (Week 4 & Week 5)

This repository contains my lab submissions uploaded as ZIP files (as required for in-class lab demo / GitHub link submission).

## Files in this repository
- `Week_4_Lab_Acitivities.zip`
  - Week 4: Tkinter + Pillow tasks (Task 1–7)
  - Includes: Python scripts, Assets folder, and `Week_4_lab_report.pdf` inside the ZIP

- `Week_5_Lab_Acitivities.zip`
  - Week 5: NumPy + OpenCV tasks (Task 1.1–1.10 and Task 2.1–2.10)
  - Includes: Python scripts, report document, and required sample images inside the ZIP

> Note: Code is intentionally kept inside ZIPs because the assessment requires exporting the project as a ZIP file and uploading it to GitHub.

---

## How to run (after downloading & extracting)

### 0) Extract the ZIP
Download the ZIP file from GitHub, then extract it:
- Windows: Right-click → **Extract All**
- macOS: Double-click the ZIP

Open the extracted folder in PyCharm:
**PyCharm → File → Open → select the extracted folder**

---

## Week 4 (Tkinter + Pillow)

### Requirements
- Python 3.x
- Pillow
  ```bash
  python -m pip install Pillow

## Week 6 – Case Study 3 (Keras & Google Colab) – Task 1_5 to 1_7

This folder includes Python scripts for Week 6 Tutorial & Lab (Case Study 3).  
For assessment, each task script was tested, the console outputs/screenshots were embedded in the Week 6 tutorial document, and the working activities were demonstrated in class before submission to GitHub. :contentReference[oaicite:8]{index=8}

### Tasks covered
- **Task 1_5 (Normalization)**: MNIST preprocessing with `ImageDataGenerator(rescale=1.0/255.0)` to scale pixel values to **0–1**. :contentReference[oaicite:9]{index=9}  
- **Task 1_6 (Centering)**: `ImageDataGenerator(featurewise_center=True)` with `datagen.fit(trainX)` to subtract the training mean (output mean ≈ 0). :contentReference[oaicite:10]{index=10}  
- **Task 1_7 (Standardization)**: `ImageDataGenerator(featurewise_center=True, featurewise_std_normalization=True)` to produce data with mean ≈ 0 and std ≈ 1. :contentReference[oaicite:11]{index=11}

### How to run (PyCharm)
1. Open the project folder in PyCharm.
2. Install dependencies (example):
   - `pip install tensorflow matplotlib pillow numpy`
3. Run each script: `task1_5.py`, `task1_6.py`, `task1_7.py`.
4. Capture console outputs as evidence for the report/documentation.
