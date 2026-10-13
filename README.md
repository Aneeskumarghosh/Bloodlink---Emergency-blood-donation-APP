<div align="center">

# 🩸 BloodLink

### Emergency Blood Donation App

**Location-aware emergency blood donation platform connecting requests with verified, nearby donors.**

[![Status](https://img.shields.io/badge/Status-Beta-red?style=for-the-badge)](https://github.com/YOUR_USERNAME/BloodLink/releases)
[![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://developer.android.com)
[![Language](https://img.shields.io/badge/Language-Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org)
[![UI](https://img.shields.io/badge/UI-Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)](https://developer.android.com/jetpack/compose)
[![Backend](https://img.shields.io/badge/Backend-Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com)

[Portfolio](https://aneeskumarghosh.github.io/anees-portfolio/) • [Case Study](https://aneeskumarghosh.github.io/anees-portfolio/assets/case-study.html) • [Report Bug](../../issues) • [Request Feature](../../issues)

</div>

---

## 📖 Overview

**BloodLink** is a location-aware emergency blood donation app designed to connect blood requests with verified, potentially compatible nearby donors — and coordinate communication through the donation process.

Built end-to-end as a portfolio project: **research → UX strategy → UI design → native Android development.**

> ⚠️ **Status: Beta** — This is an actively developed portfolio project. Core flows are functional and open for testing. Some features are still in progress.

---

## 🎯 The Problem

Every day, patients require blood due to accidents, surgery, childbirth, cancer treatment, and other medical conditions. Although people may be willing to donate, finding a suitable and available donor during an emergency can be difficult.

Families often resort to contacting hospitals, blood banks, NGOs, friends, relatives, and social media communities. This fragmented process involves repeated calls, manual coordination, and outdated donor information.

**BloodLink** aims to make donor discovery and emergency coordination more organized, accessible, and efficient.

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🚨 Emergency Requests
Create a request with blood group, hospital, units required, and urgency level.

### 📍 Nearby Donor Discovery
Browse verified, eligible donors on a list or interactive map view.

### 👤 Donor Profiles
View blood group, availability, eligibility, distance, and donation history.

</td>
<td width="50%">

### 🔄 Request Coordination
Track status from searching → donor accepted → on the way → completed.

### 🔒 Privacy Controls
User-controlled emergency contact visibility and location sharing radius.

### 📊 Donation History
Track past donations and view your next eligible date.

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

### Frontend

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)
![Material 3](https://img.shields.io/badge/Material%203-757575?style=flat-square&logo=materialdesign&logoColor=white)
![Coroutines](https://img.shields.io/badge/Coroutines-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![StateFlow](https://img.shields.io/badge/StateFlow-7F52FF?style=flat-square&logo=kotlin&logoColor=white)

### Backend & Services

![Firebase Auth](https://img.shields.io/badge/Firebase%20Auth-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Firestore](https://img.shields.io/badge/Cloud%20Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Cloud Functions](https://img.shields.io/badge/Cloud%20Functions-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![FCM](https://img.shields.io/badge/FCM-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Google Maps](https://img.shields.io/badge/Google%20Maps-4285F4?style=flat-square&logo=googlemaps&logoColor=white)

</div>

| Layer | Technology |
|---|---|
| **Language** | Kotlin |
| **UI Framework** | Jetpack Compose, Material 3 |
| **Architecture** | MVVM, feature-based |
| **Async** | Kotlin Coroutines, StateFlow |
| **Navigation** | Navigation Compose |
| **Image Loading** | Coil |
| **Local Storage** | DataStore |
| **Auth** | Firebase Authentication (Phone OTP) |
| **Database** | Cloud Firestore |
| **Storage** | Firebase Storage |
| **Notifications** | Firebase Cloud Messaging |
| **Backend Logic** | Firebase Cloud Functions |
| **Security** | Firebase App Check, Firestore Security Rules |
| **Maps** | Google Maps SDK, Maps Compose |
| **Location** | Android Location Services |

---

## 🎨 Design System

<div align="center">

| Color | Hex | Usage |
|:---:|:---:|---|
| 🔴 | `#D32F2F` | Primary Red |
| 🔴 | `#E53935` | Secondary Red |
| 🟠 | `#FF6B6B` | Accent Coral |
| 🩷 | `#FFEBEE` | Light Red Surface |
| 🔵 | `#1976D2` | Trust Blue |
| 🟢 | `#2E7D32` | Success Green |
| 🟡 | `#F59E0B` | Warning |
| ⚪ | `#FAFAFA` | Background |
| ⚪ | `#FFFFFF` | Surface |
| ⚫ | `#212121` | Primary Text |
| ⚫ | `#757575` | Secondary Text |
| ⚪ | `#E0E0E0` | Border |

</div>

**Typography:** Poppins (headings) • Inter (body)
**Spacing:** 8px system
**Style:** Material 3-inspired • Rounded cards • Subtle shadows • Restrained red usage

---

## 📱 Screens

<table>
<tr>
<td align="center" width="25%">
<b>Home Dashboard</b><br/>
<i>Emergency actions front and center</i>
</td>
<td align="center" width="25%">
<b>Nearby Donors</b><br/>
<i>List & map discovery</i>
</td>
<td align="center" width="25%">
<b>Emergency Requests</b><br/>
<i>Live queue with urgency</i>
</td>
<td align="center" width="25%">
<b>Profile & Settings</b><br/>
<i>Privacy-first controls</i>
</td>
</tr>
</table>
