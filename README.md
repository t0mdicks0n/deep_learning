# Simple PyTorch Experiments 🧠

A collection of beginner-friendly PyTorch models built to learn the fundamentals of Deep Learning.

## Projects

### 1. Swedish Name Classifier (RNN/LSTM)
A model that predicts if a Swedish name is a **Boy** or a **Girl**.
- **Architecture:** LSTM (Long Short-Term Memory)
- **Input:** Character-level sequences (One-Hot Encoded)
- **Learned Features:** Successfully learned Swedish phonetics (e.g., double consonants like "ss" in *Nisse* = Boy).

### 2. Quadrant Detector
A simple Feedforward Neural Network.
- **Goal:** Predict if a coordinate `(x, y)` is in the top-right quadrant.
- **Key Concepts:** Sigmoid activation, Binary Classification.

## How to Run

1. **Install Dependencies:**
```bash
pip install -r requirements.txt
```

2. **Open the Notebooks:**
```bash
jupyter notebook
```