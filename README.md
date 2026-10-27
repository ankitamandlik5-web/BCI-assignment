# 🧠 Motor Imagery Brain-Computer Interface (BCI)

**Student Name:** Ankita Mandlik  
**Project:** BCI Practical Lab 4

An end-to-end signal processing and machine learning pipeline for decoding Left vs. Right Hand motor imagery from raw EEG data. The pipeline is visualized using an interactive Gradio dashboard.

## 🚀 Pipeline Features
- **Preprocessing:** 8-30 Hz Butterworth Bandpass filtering.
- **Artifact Removal:** Independent Component Analysis (ICA) to remove eye blinks.
- **Feature Extraction:** Common Spatial Patterns (CSP).
- **Classification:** Linear Discriminant Analysis (LDA) with 3-fold Cross-Validation.
- **Real-Time Simulation:** 500ms sliding window buffer with < 1ms latency benchmarking.

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/bci-motor-imagery-lab.git
   cd bci-motor-imagery-lab


## Requirements
mne>=1.6.0
scikit-learn>=1.4.0
numpy>=1.26.0
scipy>=1.11.0
matplotlib>=3.8.0
gradio>=4.0.0
Pillow>=10.0.0
