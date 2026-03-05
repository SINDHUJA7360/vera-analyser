# vera-analyser
# Project VERA 🕵️‍♂️
### **Visionary Emotional and Response Analyzer**

**Project VERA** is an intelligent, multimodal truth-verification system designed to identify potential stress or deception responses by analyzing physiological signals. By integrating biometric sensors with real-time data analysis, VERA offers a modern, compact, and data-driven alternative to traditional polygraph systems.

---

## 🎯 Project Goals
* **Portable Monitoring:** A compact system for mobile physiological tracking.
* **Signal Synchronization:** Seamless alignment of multi-sensor inputs.
* **Stress Detection:** Accurate identification of physiological spikes during stimulus.
* **AI Readiness:** A foundation for future machine-learning-based truth analysis.

---

## 🏗 System Architecture
The platform is organized into five modular layers:

1. **Sensor Layer:** * **GSR Sensor:** Measures skin conductivity (electrodermal activity).
   * **Pulse Sensor:** Tracks heart rate and pulse variability.
2. **Microcontroller Layer:** Uses **Arduino/ESP32** for analog-to-digital conversion and serial data transfer.
3. **Data Processing Layer:** Signal normalization, noise filtering, and feature extraction via Python.
4. **Analysis Layer:** Pattern recognition for stress and deception response detection.
5. **Visualization Layer:** Real-time monitoring via graphical interfaces and data dashboards.

---

## 💻 Tech Stack

### **Hardware**
* **Microcontroller:** Arduino or ESP32
* **Sensors:** GSR (Galvanic Skin Response) & Pulse/Heart Rate Sensors
* **Interface:** USB / Serial Communication

### **Software**
* **Language:** Python
* **Libraries:** NumPy, Pandas, Matplotlib, PySerial
* **Optional:** Scikit-Learn (for future ML models)

---

## 🔄 System Workflow

1. **Acquisition:** Sensors capture real-time physiological data.
2. **Transmission:** Data is streamed to a PC via a Microcontroller.
3. **Refinement:** Raw signals are cleaned and filtered using Python.
4. **Analysis:** The system identifies patterns correlated with stress.
5. **Output:** Data is displayed on a live monitoring dashboard.

---

## 🚀 Key Features
* **Real-Time Tracking:** Instant monitoring of biometric variations.
* **Modular Design:** Highly scalable for additional sensors or software logic.
* **Data-Driven:** Focuses on interpretable graphical outputs for response analysis.
* **Future-Proof:** Built to support future integration of AI and wireless connectivity.

---

## 🔮 Future Roadmap
 Integration of facial expression recognition.
 Voice stress analysis (VSA) implementation.
 Transition to wireless (Bluetooth/Wi-Fi) sensor connectivity.

---

## 🧪 Project Status
**Current Phase:** Prototype / Research



