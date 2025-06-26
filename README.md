# Virtual-Personal-Fitness-Coach


The **AI Virtual Personal Fitness Coach** is a real-time, computer vision-based workout tracking system. Using **OpenCV** and **MediaPipe**, the app detects body posture, tracks joint angles (like the elbow in bicep curls), counts repetitions, and provides real-time visual feedback. This is useful for home workouts, fitness tracking, or as a foundation for building a smart personal trainer.

---

##  Project Overview

Traditional fitness tracking apps depend on manual input or wearables. This project brings **AI-powered body pose estimation** to the table by using only a **webcam**. It enables:

-  **Live pose detection**
-  **Tracking of body joint movement**
-  **Automated rep counting**
-  **Angle annotation and real-time feedback**


---

## Objectives

- Detect workout poses using a webcam and MediaPipe's Pose model
- Calculate joint angles using geometric computation
- Implement a logic system to identify and count exercise repetitions
- Visualize movement with overlaid feedback (angle, count, stage)
- Build a real-time application (CLI or GUI)
- Optional features: rep tracker, timer, and workout log saving

---

##  Dataset

No external dataset is used. Instead, the **real-time webcam feed** is processed using MediaPipe’s pretrained pose detection model.

---

## Tools & Technologies

| Tool        | Purpose                                |
|-------------|----------------------------------------|
| **Python**  | Main programming language              |
| **OpenCV**  | Webcam access, drawing, and UI         |
| **MediaPipe** | Real-time body landmark detection     |
| **NumPy**   | Math operations and angle calculations |
| **Streamlit** *(optional)* | Web UI for app deployment |

---

## ⚙️ Installation

Install dependencies via pip:

```bash
pip install opencv-python mediapipe numpy streamlit