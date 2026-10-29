# Digital Signal Processing (DSP) in Python 🚀

This repository contains practical implementations of various Digital Signal Processing (DSP) experiments using Python (NumPy, SciPy, and Matplotlib). 

---

## 📂 Experiments & Simple Definitions# Digital Signal Processing (DSP) Lab in Python 🚀

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

### 5. Z-Transform and ROC (Region of Convergence)
* **What it is:** A powerful mathematical tool that converts discrete-time signals from the time domain into the complex frequency domain (Z-domain) to analyze system stability and causality[cite: 20, 23].
* **Key Concept:** The Region of Convergence (ROC) determines whether a system is stable (includes the unit circle) and causal (extends outward from the outermost pole)[cite: 2, 38, 39].

### 6. Discrete Fourier Transform (DFT)
* **What it is:** An algorithm used to convert a finite sequence of equally-spaced time-domain samples into the frequency domain[cite: 11].
* **Key Concept:** It helps analyze the frequency components of a signal (such as identifying tones or noise in audio signals) and is closely related to filter design and spectrum analysis[cite: 11, 12, 17].

---

## 🛠️ Requirements
Make sure you have Python installed along with these libraries:
```bash
pip install numpy matplotlib scipy

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
