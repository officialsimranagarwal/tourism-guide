# Tourism Guide App 🗺️

![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase)
![Gradle](https://img.shields.io/badge/Build-Gradle-02303A.svg?style=for-the-badge&logo=Gradle&logoColor=white)

## 📖 Overview

**Tourism Guide** is a native Android application designed to assist travelers in discovering attractions. It integrates **Firebase Banking-as-a-Service (BaaS)** for real-time data sync, user authentication, and storage, replacing traditional SQL backends.

## 🏗️ Technical Architecture

### 1. Backend (Firebase)
-   **Realtime Database**: Stores structured JSON data for tourist spots, reviews, and user profiles.
-   **Google Services**: Integrated via the `com.google.gms:google-services` Gradle plugin to enable auto-configuration of Firebase SDKs.

### 2. Android Client
-   **Build System**: Gradle 4.2.1 is used for dependency management and building the APK.
-   **Project Structure**: Follows the standard Android MVC/MVVM pattern.
    -   `app/src/main/java`: Java/Kotlin source code.
    -   `app/src/main/res`: XML layouts and resources.
    -   `AndroidManifest.xml`: Defines app permissions (Internet, Access Network State) and Activity entry points.

## ⚙️ Configuration

The application requires the google-services configuration file:
-   **File**: `google-services.json`
-   **Location**: `/app` root directory.
-   **Purpose**: Contains API keys and project IDs to authenticate the app with the specific Firebase project instance.

## 🚀 Build Instructions

1.  **Prerequisites**: Android Studio and JDK 8+.
2.  **Setup**:
    ```bash
    git clone https://github.com/officialsimranagarwal/tourism-guide.git
    ```
3.  **Firebase Config**: Place your `google-services.json` in the `app/` folder.
4.  **Build**:
    -   Sync Project with Gradle Files.
    -   Run on Emulator (AVD) or physical device via USB Debugging.

## 🤝 Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## 👤 Author

**Simran Agarwal**
-   [Profile](https://github.com/officialsimranagarwal)
-   [LinkedIn](https://linkedin.com/in/simran-agarwal-54751b191)

---
*Generated with ❤️ by Simran Agarwal*
