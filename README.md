# NeonPulse Installer | Desktop Deployment Suite

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Windows-0078D4?style=for-the-badge&logo=windows&logoColor=white)
![Build](https://img.shields.io/badge/Build-Executable-orange?style=for-the-badge)

## 🚀 Overview

The **NeonPulse Installer** is a dedicated deployment project designed to package the NeonPulse Java Desktop application into a professional, standalone executable. This project ensures a seamless onboarding experience by eliminating the need for users to manually configure Java environments or run complex terminal commands.

## ✨ Key Features

* **Standalone Executable Generation:** Successfully converted raw Java JAR files into a production-ready `.exe` format for Windows deployment.
* **Bundled JRE (Java Runtime Environment):** Configured the installer to include a lightweight, embedded JRE, allowing the NeonPulse app to run on machines that do not have Java pre-installed.
* **Automated Desktop Integration:** The installer automatically handles directory creation, shortcut placement, and icon mapping during the setup process.
* **Resource Management:** Optimized the installation package size to ensure fast downloads and efficient disk space usage.
* **Clean Uninstallation Logic:** Included a built-in uninstaller to ensure all application data and shortcuts are safely removed upon user request.

## 🛠️ Tech Stack

* **Primary Language:** Java
* **Build Tools:** jpackage / Launch4j (Specify the tool you used)
* **Environment:** OpenJDK 
* **Target OS:** Windows 

## 📂 Installation Flow

1.  **Launch:** User runs the `NeonPulse.exe`.
2.  **Extraction:** The installer extracts the application core and the private JRE to the specified Program Files directory.
3.  **Finalization:** A desktop shortcut is created, and the "Launch NeonPulse" option is presented to the user.

## 💡 Why This Matters

This project demonstrates proficiency in the **Software Development Life Cycle (SDLC)** by taking a project beyond the "it works on my machine" stage and transforming it into a consumer-ready digital product.

---
*Developed by Shlok Patel*
