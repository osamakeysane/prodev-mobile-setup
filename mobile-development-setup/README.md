# 📱 Mobile Development Setup — Expo Go

## 🧩 Objective

The goal of this setup is to prepare my environment for **mobile development** using **React Native with Expo**.  
This ensures that I can build, test, and run mobile applications directly on my physical device using **Expo Go**.

---

## ⚙️ Tools Installed

| Tool                     | Purpose                                                      | Status       |
| ------------------------ | ------------------------------------------------------------ | ------------ |
| **Node.js (LTS)**        | Required to run JavaScript and React Native commands         | ✅ Installed |
| **VS Code**              | Main IDE for writing and debugging code                      | ✅ Installed |
| **Expo Go (Mobile App)** | Used to test React Native apps directly on a physical device | ✅ Installed |
| **Git & GitHub**         | Version control and collaboration                            | ✅ Installed |
| **Windows OS**           | Operating System for development                             | ✅ In use    |

---

## 🚀 Setup Process

1. **Installed Node.js (LTS version)**

   - Downloaded from [nodejs.org](https://nodejs.org/).
   - Verified installation using:
     ```bash
     node -v
     npm -v
     ```
   - Both commands returned version numbers successfully.

2. **Installed Visual Studio Code**

   - Downloaded from [https://code.visualstudio.com/](https://code.visualstudio.com/).
   - Added helpful extensions such as _ES7+ React/Redux snippets_ and _Prettier_ for code formatting.

3. **Installed Expo CLI (optional for project setup)**

   - Used:
     ```bash
     npm install -g expo-cli
     ```
   - Verified installation:
     ```bash
     expo --version
     ```

4. **Created a New Expo Project**

   - Ran:
     ```bash
     npx create-expo-app app-example
     ```
   - This created the initial React Native project structure.

5. **Installed Expo Go on My Mobile Device**

   - Downloaded Expo Go from [https://expo.dev/go](https://expo.dev/go).
   - Logged into my Expo account inside the mobile app.
   - Opened the camera or Expo Go app to scan the QR code and run my project on my device.

6. **Tested the Setup**
   - Started the development server with:
     ```bash
     npx expo start
     ```
   - Opened the app on my phone through Expo Go.
   - The initial screen appeared successfully — setup confirmed! ✅

---

## 🧠 Challenges Faced

- **Network Connection Issue:**  
  Initially, my phone and computer were on different networks, causing the QR code not to connect.  
  ✅ Solution: Connected both devices to the same Wi-Fi network.

- **Expo CLI Installation Warning:**  
  Received some permission warnings during global install.  
  ✅ Solution: Used `npx create-expo-app` which works without global installation.

- **Understanding Folder Structure:**  
  The structure of the app was initially confusing, but after reviewing Expo documentation, it became clear how the `/app` and `/components` directories work.

---

## 🏁 Final Verification

After completing the setup:

- I can now create and run React Native apps using Expo.
- The Expo Go app on my phone successfully displays my project.
- Environment setup is **fully functional** and ready for future mobile development tasks.

---

**Author:** Mohamed Keytsane  
**Date:** November 2025  
**Project Repository:** [prodev-mobile-setup](#)
