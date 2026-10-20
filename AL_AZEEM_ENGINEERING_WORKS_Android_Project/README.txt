# AL AZEEM ENGINEERING WORKS — Android Billing App

This project is prepared from the supplied billing HTML and optimized for phone screens.

## Build the Android APK

Requirements:
- Windows 10/11
- Node.js LTS
- Android Studio
- Android SDK / Android SDK Platform
- A USB cable if you want to install directly on an Android phone

Open Command Prompt in this folder and run:

1. npm install
2. npm run build
3. npx cap add android
4. npx cap sync android
5. npx cap open android

Android Studio will open. Wait for Gradle sync to finish.

To test:
- Connect your Android phone with USB debugging enabled, or use an Android emulator.
- Press Run ▶ in Android Studio.

To make an APK:
- Android Studio → Build → Build Bundle(s) / APK(s) → Build APK(s)

The APK will be inside the Android project's build/outputs/apk folder.

## Current app details

Company:
AL AZEEM ENGINEERING WORKS
Phone: 03103363128
Address: House No. 42, Old Taj Ghee Mil, Rohri Township, New Yard

The supplied billing features are retained: invoice numbering, customer name/WhatsApp number, items, quantity, rate, discount, total, payment status, history, printing, and WhatsApp sharing.

Note: the current supplied HTML creates a printable invoice page rather than a true PDF file. A later native version can add true PDF generation and native WhatsApp file sharing.
