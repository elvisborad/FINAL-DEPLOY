# FINAL-DEPLOY
🏥 CareSync – Medication Management Web App

CareSync is a web-based healthcare management system designed to help patients and caregivers manage medication schedules efficiently. It provides a simple and responsive interface for tracking medicines, ensuring timely intake, and improving coordination between users.

🚀 Features
👤 User Roles
Patient
View medication schedule
Track daily intake
Caregiver
Add, update, and manage medicines
Monitor patient’s medication routine

🔐 Authentication System
Signup for patient and caregiver
Login system with role detection
OTP verification (demo-based)

💊 Medication Management
Add medicine with:
Name
Dosage
Stock
Multiple time slots
Store and retrieve data from cloud
Dynamic UI updates

☁️ Database Integration
Uses Firebase Firestore
Stores:
User credentials
Medication data
Logs
Real-time data persistence
Accessible across devices

🎨 UI/UX
Built with HTML, Tailwind CSS, JavaScript
Responsive and clean design
Modal-based interactions
Dashboard navigation for both roles

🧠 Core Functions
🔹 Authentication
handleSignup() → Registers patient & caregiver
handleLogin() → Validates user and loads data
generateOTP() → Generates OTP (demo)
verifyOTP() → Verifies OTP and redirects
logout() → Ends session without deleting data
🔹 Database (Firebase)
saveState() → Saves user data to Firestore
loadState(userId) → Loads user data from Firestore
🔹 Medication Management
saveMed() → Adds new medicine
renderTimeInputs() → Handles multiple time inputs
initCaregiverDash() → Loads caregiver dashboard
🔹 Navigation & UI
nav(pageId) → Handles page navigation
openAddModal() → Opens medicine modal
closeAddModal() → Closes modal
toggleNotif() → Toggles notifications
🔹 Utility
calcAge() → Calculates age from DOB input

⚙️ Tech Stack
Frontend: HTML, Tailwind CSS, JavaScript
Backend: Firebase Firestore
Hosting: Localhost / Vercel (optional)

⚠️ Limitations
OTP system is simulated (not real SMS)
Passwords are stored in plain text (not secure)
Caregiver is stored inside patient document (not ideal structure)

🔮 Future Improvements
Firebase Authentication (secure login)
Real OTP via SMS
Separate database structure for caregiver
Notification system (reminders)
Analytics dashboard

🧩 How It Works
User signs up (patient + caregiver)
Data is stored in Firebase
User logs in → data fetched from database
Caregiver manages medicines
Patient views and follows schedule


📌 Conclusion
CareSync demonstrates a complete integration of frontend development with a cloud-based backend. It provides a functional prototype for medication tracking and showcases real-world concepts like authentication, database management, and UI interaction.
