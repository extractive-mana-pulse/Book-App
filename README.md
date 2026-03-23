### 📚 KMP Book Search App

A Kotlin Multiplatform (KMP) Book Search application built with a focus on real-world architecture, scalability, and clean code practices. The goal of this project is to demonstrate how a single codebase can power multiple platforms — Android, iOS, and Desktop — using pure Kotlin. [Original Source](https://youtu.be/WT9-4DXUqsM?si=XUtPV46fu6X7Rghl)

![Book App Thumbnail](https://github.com/user-attachments/assets/c789bfa0-fd9e-46f3-b03e-3cbb6387e5f1)

### ✨ Overview

> [!IMPORTANT]
> This project is not just about searching books — it’s about building a production-ready foundation for cross-platform apps.

It follows modern development principles and mimics a real-world environment where code needs to be maintainable, testable, and scalable. The app allows users to search for books and view relevant information, while under the hood it showcases how to structure a robust KMP project.

### 🧱 Architecture

The project is designed with separation of concerns in mind:

Shared Module
Contains business logic, networking, and data handling
Written entirely in Kotlin
Platform-specific Modules
Android, iOS, and Desktop UIs
Consume shared logic with minimal duplication

The architecture is inspired by clean architecture principles:

Clear layering (data → domain → presentation)
Dependency injection-friendly structure
Easy to scale and extend

### 🚀 Features

- 🔍 Book search functionality
- 🌐 API integration (remote data source)
- ⚡ Shared business logic across platforms
- 🧩 Modular and maintainable codebase
- 🧼 Clean and readable structure

### 🛠️ Tech Stack
Kotlin Multiplatform (KMP)
Kotlin Coroutines & Flow
Ktor (for networking)
Compose (Android/Desktop UI)
Native UI (iOS integration)
Gradle Kotlin DSL

### 🎯 Purpose of the Project

This project was built to:

Practice building real-world KMP applications
Explore best practices for shared codebases
Create a solid reference for future cross-platform apps
Understand how to design scalable architectures in Kotlin

### ⚙️ Getting Started
Clone the repository
Open in your preferred IDE (Android Studio recommended)
Sync Gradle
Run the platform you want:
Android → via emulator/device
iOS → via Xcode
Desktop → via JVM run configuration

> [!NOTE]
> This project is intentionally kept focused and practical — no unnecessary complexity, just a solid foundation you can build on or learn from.

🤝 Contributions

Feel free to explore, fork, or improve the project. Any suggestions or improvements are welcome.
