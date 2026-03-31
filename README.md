# 🎮 MediaPipe Hand Tracking → Unity (UDP)

This project connects **Python hand tracking (MediaPipe)** with **Unity** using UDP communication.

---

## Overview

* Python detects hand movement using MediaPipe
* Data is sent via UDP
* Unity receives the data and controls objects in real-time

---

## 📁 Project Structure

```
.
├── main.py
├── hand_detector.py
├── requirements.txt
├── Assets
│   ├── HandTracking.cs
│   ├── LineCode.cs
│   ├── UDPReceive.cs
```

---

## 🧠 File Explanation

### Python

* `main.py`
  Runs hand tracking and sends data to Unity

* `hand_detector.py`
  Handles hand detection logic using MediaPipe

---

###  Unity

* `HandTracking.cs`
  Controls object movement based on hand input

* `LineCode.cs`
  Draws lines following hand movement

* `UDPReceive.cs`
  Receives data from Python via UDP

---

## ▶️ How to Run

### 1. Install dependencies

```
pip install -r requirements.txt
```

### 2. Run Python

```
python main.py
```

### 3. Run Unity

* Open the Unity project
* Press ▶️ Play

