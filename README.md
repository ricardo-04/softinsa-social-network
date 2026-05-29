# SoftShares — Corporate Social Network

> A full-stack corporate social platform built for Softinsa employees, combining a Flutter mobile app with a React-powered admin web dashboard.

---

## 📌 Overview

SoftShares is a corporate social network developed as part of the Integrated Project course at ESTGV – Instituto Politécnico de Viseu, in partnership with **Softinsa**. The platform fosters internal communication, collaboration, and community among company employees through a mobile application and a dedicated admin web interface.

---

## ✨ Features

### 📱 Mobile App (Flutter)
- **Authentication** — Email/password login, Google & Facebook OAuth, saved profiles, and password recovery
- **Events** — Browse, create, and join events filtered by category; event photo albums; participant management; comment system with admin moderation
- **Forums** — Create and reply to discussion threads, organized by area
- **Places** — Discover and rate company-recommended locations, filterable by area and star rating
- **Notifications** — Real-time in-app notifications for event shares, comments, participations, and forum activity
- **Profile** — View and edit personal info, manage area preferences, see enrolled and created events
- **Event Calendar** — Visual calendar showing upcoming events
- **Multilingual** — Full support for Portuguese, English, and Spanish

### 🌐 Admin Web Platform (React)
- **Dashboard** — Statistics and charts on user distribution, comment volume, and center activity
- **User Management** — Validate or reject pending user accounts
- **Content Moderation** — Review and approve/reject comments across events, forums, and places
- **Events Management** — Create, validate, edit, and invalidate events; manage photo albums
- **Places Management** — Validate, filter, and edit submitted locations
- **Areas & Sub-Areas** — Create and manage content categories (admin-only for areas)
- **Centers** — Add and manage Softinsa office centers
- **Form Controls** — Enable or disable account creation, event, and place submission forms
- **Announcements** — Publish company-wide information and notices visible to all employees

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Mobile | Flutter (Dart) |
| Web Frontend | React, HTML, CSS, JavaScript |
| Authentication | Google OAuth, Facebook OAuth |
| Maps | Google Maps API |

---

## 🚀 Getting Started

### Prerequisites
- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- [Node.js](https://nodejs.org/) & npm

### Mobile App

```bash
cd mobile
flutter pub get
flutter run
```

### Web Admin Dashboard

```bash
cd web
npm install
npm start
```

⚠️ You will need to configure your own backend API and authentication credentials in the respective environment files.

---

## 📄 License

This project was developed for academic purposes. All rights reserved by the authors.