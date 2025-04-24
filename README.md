# ANC
Here's a polished and professional **README** section for your GitHub repository:

---

# 🎧 Real-Time Active Noise Cancellation using RNNoise on Raspberry Pi

## Overview

This project implements a **real-time Active Noise Cancellation (ANC)** system using the **RNNoise** deep learning model. Designed for low-power embedded platforms like the **Raspberry Pi 4B+**, the system captures live audio via a microphone, applies machine learning–based noise suppression, and plays back the enhanced signal in real-time with minimal latency.

It showcases the integration of **Recurrent Neural Networks (GRUs)** for efficient and adaptive audio enhancement, making it ideal for applications such as voice communication, smart assistants, telepresence, and hearing support systems.

---

## 🔍 Key Features

- **Low-latency Real-Time Noise Cancellation**  
  Utilizes RNNoise with a multithreaded pipeline for seamless live audio processing on Raspberry Pi.

- **Embedded Deployment**  
  Optimized for **Raspberry Pi 4B+**, demonstrating the feasibility of deploying AI-powered ANC in edge devices.

- **Visualization and Analysis**  
  Includes spectrogram generation and signal analysis (RMS, ZCR, Dynamic Range) for pre/post audio comparison.

- **Robust Architecture**  
  Employs Python-based threaded design for concurrent audio capture, processing, and playback, ensuring system stability.

---

## 🧠 Technologies Used

- **Machine Learning:** RNNoise (GRU-based RNN model for speech enhancement)
- **Programming Language:** Python 3
- **Audio Libraries:** SoundDevice, SoundFile, NumPy, SciPy, Librosa
- **Visualization:** Matplotlib (for spectrograms and waveform analysis)
- **System Design:** Threading, Queue-based inter-process communication
- **Hardware:** Raspberry Pi 4B+, USB/Bluetooth Microphone, 3.5mm Earphones


## 📜 License and Attribution

This project uses [RNNoise](https://github.com/xiph/rnnoise), an open-source noise suppression library.

RNNoise is licensed under the BSD 3-Clause License. You can find the full license text [here](https://github.com/xiph/rnnoise/blob/main/COPYING).


