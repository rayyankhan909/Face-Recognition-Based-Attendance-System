# Face-Recognition-Based-Attendance-System
A Python-based attendance system using face recognition and an interactive Tkinter GUI. It automatically identifies users, records attendance with date and time, stores data in CSV files, and provides secure registration with password protection.

📌 Project Overview

This project uses computer vision and face recognition techniques to identify individuals and mark their attendance automatically.
It eliminates the need for manual attendance and maintains daily attendance records in CSV format.

The application includes:

Face detection and recognition

Secure registration

Automated attendance logging

Interactive GUI for easy usage

🛠️ Technologies Used

Python

Tkinter – for the complete GUI

OpenCV – for image processing and face recognition
(cv2.face.LBPHFaceRecognizer_create())

NumPy – numerical operations

Pandas – data handling

CSV – storing student and attendance records

Datetime – date and time management

✨ Features

✔ Interactive and easy-to-use GUI
✔ Face recognition-based attendance system
✔ Password protection for new user registration
✔ Automatically creates/updates student details CSV file
✔ Generates a new attendance CSV file daily
✔ Marks attendance with accurate date & time
✔ Displays live attendance updates on the main screen
✔ Attendance shown in tabular format (ID, Name, Date, Time)

🚀 How to Run the Project

Clone the repository:

git clone https://github.com/your-username/face-recognition-attendance-system.git


Install required dependencies:

pip install opencv-python opencv-contrib-python numpy pandas


Run the main Python file:

python main.py

📂 Output Files

StudentDetails.csv – Stores registered student information

Attendance/YYYY-MM-DD.csv – Daily attendance records

🔐 Security

Password-protected registration system

Password can be changed from the GUI menu

📌 Future Enhancements (Optional)

Database integration (MySQL / Firebase)

Email notifications

Cloud-based attendance storage

Mobile app version.
