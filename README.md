# FaceApp 👤📸

FaceApp is a **Face Recognition Attendance System** built with **Python (Tkinter GUI + OpenCV)**.  
It allows users to register employees, capture their face data, train the model, and mark attendance automatically using facial recognition.  

---

## 🚀 Features
- 📝 Employee Registration (with EMP ID & Name)
- 📷 Capture face images for training
- 🤖 Train the recognition model
- 🧑‍💼 Real-time face recognition
- 📊 Automatic attendance logging
- 🖥️ Simple Tkinter GUI

---

## 📂 Project Structure
```
FaceApp/
│-- faceapp.py        # Main application file (Tkinter GUI)
│-- TrainingImage/    # Captured face images
│-- TrainingImageLabel/ # Trained model files
│-- EmployeeDetails/  # Employee details CSV
│-- Attendance/       # Attendance records (CSV)
│-- README.md         # Project documentation
```

---

## 🛠️ Requirements
- Python 3.x  
- Tkinter  
- OpenCV  
- NumPy  
- Pillow  
- Pandas  

Install dependencies:
```bash
pip install opencv-python numpy pillow pandas
```

---

## ▶️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/faceapp.git
   cd faceapp
   ```
2. Run the application:
   ```bash
   python faceapp.py
   ```
3. Use the GUI to:
   - Register an employee  
   - Capture face images  
   - Train the model  
   - Start attendance recognition  

---

## 📊 Attendance Output
Attendance is saved in **CSV files** under `Attendance/`, containing:
- Employee ID  
- Name  
- Date  
- Time  

---

## 🎨 GUI Preview
The app provides a **Tkinter-based interface** with labeled input fields and buttons for easy use.

---
