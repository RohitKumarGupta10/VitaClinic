# Virtual Clinic - Telemedicine Web App

## 📌 Project Overview
The **Virtual Clinic** is a web-based telemedicine platform designed to provide remote consultations, video calls with doctors, and a chatbot-powered assistant for patient queries.

## 🚀 Features Implemented
### ✅ **1. User Authentication System**
- Users (Students, Teachers, Admins) log in based on roles.
- Parents have a separate login system.
- User data stored in the `login_details` table of the `erp` database.

### ✅ **2. Notice Board System**
- Admins & Teachers can send notices.
- Notices are displayed with filtering options.

### ✅ **3. Homework Assignment System**
- Teachers can assign homework to students.

### ✅ **4. Attendance Management System**
- Teachers can mark attendance.
- Attendance details stored in the `attendance_details` table.

### ✅ **5. Student Marks Entry System**
- Marks entry for subjects (Physics, Chemistry, etc.).
- Support for FA1, SA1, FA2, SA2 exams.
- Data stored in the `erp` database.

### ✅ **6. AI Chatbot (Dialogflow Integration)**
- Chatbot assists users with general queries.
- Integrated using Google Dialogflow.

### ✅ **7. Jitsi Meet Video Consultation**
- Embedded Jitsi Meet for doctor-patient video calls.
- `Start Call` and `End Call` buttons added in `services.html`.
- Dynamic room creation for each consultation.

## 📂 Folder Structure
```
/virtual-clinic
│── index.html         # Home Page
│── services.html      # Video Consultation Page
│── services.css       # Styles for Consultation Page
│── chatbot.js         # Dialogflow Chatbot Logic
│── db_config.php      # Database Connection
│── README.md          # Project Documentation
└── /assets            # Images, Icons, and Static Files
```

## 🛠️ Setup Instructions
### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/your-username/virtual-clinic.git
cd virtual-clinic
```

### 2️⃣ **Start Local Server**
For PHP and MySQL setup using XAMPP:
- Start Apache & MySQL in XAMPP.
- Place project in `htdocs` directory.
- Access via `http://localhost/virtual-clinic`

For a simple HTML/JS setup:
```bash
npx serve .
```

### 3️⃣ **Database Setup**
- Import `erp.sql` into MySQL.
- Ensure `db_config.php` has correct credentials.

### 4️⃣ **Running the Project**
- Open `http://127.0.0.1:5500/index.html` in a browser.

## 🔗 Contributing & Committing Changes
### ✅ **1. Check Git Status**
```bash
git status
```

### ✅ **2. Add Changes**
```bash
git add .
```

### ✅ **3. Commit the Changes**
```bash
git commit -m "Added Jitsi Meet video consultation feature"
```

### ✅ **4. Push to GitHub**
```bash
git push origin main
```

## 💡 Future Improvements
- Secure authentication for video calls.
- Patient medical record management.
- Appointment scheduling system.

---

This README provides a detailed guide for setting up, contributing, and managing your Virtual Clinic project. Let me know if you need modifications! 🚀

