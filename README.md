# 📸 Attendance Monitoring System using Machine Learning

An intelligent attendance monitoring system that leverages **facial recognition** and **machine learning** to automate and secure attendance tracking. Built with a focus on real-time detection, data privacy, and insightful visualizations.

---

## 🚀 Features

* 🔍 **Face Recognition** using machine learning
* 🔐 **Encryption** for secure attendance data storage
* 🧠 **Custom Dataset Handling** (Add/Delete student images)
* 🗂️ **Attendance Logging** with timestamps
* 📊 **Streamlit Dashboard** for attendance visualization
* 🌐 **Frontend Integration** to launch dashboard from a button click

---

## 🛠️ Technologies Used

* **Python**
* **OpenCV** – for image processing and face detection
* **face\_recognition** – for facial embeddings and recognition
* **Pandas** – for data handling and CSV logging
* **Streamlit** – for interactive dashboard visualization
* **Cryptography / Fernet** – for encryption
* **Flask / Web Interface** – for frontend/backend integration (optional)

---

## 📂 Project Structure

```text
face-attendance-system/
├── static/                  # CSS, JavaScript, and images
├── templates/               # HTML templates (Flask views)
├── photos/                  # Captured face images for training
├── outputScreenshot/        # Output screenshots of features
├── Attendance_2025-04.csv   # Attendance log (CSV format)
├── Attendance_2025-04.pdf   # Attendance log (PDF format)
├── app.py                   # Flask main app
├── takephoto.py             # Capture and store new user photo
├── train_model.py           # Face encoding and model training
├── encryption.py            # AES-based encryption for logs
├── update1.py               # Attendance visualization module
├── requirements.txt         # Required Python packages
└── README.md

---

## 💡 How It Works

1. **Image Dataset Collection**
   Capture student images and store them with labeled folders.

2. **Face Encoding**
   Extract facial features and store them securely using a trained model.

3. **Live Recognition**
   Detect and recognize faces via webcam input and log attendance in a CSV.

4. **Encryption**
   Attendance logs are encrypted to ensure confidentiality.

5. **Visualization**
   View attendance reports and graphs using the Streamlit dashboard.

---

## 📈 Streamlit Dashboard

To launch the dashboard:

bash:
streamlit run dashboard.py

Or, if integrated with your frontend:

* Clicking the **"Visualize Attendance"** button will automatically open the Streamlit dashboard in a browser.

---

## ✅ Requirements

bash:
pip install -r requirements.txt


## 📸 Sample Use Case

* Educational institutions automating student attendance.
* Corporate settings tracking meeting participation.
* Any environment where manual attendance is inefficient or error-prone.

---

## 🔐 Security & Privacy

* All attendance data is encrypted using the **Fernet** symmetric encryption.
* Facial data is stored locally (not on cloud) ensuring user privacy.

---

## 📌 Future Improvements

* Role-based login system (Admin/Faculty)
* Cloud deployment (e.g., Render, Heroku)
* SMS or Email notifications
* Mobile app integration


