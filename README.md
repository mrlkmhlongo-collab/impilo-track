# iMpilo Track 🩺

**AI-powered health and patient management system built for rural clinic workflows in South Africa.**

iMpilo Track is a multi-role mobile health application designed to bridge the gap between patients and clinics in under-resourced, rural healthcare settings. It combines offline-first data storage, biometric security, and AI-assisted health support to make quality care more accessible.

## 🎥 Demo

<!-- Drop your demo video file directly into this README while editing on GitHub, or paste a YouTube link below -->

[Watch the demo video](#)

## ✨ Key Features

- **AI Health Assistant** — Symptom triage and health guidance powered by the Claude AI API
- **Cross-Clinic Anomaly Detection** — Flags unusual patterns in patient data across facilities to support early intervention
- **Offline-First Architecture** — Local SQLite storage with automatic Firestore sync once connectivity is restored, built for areas with unreliable internet access
- **Biometric Login** — Secure, fast authentication for both patients and clinic staff
- **Dose Tracking** — Helps patients stay on top of medication schedules
- **Role-Based Dashboards** — Separate, tailored experiences for Patients and Admins/clinic staff
- **Vitals Monitoring** — Track and visualise patient health metrics over time

## 🛠️ Tech Stack

- **Frontend:** Flutter / Dart
- **Backend & Auth:** Firebase (Authentication, Firestore, Storage)
- **Local Storage:** SQLite (offline-first sync layer)
- **AI Integration:** Claude AI API
- **Design:** Custom purple/teal theme built for clarity and accessibility in clinical settings

## 👥 Team

Built as a BICT Honours capstone project (BICT421) by:
- Lifa Kagiso Mhlongo
- Malatsoa Kingsley Molepo
- Nkanyo Bingwa

## 📱 Screens & Roles

The app supports two primary user roles:
- **Patient** — View vitals, get AI-assisted symptom guidance, track medication doses, manage their own health records
- **Admin / Clinic Staff** — Monitor patients across the clinic, review flagged anomalies, manage records and dashboards

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/mrlkmhlongo-collab/impilo-track.git
cd impilo-track

# Install dependencies
flutter pub get

# Run the app
flutter run
```

You'll need a Firebase project configured (see `firebase_options.dart` setup) and a Claude API key for the AI assistant features to work.

## 📄 About This Project

iMpilo Track was built to address real gaps in rural healthcare delivery — where intermittent connectivity, limited clinic staffing, and fragmented patient records make consistent care difficult. The offline-first design ensures the app remains usable even when internet access is unreliable, syncing automatically once a connection is available.

---

*This project was developed as part of the BICT Honours programme at the University of Mpumalanga.*
