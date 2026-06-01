💼 EmployeeSalaryApp 📊

A modern Android application built with Material Design that calculates employee net salary based on progressive tax brackets, with support for multiple currencies and local history tracking.

✨ Features
💰 Smart Tax Calculation

Automatically calculates tax based on salary ranges:

0 – 10,000 → 5% Tax
10,001 – 30,000 → 7% Tax
Above 30,000 → 10% Tax
💱 Multi-Currency Support

Switch between multiple currencies:

USD ($)
EUR (€)
GBP (£)
🎨 Modern UI (Material Design 3)

Built using clean and responsive UI components:

Card-based layout
Outlined text fields
Smooth fade-in animations
Clean typography and spacing
📜 Calculation History
Stores last 5 salary calculations locally
Easy access to recent results
Auto-removes oldest entry when limit is exceeded
📤 Share Functionality
Share calculation results via:
WhatsApp
Email
Other installed apps
✅ Input Validation
Real-time validation for empty inputs
Prevents invalid salary entries
User-friendly error messages
🛠️ Architecture

The project follows clean separation of concerns:

Employee
Data model representing employee details and salary input.
EmployeeSalaryCalculator
Handles all tax logic and salary computation.
MainActivity
Controls UI interactions, state management, and user events.
🚀 How to Run
Clone this repository
Open in Android Studio (Hedgehog or newer)
Let Gradle sync finish
Run on an emulator (recommended: Pixel 8, API 34+) or a physical device
📸 Screenshots

(Add screenshots or screen recordings here to showcase UI and functionality)

📌 Notes

This project was built as a learning exercise to practice:

Clean architecture principles
Material Design 3 UI development
Kotlin/Android state handling
Basic financial logic implementation
