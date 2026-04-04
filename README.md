# 📚 PolyPath

A beautiful, offline-first **study progress tracker** built for Polytechnic students in India. Track your topics, subjects, and semester-wise progress — all in one place.

---

## 📥 Download

[⬇️ Download APK](../../raw/main/PolyPath.apk)

> Requires Android 6.0 (Marshmallow) or above. Allow installation from unknown sources to install.

---

## ✨ Features

### 🎓 Multi-Stream Support
Choose your engineering stream at first launch:
- ⚡ Electrical Engineering (EE)
- 💻 Computer Science & Technology (CST)
- 🏗️ Civil Engineering (CE)
- 📡 Electronics & Telecommunication (ETCE)
- ⚙️ Mechanical Engineering (ME)

### 📖 Topic-Level Tracking
- Mark individual topics as done within each subject
- Toggle entire subjects complete/incomplete at once
- Visual progress bars per subject

### 📊 Smart Progress Dashboard
- Animated progress ring showing semester-wise completion
- Live stats: topics done, subjects completed, remaining count
- Per-subject breakdown with progress bars

### 🏠 Home Screen
- Set your current active semester (Sem 1–6)
- Smart "Study Today" suggestions — shows your lowest-progress subjects first
- Daily study streak tracker 🔥

### 📈 Progress Screen
- Large animated ring showing overall or semester-wise progress
- Share your progress via any app or copy to clipboard
- Reset progress option with confirmation

### ⚙️ Settings
- Switch engineering stream anytime
- Change current semester
- Full reset option

### 📱 Native Android Feel
- Hardware back button support (navigates back or exits app)
- Daily reminder notification at 8:00 PM 🔔
- Splash screen on launch
- Smooth fade-in animations throughout

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React 18 | UI framework |
| Capacitor 5 | Native Android bridge |
| Vite 5 | Build tool |
| LocalStorage | Offline data persistence |
| Capacitor Local Notifications | Daily study reminders |
| Capacitor App Plugin | Hardware back button & exit |

---

## 📂 Project Structure
```
polypath-fixed/
├── src/
│   ├── screens/
│   │   ├── SplashScreen.jsx     # Launch screen
│   │   ├── StreamPicker.jsx     # Choose your stream
│   │   ├── HomeScreen.jsx       # Dashboard & suggestions
│   │   ├── SubjectsScreen.jsx   # Topic tracking
│   │   ├── ProgressScreen.jsx   # Stats & progress rings
│   │   └── SettingsScreen.jsx   # App settings
│   ├── components/
│   │   ├── ProgressRing.jsx     # Animated SVG ring
│   │   ├── SubjectCard.jsx      # Subject UI card
│   │   └── Toast.jsx            # Notification toast
│   ├── hooks/
│   │   └── useProgress.js       # Progress state & localStorage
│   ├── data.js                  # All streams, semesters & subjects
│   ├── App.jsx                  # Root component & navigation
│   └── global.css               # Theme & CSS variables
├── capacitor.config.json
├── package.json
└── index.html
```

---

## 🎓 Streams & Curriculum

Each stream contains **6 semesters** with full subject and topic data based on the West Bengal State Council of Technical Education (WBSCTE) syllabus:

| Stream | Semesters | Total Subjects |
|---|---|---|
| Electrical Engineering | 6 | 47 |
| Computer Science & Technology | 6 | 43 |
| Civil Engineering | 6 | 48 |
| Electronics & Telecom | 6 | 57 |
| Mechanical Engineering | 6 | 48 |

---

## 👨‍💻 Developer

Made with ❤️ by [arpan-creates](https://github.com/arpan-creates)

