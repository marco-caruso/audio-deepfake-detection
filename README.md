# audio-deepfake-detection

> **Academic project** developed for the "Artificial Intelligence and Security" course at the **University of Cagliari**.

Audio Deepfake Detection: 
1. ML (SVM + MFCC/Mel)
2. Deep Learning
3. Robustness in noisy environments (Open Problem).

<br>

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

> ⚠️ **Note:** This section is currently under development. 

---

### 3. Open Problem: Robustness in Noisy Environments
The experimental core of this project focuses on a critical real-world challenge.

* **The Issue:** Most detection models suffer from a drastic performance drop when exposed to background noise, making them unreliable in non-laboratory settings.
* **Analysis:** We conducted an evaluation of system resilience under various **acoustic disturbance conditions**, aiming to bridge the gap between controlled environment tests and real-world application scenarios.
> ⚠️ **Note:** This section is currently under development.





<br>
<br>

## 📊 Dataset & Environment

### Dataset Overview: FakeAVCeleb
The agent operates on a dataset of English digital audio signals. We utilized a balanced subset of the **FakeAVCeleb** dataset, consisting of **200 audio samples** in `.mp3` format, structured as follows:

| Category | Real | Fake |
| :--- | :---: | :---: |
| **Male** | 50 | 50 |
| **Female** | 50 | 50 |

*Note: Fake samples were synthetically generated directly from the corresponding real source files.*

The audio clips vary significantly in terms of **speaker identity**, **intonation**, **duration** (ranging from approximately 3 to 15 seconds), and **overall recording quality**.

### Environment Properties
According to AI agent theory, the task environment is characterized as follows:

* **Partially Observable:** The agent has access to the provided audio signals and their extracted features but lacks information regarding the original source or the exact recording context.
* **Stochastic:** Audio inputs exhibit high variability, containing potential noise or artifacts. The model's behavior may not be strictly deterministic due to the complexity of the signal and the model's architecture.
* **Static:** Each audio file is analyzed individually. The system does not interact with an evolving or dynamic environment during the classification process.
* **Discrete:** In terms of actions, the model performs a **binary decision** (Real vs. Fake) for each discrete audio input.



<br>
<br>

## 🎓 Academic Context
This project was carried out as part of the Bachelor's Degree in Computer Science at the **University of Cagliari (Università degli Studi di Cagliari)**.

* **Course:** Artificial Intelligence and Security (Intelligenza Artificiale e Sicurezza)
* **Academic Year:** 2024/2025

### 👥 Team Members
Developed in collaboration by:
* **Marco Caruso** - (https://github.com/.....)
* **Marco Loddo** - (https://github.com/.....)
* **Mauro Contu** - (https://github.com/.....)
