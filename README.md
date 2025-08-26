# FaceApp 👤📸

**FaceApp** is a **Face Recognition Attendance System** built with **Python (Tkinter GUI + OpenCV)**.  
It allows you to **register employees, capture face data, train a recognition model, and automatically mark attendance** using facial recognition technology.

---

## 🚀 Features
- 📝 **Employee Registration** (with EMP ID & Name)  
- 📷 **Capture Face Images** for training  
- 🤖 **Train the Recognition Model**  
- 🧑‍💼 **Real-time Face Recognition** for attendance  
- 📊 **Automatic Attendance Logging**  
- 🖥️ **Simple Tkinter GUI** for ease of use  

---

## 📂 Project Structure
```
FaceApp/
│-- faceapp.py            # Main Tkinter GUI application
│-- TrainingImage/        # Captured face images
│-- TrainingImageLabel/   # Trained model files (YML)
│-- EmployeeDetails/      # Employee details CSV
│-- Attendance/           # Attendance records (CSV)
│-- README.md             # Project documentation
```

---

## 🛠️ Requirements
- Python 3.x  
- Tkinter  
- OpenCV (opencv-contrib-python for LBPHFaceRecognizer)  
- NumPy  
- Pillow  
- Pandas  
- cx_Freeze  

Install dependencies using pip:
```bash
pip install opencv-contrib-python numpy pillow pandas cx_Freeze
```

Or using Conda:
```bash
conda install -c conda-forge opencv numpy pillow pandas tk
pip install cx_Freeze
```

---

## ▶️ How to Run

1. **Clone the repository:**
```bash
git clone https://github.com/your-username/faceapp.git
cd faceapp
```

2. **Create a Conda environment (optional but recommended):**
```bash
conda create -n faceapp python=3.9 -y
conda activate faceapp
```

3. **Install dependencies:**
```bash
conda install -c conda-forge opencv numpy pillow pandas tk
pip install opencv-contrib-python cx_Freeze
```

4. **Run the application:**
```bash
python faceapp.py
```

5. **Use the GUI to:**
- Register employees  
- Capture face images  
- Train the recognition model  
- Start attendance recognition  

⚠️ **Note:** The `cv2.face` module (LBPHFaceRecognizer) is part of **opencv-contrib-python**, not the standard OpenCV package.

---

## 📊 Attendance Output
Attendance is saved as **CSV files** in the `Attendance/` folder. Each file contains:
- Employee ID  
- Name  
- Date  
- Time  

---

## 🎨 GUI Preview
The application provides a **clean Tkinter interface** with:
- Input fields for Employee ID and Name  
- Buttons for capturing faces, training the model, and starting attendance  
- Real-time face recognition display  

---

## 💡 Tips
- Ensure good lighting and a clear background while capturing face images for higher recognition accuracy.  
- Use at least **20–30 face images per employee** for effective training.  

---

## 📜 License
This project is **open-source**. Feel free to use, modify, and contribute!
