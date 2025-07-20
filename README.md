# 📸 Face Recognition Based Attendance System

This is an **AI-powered automated attendance system** that uses **face recognition** to detect and mark the presence of individuals. The project aims to eliminate manual attendance marking, reduce errors, and enhance security, especially in educational institutions and workplaces.

---

## 🎯 Features

- 🤖 Face detection and recognition using OpenCV and dlib
- 📷 Real-time webcam-based attendance capture
- 🧠 AI model trained on student/employee face datasets
- 🗃️ CSV-based attendance logging with date and time
- 🛡️ Prevents proxy or fake attendance entries
- 🔒 Role-based access for administrator or staff (optional extension)

---

## 🧑‍💻 Technologies Used

- Python 3.x
- OpenCV
- face_recognition (dlib-based)
- NumPy, Pandas
- Tkinter (if GUI used)
- CSV or SQLite for attendance logs

---

## 🧪 How It Works

1. System captures and stores facial encodings from training images.
2. During runtime, the webcam scans and matches faces with trained data.
3. Once matched, it marks attendance with timestamp in a `.csv` file.
4. Duplicate entries for the same session are avoided.

---

## 🚀 Getting Started
### 1. Clone the Repo
git clone https://github.com/srishtikarn11/Face-Recognition-Based-Attendance.git
cd Face-Recognition-Based-Attendance
---
2. Install Dependencies
pip install opencv-python face_recognition numpy pandas
---
3. Run the Program
python attendance.py

---

🗃️ Project Structure
bash
Copy
Edit
Face-Recognition-Based-Attendance/
├── images/               # Folder of known faces (students/employees)
├── attendance.py         # Main script
├── attendance.csv        # Auto-generated attendance logs
├── train_model.py        # (optional) Face encoding generator
├── README.md

