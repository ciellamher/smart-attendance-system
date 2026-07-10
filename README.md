**smart-attendance-system**
An advanced, real-time facial recognition attendance system built with Python and OpenCV, featuring Voice AI feedback and dynamic CSV database management.

### 01 — INSTALL

Bash
> git clone https://github.com/ciellamher/smart-attendance-system.git
> cd smart-attendance-system
> pip install opencv-python face_recognition numpy

---

### 02 — USE

> python main.py

The system will activate your webcam and log identified faces into the CSV database.

---

### 03 — WHAT'S INSIDE

- `main.py` — Core entry point capturing video and identifying students.
- `attendance.csv` — Dynamic database log output.
- `encodings/` — Stored 128-dimensional facial encodings for matching.

---

### 04 — LICENSE

MIT
