# Android Terminal Idle Screen

A professional, lightweight Android launcher specifically designed for payment terminals and Kiosk-mode hardware. This project transforms a standard Android device into a dedicated payment interface with a focus on premium user experience and system stability.

## Key Features
* **Kiosk Optimized:** Configured as a Home Screen launcher to "own" the device interface.
* **Immersive UI:** Automatically hides system navigation and status bars for a true full-screen experience.
* **Material 3 Design:** Implements a soft-grey radial gradient background (`#FBFBFF` to `#E2E2EC`) to reduce eye strain and prevent screen burn-in.
* **Smooth Animations:** Powered by **Lottie** for high-quality, vector-based 3D animations that remain crisp on any screen density.
* **Instant Start:** Optimized Splash Screen API integration to eliminate the default Android logo during boot-up.
* **Display Management:** Forces 100% screen brightness and uses `FLAG_KEEP_SCREEN_ON` to ensure the terminal is always ready for customers.

## Tech Stack
* **UI Framework:** Jetpack Compose
* **Architecture:** Kotlin with Material 3
* **Animations:** Airbnb Lottie
* **Min SDK:** API 24 (Android 7.0)

## Getting Started
1. Clone the repository.
2. Add your Lottie JSON file to `app/src/main/res/raw/terminal_animation.json`.
3. Build and deploy to your Android-based terminal.
4. Set the app as the "Default Home App" in Android settings.