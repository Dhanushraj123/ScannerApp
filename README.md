QrScannerApp
A beginner-friendly mobile app built with **React Native** using **Expo**

## Note :To run this project locally, create a `.env` file in the root directory and add the following:

```env
REACT_APP_SUPABASE_URL=your_supabase_url_here
REACT_APP_SUPABASE_ANON_KEY=your_supabase_anon_key_here
add .env file in your code and add the url key and anon key of ur database supabase. for security reasons its not added here.

** Functionalities
Login using Firebase  
Scan QR Codes using the device camera  
Save scanned data to **Supabase**  
View scan history (user-specific)
---

## Features
**Supabase Authentication**  
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
**Supabase Authentication**
**Supabase (PostgreSQL + RLS)**
**Expo Camera**

---
## Note : the .apk file is uploaded in the releases.
## Installation & Run Locally

1. Clone the repo:

```bash
git clone https://github.com/your-username/ScannerApp.git
cd ScannerApp
