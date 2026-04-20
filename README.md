# audio-deepfake-detection
Audio Deepfake Detection: 
1. ML (SVM + MFCC/Mel)
2. Deep Learning
3. Robustness in noisy environments (Open Problem).



## 🔬 Project Structure

The project is organized into **three core pillars**, each addressing the detection challenge from a different technical perspective:

---

### 1. Classical Machine Learning (Baseline)
We established a solid performance baseline using traditional statistical models.

* **Feature Extraction:** Audio signals were transformed into **MFCCs** (Mel-frequency cepstral coefficients) and **Mel-Spectrograms** for frequency-domain analysis.
* **Classifier:** Implementation of a **Support Vector Machine (SVM)** to validate the effectiveness of the extracted features in distinguishing between synthetic and natural speech.

---

### 2. Deep Learning Approach
*Evolution of the detection system through advanced neural architectures.*

> ⚠️ **Note:** This section is currently under development. It will be updated with details regarding **CNNs** for spectrogram analysis and **RNN/LSTM** models for temporal sequence processing as the code is uploaded.

---

### 3. Open Problem: Robustness in Noisy Environments
The experimental core of this project focuses on a critical real-world challenge.

* **The Issue:** Most detection models suffer from a drastic performance drop when exposed to background noise, making them unreliable in non-laboratory settings.
* **Analysis:** We conducted an evaluation of system resilience under various **acoustic disturbance conditions**, aiming to bridge the gap between controlled environment tests and real-world application scenarios.
