# 🚑 Health System - Login & Dashboard

A **frontend prototype** for a healthcare system with **User Registration/Login** and **Doctor Dashboard**.  
Built using **HTML, CSS, and basic JavaScript** to simulate real functionality.  

---

## ✨ Features
### 👤 User Side
- Register with **Phone (10 digits)** + **DOB**.
- Dashboard includes:
  - Slide-in **sidebar menu** (Normal Call ₹200 / Emergency Call ₹500).
  - 6 animated services:
    👁 Eye Checkup · ⚖ Fat Checkup · 👅 Tongue Checkup · 🫁 Lungs Checkup · 🧘 Yoga · 🧘‍♂️ Meditation  

### 👨‍⚕️ Doctor Side
- Login with:
  - Doctor ID → **10 digits**.
  - Password → **6 digits** (toggle Show/Hide).
- Dashboard includes:
  - 📞 Attend Call
  - 👥 View Patient Queue (with add/remove demo using JS)
  - 🚪 Logout
- Sidebar menu with doctor actions.

### 🏥 Patient Queue
- Interactive table where doctor can:
  - View existing patients.
  - Add a new patient (button).
  - Remove a patient row.

### 🛡 Extras
- Global **CSS file** for all pages.
- Responsive design with **media queries**.
- Clean Google Font (Poppins).
- Favicon support.

---

## 📂 Project Structure


├── index.html # Landing page
├── user_registration.html # User registration form
├── user_login.html # User dashboard (sidebar + services)
├── doctor_registration.html # Doctor login
├── doctor_login.html # Doctor dashboard
├── patient_queue.html # Patient queue (interactive)
├── style.css # Global stylesheet
├── favicon.ico # Browser tab icon
├── screenshots/ # Screenshots folder
│ ├── landing.png
│ ├── user_dashboard.png
│ ├── doctor_dashboard.png
│ ├── patient_queue.png
├── README.md # Documentation



---

## 📸 Screenshots

### User login
![User Login](screenshots/user_login.png)

### Doctor Login
![Doctor Login](screenshots/doctor_login.png)




---

## 🌍 Live Demo
👉 (https://github.com/Abhinav-23-Garg/Mediconnect-Help-System.git)

---

## 🚀 How to Run Locally
1. Clone/download this repo.  
2. Open `index.html` in your browser.  
3. Navigate between pages.  

---

## 🔧 Next Steps
- Add real **backend authentication**.  
- Store patients in a database.  
- Add live **video/audio calling (WebRTC)**.  
- Deploy live on GitHub Pages or Netlify.  

---

👨‍⚕️ Designed as a **learning project** for building clean UIs with HTML, CSS, and JS.



