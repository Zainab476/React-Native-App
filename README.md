# 📱 Device Explorer

A React Native mobile application built with **Expo** and **React Navigation** that demonstrates how to access and utilize native mobile device capabilities[cite: 11].

---

## 💡 Project Overview

**Device Explorer** is a mobile application designed to showcase native hardware and system features using Expo's modular SDKs[cite: 11]. The application features a clean, tab-based or drawer-based navigation layout that allows users to seamlessly switch between two distinct native device capabilities (e.g., Camera, Location, Battery Status, or Sensors)[cite: 11].

---

## 🛠️ Tools & Technologies Used

* **Framework:** React Native[cite: 11]
* **Tooling/Platform:** Expo SDK[cite: 11]
* **Navigation:** React Navigation (Tab Navigation / Drawer Navigation)[cite: 11]
* **Device APIs (Expo Libraries):**
  * `expo-location` (or `expo-camera` / `expo-sensors` / `expo-battery`)[cite: 11]
  * `expo-image-picker` (or preferred Expo library)[cite: 11]
* **Language:** JavaScript / TypeScript

---

## 🎯 Learning Objectives

* Build a fully functional React Native application using Expo[cite: 11].
* Implement screen-to-screen navigation using **React Navigation**[cite: 11].
* Integrate Expo's external libraries to interact directly with physical phone capabilities[cite: 11].

---

## ⚡ Features & Application Structure

### 📱 Navigation Structure
The app utilizes **Tab-based** (or **Drawer-based**) navigation to provide quick access to different device features[cite: 11]:

1. **Feature Screen 1 (e.g., Location Explorer):** Uses `expo-location` to fetch, display, and track the device's real-time GPS coordinates and address details[cite: 11].
2. **Feature Screen 2 (e.g., Camera / Media Explorer):** Uses `expo-camera` or `expo-image-picker` to capture photos or access the user's media library[cite: 11].

---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed on your machine:
* [Node.js](https://nodejs.org/) (v16 or higher)
* Expo Go app on your physical mobile device (iOS/Android) or an emulator (Android Studio / Xcode).

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/device-explorer.git
   cd device-explorer
