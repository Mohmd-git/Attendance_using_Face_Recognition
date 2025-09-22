# 📌 Attendance Using Face Recognition System  

This is a **Python-based application** that uses **face recognition technology** to mark attendance for students. It incorporates a **GUI**, **MySQL database integration**, and various features to manage student data, mark attendance, generate reports, and analyze attendance records.  

---

## 🚀 Getting Started  

Follow these steps to set up and run the project:  

### Clone the Repository  
```bash
git clone https://github.com/Mohmd-git/Attendance_using_Face_Recognition.git
```
### Install Dependencies
Make sure you have Python installed. Then, install the required packages:
```bash
pip install -r requirements.txt
```
### Set up MySQL Database

Install MySQL if not already installed.

Create a new database named sem6_project.

Import the provided SQL file to create the necessary tables.

### Configure Database Connection
Update your MySQL credentials in main.py:
```bash
db = MySQLdb.connect(
    host="localhost",
    user="your_username",
    password="your_password",
    database="sem6_project"
)
```

### Run the Application:
```bash
python face.py
```

### Key Features

👥 Add new students and capture their photos

📷 Mark attendance using face recognition

📊 Analyze attendance data with visualizations

📃 Generate attendance reports (PDF format)

🔐 User authentication & authorization

### Contributions are welcome! 🎉
Open an issue for bugs or suggestions

Submit a pull request for improvements


 ---
