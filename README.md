QrScannerApp
A beginner-friendly mobile app built with **React Native** using **Expo** that allows users to:

Login using Firebase  
Scan QR Codes using the device camera  
Save scanned data to **Supabase**  
View scan history (user-specific)
---

## Features
**Firebase Authentication**  
Users can log in securely using email and password.

**QR Code Scanner**  
Uses `expo-camera` to scan QR codes directly from the app.

**Supabase Database**  
All scanned data is stored along with user email and timestamp.

**Scan History**  
Users can view their personal scan history in a neatly listed format.

---

## Tech Stack

**React Native (with Expo)**
**Firebase Authentication**
**Supabase (PostgreSQL + RLS)**
**Expo Camera**

---

## Installation & Run Locally

1. Clone the repo:

```bash
git clone https://github.com/your-username/ScannerApp.git
cd ScannerApp
