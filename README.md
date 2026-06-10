# Multilingual Automatic Speech Recognition using Wav2Vec2 XLS-R

## 📌 Overview

This project implements a Multilingual Automatic Speech Recognition (ASR) system using Facebook's Wav2Vec2 XLS-R 300M model and the Google FLEURS dataset.

The system is designed to transcribe speech from multiple languages including:

- Hindi
- Telugu
- Tamil
- Kannada
- English

The model is fine-tuned using Hugging Face Transformers and evaluated using Word Error Rate (WER).

---

## 🚀 Project Highlights

- Built a multilingual speech-to-text system
- Fine-tuned Wav2Vec2 XLS-R 300M
- Created multilingual character-level vocabulary
- Trained on Google FLEURS dataset
- Implemented multilingual preprocessing pipeline
- Evaluated model performance using WER
- Integrated Hugging Face model versioning and checkpoint recovery

---

## 🛠️ Tech Stack

- Python
- PyTorch
- Hugging Face Transformers
- Hugging Face Datasets
- Google FLEURS
- Librosa
- Evaluate
- JiWER

---

## 🌍 Supported Languages

| Language | Code |
|----------|------|
| Hindi | hi_in |
| Telugu | te_in |
| Tamil | ta_in |
| Kannada | kn_in |
| English | en_us |

---

## 📂 Repository Structure

```text
multilingual-speech-recognition/
│
├── Multilingual_ASR_XLS_R_v2.ipynb
├── README.md
├── requirements.txt
└── screenshots/
