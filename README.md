# ⚡ VigilCloud — Highway Intelligence System

AI-powered real-time hazard detection for Indian highways using camera vision + IoT sensors.

## 🔴 Live Demo
- **Dashboard:** [add Vercel link here]
- **Demo Video:** [add YouTube link here]

## 🧠 What it does
- Detects potholes, fog, fire, stalled vehicles on NH-44 in real time
- YOLOv8 computer vision model trained on 665 labelled road images
- 10 sensor nodes send data every 500ms to cloud backend
- Cross-node verification confirms alerts before dispatching
- Drivers get alerted within 5 seconds of detection

## 🏆 Far Away 2026 — Themes
- **Agentic & Autonomous Systems** (primary) — nodes perceive, decide, act independently
- **Logistics & Transit** (secondary) — highway safety = freight movement safety

## ⚙️ Tech Stack
| Layer | Technology |
|---|---|
| ML Model | YOLOv8 nano fine-tuned on pothole dataset |
| Backend | Python FastAPI + WebSockets + SQLite |
| Frontend | React + Vite + Leaflet.js |
| Simulator | Python — simulates 10 NH-44 sensor nodes |

## 🚀 Run Locally

**Backend:**
```bash
cd backend
venv\Scripts\activate
uvicorn main:app --reload
```

**Frontend:**
```bash
cd frontend/dashboard
npm run dev
```

**Simulator:**
```bash
cd backend
python simulator.py
```

## 👥 Team
- [Your Name] — [Your College]