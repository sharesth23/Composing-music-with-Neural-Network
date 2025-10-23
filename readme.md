# Composing music with Neural Network :

> *“Where deep learning learns to compose like Bach.”*

This project explores how neural networks can **generate music in the style of Johann Sebastian Bach** using the **Kaggle Bach MIDI Dataset**.  
By training recurrent models on Bach’s compositions, the system learns musical structure, rhythm, and harmonic progression — allowing it to compose original, Bach-style melodies.

---

## 🧠 Project Overview

🎹 **Goal:**  
Use **Recurrent Neural Networks (RNN/LSTM)** to generate music sequences similar to Bach’s compositions.

📂 **Dataset:**  
[Kaggle — Bach MIDI Dataset](https://www.kaggle.com/datasets)  
Contains over 400+ Bach chorales and pieces in MIDI format, perfect for sequence learning.

🧩 **Key Idea:**  
Model learns patterns of musical notes, timing, and harmony to predict the next note, creating an AI-driven composer.

---

## 🧰 Tech Stack

| Component | Technology |
|------------|-------------|
| Programming Language | Python 3.10+ |
| Deep Learning | TensorFlow / Keras |
| Data Processing | `music21`, `mido`, `numpy` |
| Visualization | `matplotlib`, `seaborn` |
| Dataset | Bach MIDI Dataset (Kaggle) |


---
## 🧩 Pipeline Diagram
    flowchart TD
    A[Bach MIDI Dataset 🎼] --> B[Preprocessing — Extract Notes 🎵]
    B --> C[LSTM Neural Network 🧠]
    C --> D[Predict Next Note Sequence 🔁]
    D --> E[Generate MIDI File 🎧]
    E --> F[Play AI-Composed Bach Music 🎹]
---






