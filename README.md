---
title: "Inner Voice EMG Interface"
author: "Jonas (@your-slack-handle)"
description: "An open-source, low-cost EMG system to classify subvocalized commands using custom hardware and machine learning."
created_at: "2024-03-20"
---
# 🧠 Inner Voice EMG Interface

What if you could talk to a computer without making a sound?

**Inner Voice EMG** is a fully open-source, DIY alternative to MIT's AlterEgo. It uses surface electromyography (sEMG) sensors to pick up signals from the jaw, throat, and neck when the user subvocalizes (i.e., silently says) words  and classifies them using a machine learning model.

---

## 🛠️ Features

- Custom-designed, through-hole EMG breakout PCB
- Up to **6 sensor channels**
- ESP32-based data collection (USB or wireless)
- Python pipeline for filtering, segmenting, and classifying signals
- Trainable on 4–10+ silent speech commands
- 100% reproducible and open-source

---

## 🧪 Current Status

| Component              | Status          |
| ---------------------- | --------------- |
| PCB Design             | 🟡 In Progress  |
| Hardware Assembly      | ⬜ Not Started  |
| Data Collection Script | 🟡 In Progress |
| ML Pipeline            | 🟡 In Progress  |
| Model Training         | ⬜ Not Started  |
| Demo Video             | ⬜ Not Started  |

---

## 🧰 Hardware

- ESP32 Dev Board
- Custom ADS1299 Breakout PCB
- Snap-on electrodes
- Jumper wires, resistors, and a mild tolerance for frustration

---

## 🧠 Machine Learning Pipeline

Planned features:

- Signal preprocessing (RMS, filtering, FFT)
- Windowing and segmentation (1.5 sec windows)
- Feature extraction
- SVM / LSTM classifier for subvocal words

---

## 🗂️ Repo Structure
