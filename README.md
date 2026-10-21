# 🌊 Subsurface Sonar Acoustic Intelligence

A next-generation enterprise-grade machine learning web application engineered to differentiate geological rock formations from submerged metallic ordinance (mines) using acoustic signature frequency analysis.

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://rockvsmine-project-ersofcszt4prsymqxpditr.streamlit.app/)

---

## ✨ Live Demo
Experience the application live here: [Sonar Acoustic Intelligence Web App](https://rockvsmine-project-ersofcszt4prsymqxpditr.streamlit.app/)

---

## 🚀 Key Features
* **Real-Time Inference Portal:** Input 60-channel normalized frequency arrays to receive instant predictive assessments.
* **Custom Weather Overlays:** 
  * 🌧️❄️ **Sample A:** Triggers simultaneous rain and snowfall canvas particle effects.
  * 🍂🍁 **Sample B:** Triggers vibrant, multi-colored falling autumn leaves simulation.
* **Celebratory UI Feedback:** Integrated particle animations and celebratory popup effects upon executing model inference.
* **Robust Error Handling:** Built-in telemetry validation for dimension matching and data parsing safeguards.

---

## 🛠️ System Architecture & Tech Stack
* **Core Machine Learning Engine:** Random Forest Ensemble (`sonar_model.pkl`) trained on the classic Sonar dataset.
* **Model Performance:** ~82.51% Cross-Validated Accuracy with sub-10ms inference latency.
* **Frontend & Dashboard:** Streamlit with custom HTML5/CSS glassmorphism, responsive session state management, and dynamic canvas overlays.
* **Data Pipeline:** NumPy & Pandas for high-dimensional feature scaling.

---

## 📂 Project Structure
```text
Rock_vs_mine_project/
│
├── app.py                  # Main Streamlit web application interface
├── sonar_model.pkl         # Trained Random Forest classification artifact
├── requirements.txt        # Python package dependencies
└── README.md               # Project documentation
