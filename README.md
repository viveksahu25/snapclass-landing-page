# 🎓 SnapClass — Smart AI Attendance Showcase Website

![SnapClass Preview](./static/img/snapclassfrontview.png)

This repository contains the official **Product Overview & Showcase Website** for **SnapClass** — a next-generation smart attendance system powered by **AI Face Analysis** and **Voice Recognition**. Built with **Python (Flask)**, HTML5, and CSS3, this landing page walks users through the complete architecture, 4-phase workflow, and interactive UI of the SnapClass platform.

---

## ✨ Key Highlights Showcased

* ⚡ **Phase 01 — Instant Enrollment:** Students join courses in seconds using unique QR codes, direct links, or subject dropdowns without tedious sign-up forms.
* 🔐 **Phase 02 — Biometric Registration & Login:** Passwordless check-in using **FaceID** camera alignment and voice authentication.
* 🤖 **Phase 03 — Dual AI Attendance Modes:** 
  * **Face AI Analysis:** Upload classroom photos or capture live images to mark present students automatically.
  * **Voice AI Attendance:** Fast and accurate voice-verified attendance logging.
* 📊 **Phase 04 — Personal Dashboard & Analytics:** Dedicated views for teachers and students to manage subjects (e.g., *English Communication - BT-201*, *Introduction of Physics - BT-201*) and track real-time attendance records.

---

## 📸 Platform UI Previews

| Main Dashboard | FaceID Secure Login |
| :---: | :---: |
| ![Dashboard](./static/img/dashboard.png) | ![Secure Login](./static/img/secure_login.png) |

| Face AI Attendance | Voice AI Attendance |
| :---: | :---: |
| ![Face AI](./static/img/FaceAI_Attendance.png) | ![Voice AI](./static/img/VoiceAI_Attendance.png) |

| Course Management | Attendance Records |
| :---: | :---: |
| ![Course Management](./static/img/Course_Management.png) | ![Attendance Records](./static/img/Attendance_record.png) |

---

## 📂 Project Structure

```text
snapclass-landing-page/
├── app.py                  # Flask application entry point
├── requirements.txt        # Python dependencies
├── templates/
│   └── index.html          # Main showcase landing page template
└── static/
    ├── css/
    │   └── styles.css      # Custom styling and responsive layout
    └── img/                # UI screenshots, logos, and visual assets
