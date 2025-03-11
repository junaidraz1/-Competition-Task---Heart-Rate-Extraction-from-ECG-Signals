# 🏆 Heart Rate Extraction from ECG Signals

This repository contains my solution for the **Competition Exercise: Heart Rate Extraction from ECG Signals**. The objective is to extract **heart rate (HR) values** from ECG signals while minimizing the **mean absolute error (MAE)** compared to the provided ground truth HR values.

---

## 📌 Objective
The goal of this assignment is to develop a function that accurately extracts **heart rate (HR) values** from ECG signals using methods covered in the course named Analytics of Health Wearables.

---

## 📂 Dataset Details
- 📊 The dataset consists of **200 ECG segments**.
- ⏱️ Each segment is **30 seconds** long.
- ⚡ Signals are sampled at **200 Hz**.
- 📈 **Ground truth HR values** are provided for evaluation.
- 🗂️ The data is stored in a **.pkl file**, with a template notebook available for loading.

---

## 🛠️ Implementation Details
The implementation follows these key steps:

1. **Preprocessing:** Signal filtering and noise reduction.
2. **Peak Detection:** Identifying R-peaks from the ECG signal.
3. **HR Calculation:** Estimating beats per minute (BPM) based on detected R-peaks.
4. **Error Minimization:** Optimizing to reduce **MAE** against the ground truth.
