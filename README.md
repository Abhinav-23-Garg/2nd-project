# 🚑 Health System - Login & Dashboard

A simple **HTML, CSS, and minimal JS prototype** for a health system with **User Registration/Login** and **Doctor Login/Dashboard**.  
Built as a front-end demo project with clean design, sidebar navigation, and animations.

---

## 📂 Project Structure


├── index.html # Landing page (choose User or Doctor)
├── user_registration.html # User registration (Phone + DOB)
├── user_login.html # User dashboard (sidebar + services)
├── doctor_registration.html # Doctor login (ID + Password)
├── doctor_login.html # Doctor dashboard (Attend Call, Queue, Sidebar)
├── patient_queue.html # Patient queue (mock table)
├── style.css # Global stylesheet
├── README.md # Documentation



---

## ✨ Features
### 👤 User Side
- Register with **Phone Number (10 digits)** + **DOB**.
- Dashboard with:
  - Slide-in **sidebar menu** (Normal Call ₹200 / Emergency Call ₹500).
  - 6 animated services (slide-in effect):  
    👁 Eye Checkup · ⚖ Fat Checkup · 👅 Tongue Checkup · 🫁 Lungs Checkup · 🧘 Yoga · 🧘‍♂️ Meditation  

### 👨‍⚕️ Doctor Side
- Login with:
  - **Doctor ID** → exactly **10 digits**.
  - **Password** → exactly **6 digits**.
- Dashboard includes:
  - 📞 Attend Call
  - 👥 View Patient Queue
  - 🚪 Logout
- Slide-in **sidebar menu** with doctor actions.

### 🎨 Styling
- One **global CSS file**.
- Responsive (mobile + desktop).
- Gradient buttons, hover animations, and staggered slide-in effects.

---

## 🚀 How to Run
1. Clone/download this repo.
2. Open `index.html` in any browser.
3. Navigate between pages.

---

## 📸 Screenshots
(Add screenshots of each page here)

---

## 🛠️ Tech Stack
- **HTML5**
- **CSS3** (Flexbox + Grid + Animations)
- **Vanilla JS (sidebar toggle + animation trigger)**

---

## 🔧 Improvements & Next Steps
- Add real **backend authentication**.
- Connect **Attend Call** to WebRTC for live video/audio.
- Add **Patient Profile Pages**.
- Deploy live via **GitHub Pages / Netlify / Vercel**.

---

👨‍⚕️ Designed as a **prototype / learning project**.
