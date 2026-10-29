## Digital Signal Processing (DSP) in Python 🚀

This repository contains practical implementations of various Digital Signal Processing (DSP) experiments using Python (NumPy, SciPy, and Matplotlib). 

---

## 📂 Experiments & Simple Definitions

### 1. Effect of Convolution on Discrete-time Signal
* **What it is:** Convolution combines two signals to produce a third signal, showing how a system alters an input.
* **Key Concept:** The output length is always equal to $N + M - 1$ (where $N$ and $M$ are the lengths of the two signals).

### 2. Effect of Correlation on Discrete-time Signal
* **What it is:** Correlation measures how similar two signals are to each other or how a signal matches a time-shifted version of itself (Auto-correlation / Cross-correlation).
* **Key Concept:** Helps find matching patterns, time delays, and signal energy at lag zero.

### 3. Sampling and Quantization
* **What it is:** The process of converting smooth, continuous-world signals into digital, step-by-scale numbers that computers can understand.

### 4. FIR and IIR Filters
* **What it is:** Filters are used to clean up signals by removing unwanted noise and keeping only the useful frequencies (e.g., Lowpass filters).
* **FIR:** Uses no feedback, highly stable, and introduces a predictable linear delay.
* **IIR:** Uses feedback, highly efficient, and achieves sharp filtering with fewer coefficients.

---

## 🛠️ Requirements
Make sure you have Python installed along with these libraries:
```bash
pip install numpy matplotlib scipy
