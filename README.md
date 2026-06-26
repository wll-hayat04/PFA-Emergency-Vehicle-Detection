# 🚨 Emergency Vehicle Detection & Traffic Simulation — PFA

**Authors:** Hayat WALDI & Sofia KHARBOUCHE  
**Project:** Projet de Fin d'Année (PFA)

---

## 📌 Overview

This project combines **YOLO-based emergency vehicle detection** with **SUMO traffic simulation** to study and optimize traffic management strategies for emergency vehicles at intersections.

---

## 📁 Repository Structure

| File | Description |
|------|-------------|
| `Yolo_training.ipynb` | YOLO model training notebook |
| `sumo_project_final.zip` | SUMO traffic simulation (Python scripts, XML configs, results) |
| `output_YOLO_model.zip` | Trained YOLO model weights and outputs |
| `PFA_report.pdf` | Full project report |
| `Presentation_PFA.pdf` | Project presentation slides |

---

## 🧠 Key Components

### 🔍 YOLO Detection
- Custom-trained YOLOv model for detecting emergency vehicles
- Training notebook with evaluation metrics (precision, recall, mAP)

### 🚦 SUMO Traffic Simulation
- Intersection network simulation with multiple traffic density scenarios (low, medium, dense)
- Kalman filter & EMA smoothing for detection confidence
- KPI comparison across different strategies

---

## 🛠️ Technologies
- Python, PyTorch, Ultralytics YOLO
- SUMO (Simulation of Urban Mobility)
- Kalman Filter, Exponential Moving Average
- LaTeX (report)
