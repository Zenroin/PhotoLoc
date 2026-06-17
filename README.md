# 📸 PhotoLoc — Community Photo Spot Discovery

## 🚀 Overview

**PhotoLoc** is a mobile-first discovery platform built for photographers and explorers in Turkey. It helps users find, share, and rate the best photo spots — from city rooftops to coastal viewpoints — through a community-driven map and moderation workflow.

The app combines real-time maps, golden-hour insights, social profiles, and admin-approved content to keep the platform trustworthy and high quality.

> Built with **Expo (SDK 54)**, **React Native**, and **Firebase**.

---

## ✨ Core Modules & Capabilities

### 🏠 Discover Feed

The home screen for exploring photo spots with smart filtering and search.

- **Category filters:** Nature, city, architecture, night, sea, and more
- **Sort modes:** Newest, highest rated, nearest to you
- **Live search:** Instant suggestions as you type
- **Pull-to-refresh** and skeleton loaders for smooth UX

https://github.com/user-attachments/assets/376453e7-b309-4d04-97fb-22d00e5d0404

---

### 🗺️ Interactive Map

A map-first experience with photo-rich markers and quick spot previews.

- **Photo markers:** Each spot appears as a thumbnail pin on the map
- **Clustering:** Clean view even with hundreds of locations
- **Spot preview card:** Tap a marker → slide-up card with photo carousel
- **Location search:** Google Places + OpenStreetMap powered address search
- **Quick actions:** Recenter to GPS, fit all markers, rating filters

https://github.com/user-attachments/assets/54b425ad-2509-4f65-92de-b857e3a1a345

---

### 📍 Spot Detail & Golden Hour

Deep dive into each location with photography-focused tools.

- **Full-screen photo slider** with pinch-to-zoom viewer
- **Golden hour widget:** Sunrise, sunset, and ideal shooting time hints
- **Star ratings & tips:** Community reviews with 1–5 stars
- **Share & report:** Native share sheet and moderation-ready reporting
- **Directions:** Open spot in Apple/Google Maps

https://github.com/user-attachments/assets/ae3dd09a-96dd-46e6-bc8b-c4e66ed7585f

---

### ➕ Suggest a Spot (Öner)

Camera-first flow for contributing new photo locations.

1. **Onboarding** — quick 3-step guide for first-time users
2. **Capture** — open camera immediately
3. **Edit** — rotate, crop (4:3), retake before submit
4. **Details** — title, description, category, best shooting times
5. **Location** — GPS or interactive map picker with smart search
6. **Submit** — spot goes to **admin review** before appearing on the map

https://github.com/user-attachments/assets/c6220e87-9063-4f01-9363-40c50bc1d2df

---

### 👤 Profiles, Follow & Favorites

Social layer for photographers and spot collectors.

- **Public profiles:** Bio, avatar, cover, social links, privacy settings
- **Follow system:** Followers / following lists
- **Spot tabs:** User's contributed locations and approved photos
- **Favorites:** Organize saved spots into custom folders and lists
- **Swipeable profile tabs** with smooth crossfade animations

https://github.com/user-attachments/assets/b40d39f4-61b9-45a5-aa66-b4c8fedeb700

---

### 🛡️ Admin Moderation Panel

Three-tab moderation hub for keeping UGC safe and accurate.

| Tab | Purpose |
|-----|---------|
| **Locations** | Approve or reject new spot suggestions |
| **Photos** | Approve or reject community photo uploads |
| **Reports** | Review user reports on spots and reviews |

- Firebase Custom Claims for secure admin access
- Push notifications when content is approved
- Pending spots hidden from public map until approved

---

### 🌙 Theme & Settings

- **Light / Dark / System** theme with persistent preference
- **My submissions:** Track photo status (Pending / Approved / Rejected)
- **Legal:** Privacy policy and terms of service
- **Profile editing:** Avatar, cover, bio, visibility controls

---

## 💻 Technical Architecture & Stack

| Layer | Technology |
|-------|------------|
| **Framework** | Expo SDK 54 + React Native |
| **Navigation** | Expo Router (file-based) |
| **Backend** | Firebase Auth, Firestore, Cloud Storage |
| **Maps** | react-native-maps + Google Maps API |
| **Geocoding** | Google Places, Nominatim, Photon |
| **Media** | expo-camera, expo-image-picker, expo-image-manipulator |
| **Notifications** | Expo Push Notifications |
| **State** | React hooks + Firestore `onSnapshot` realtime listeners |

---

## 📱 Platform Support

- **iOS** — App Store ready (EAS Build configured)
- **Android** — Play Store ready
- **Expo Go** — development & testing via tunnel

---

## 🔒 Proprietary Notice

The core source code, Firebase schemas, and API integrations for PhotoLoc are maintained in a **private repository** to protect proprietary business logic and API keys.

This public showcase documents the product vision, feature set, UI/UX design, and technical architecture.

---

## 👤 Author

**Osman Ertuğrul Kestioğlu** — [GitHub @Zenroin](https://github.com/Zenroin)
