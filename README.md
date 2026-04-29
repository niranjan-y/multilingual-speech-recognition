# Multilingual Automatic Speech Recognition using Wav2Vec 2.0

## 📌 Overview

This project implements a multilingual Automatic Speech Recognition (ASR) system using Wav2Vec 2.0 for converting speech into text across multiple languages.

## 🚀 Features

* Multilingual speech-to-text transcription
* Audio preprocessing (resampling, normalization)
* Transformer-based ASR using Wav2Vec 2.0
* Model evaluation using Word Error Rate (WER)

## 🛠️ Tech Stack

* Python
* PyTorch
* Hugging Face Transformers
* Librosa

## 📂 Project Structure

* `src/` → preprocessing, training, evaluation
* `notebooks/` → experiments
* `models/` → trained models
* `outputs/` → predictions

## ⚙️ Installation

```bash
git clone https://github.com/your-username/multilingual-asr-wav2vec2.git
cd multilingual-asr-wav2vec2
pip install -r requirements.txt
```

## ▶️ Usage

```bash
python src/inference.py --audio sample.wav
```

## 📊 Evaluation

Model performance is evaluated using Word Error Rate (WER).

## 📁 Dataset

(Add dataset used, e.g., Mozilla Common Voice)

## 📈 Future Improvements

* Support for more languages
* Fine-tuning on low-resource datasets
* Real-time transcription system

## 🤝 Contributions

Open to contributions and improvements!
