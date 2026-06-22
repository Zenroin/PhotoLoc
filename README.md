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

<p align="left">
  <img width="384" height="848" alt="Discover" src="https://github.com/user-attachments/assets/0562e046-3cd9-4476-9225-e2e51d2983f6" />
</p>

---

### 🗺️ Interactive Map

A map-first experience with photo-rich markers and quick spot previews.

- **Photo markers:** Each spot appears as a thumbnail pin on the map
- **Clustering:** Clean view even with hundreds of locations
- **Spot preview card:** Tap a marker → slide-up card with photo carousel
- **Location search:** Google Places + OpenStreetMap powered address search
- **Quick actions:** Recenter to GPS, fit all markers, rating filters

<p align="left">
  <img width="384" height="848" alt="Map" src="https://github.com/user-attachments/assets/7d92e864-1412-4b2a-840a-950d32da16cf" />
</p>

---

### 📍 Spot Detail & Golden Hour

Deep dive into each location with photography-focused tools.

- **Full-screen photo slider** with pinch-to-zoom viewer
- **Golden hour widget:** Sunrise, sunset, and ideal shooting time hints
- **Star ratings & tips:** Community reviews with 1–5 stars
- **Share & report:** Native share sheet and moderation-ready reporting
- **Directions:** Open spot in Apple/Google Maps

<p align="left">
  <img width="384" height="848" alt="Spot Detail" src="https://github.com/user-attachments/assets/f4bc415a-c394-4eb6-9ac1-f3325d39f0e4" />
</p>

---

### ➕ Suggest a Spot (Öner)

Camera-first flow for contributing new photo locations.

1. **Onboarding** — quick 3-step guide for first-time users
2. **Capture** — open camera immediately
3. **Edit** — rotate, crop (4:3), retake before submit
4. **Details** — title, description, category, best shooting times
5. **Location** — GPS or interactive map picker with smart search
6. **Submit** — spot goes to **admin review** before appearing on the map

<p align="left">
  <img width="384" height="848" alt="Add Spot" src="https://github.com/user-attachments/assets/5f64060a-da47-4fac-a1c2-13a665dca27e" />
</p>

---

### 👤 Profiles, Follow & Favorites

Social layer for photographers and spot collectors.

- **Public profiles:** Bio, avatar, cover, social links, privacy settings
- **Follow system:** Followers / following lists
- **Spot tabs:** User's contributed locations and approved photos
- **Favorites:** Organize saved spots into custom folders and lists
- **Swipeable profile tabs** with smooth crossfade animations

<p align="left">
  <img width="384" height="848" alt="Profile" src="https://github.com/user-attachments/assets/c27b4e98-8e84-428a-bb84-37dd0818a5e2" />
</p>

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
