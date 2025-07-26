# Firebase Authentication Flutter App

This Flutter app demonstrates full-featured **Firebase Authentication** using **Email & Password**.


# Objective

Demonstrate the ability to integrate backend services by implementing user authentication (Sign Up, Sign In, Sign Out) using Firebase.

# Features Implemented

- Email & Password **Sign Up**
- Email & Password **Login**
- **Logout** functionality
- Display logged-in **user's email**
  **Persistent login** using `authStateChanges()`
- **Forgot Password** flow with reset email
- Password visibility toggle
- Loading indicators during network/auth actions
- Input validation (email format, password length)
- **SnackBars for error and success feedback**
- Simple, clean Material UI with gradient backgrounds

# Demo Video

📥 [Click here to download and watch the demo video](assets/demo.mp4)

This video shows the full user flow: signup, login, logout, and password reset.

# Firebase Setup Instructions

Follow these steps to configure Firebase:

1. Go to [Firebase Console](https://console.firebase.google.com/)
2. Create a new Firebase project
3. Add an Android app to the project
4. Download the `google-services.json` file
5. Place it inside:

# dependencies:
- firebase_core: ^2.0.0
- firebase_auth: ^4.0.0

#  Packages Used
- firebase_core: 	Firebase core setup
- firebase_auth: 	User authentication
- flutter/material:	UI components (built-in)

# Folder Structure
## lib/
- custom_text_field.dart
- forgot_password_screen.dart
- home_screen.dart
- login_screen.dart
- signup_screen.dart
- main.dart
## assets/
- demo.mp4


