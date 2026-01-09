<div align="center">

# 🚀 Flutter Week 1 – Login UI App

### *A Modern, Clean Login Interface Built with Flutter*

[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)](https://dart.dev)
[![Material Design](https://img.shields.io/badge/Material%20Design-757575?style=for-the-badge&logo=material-design&logoColor=white)](https://material.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

**A comprehensive beginner-friendly Flutter project demonstrating UI fundamentals, form validation, and navigation patterns.**

[View Demo](#-screenshots) · [Report Bug](https://github.com/your-username/flutter-week1-login-ui/issues) · [Request Feature](https://github.com/your-username/flutter-week1-login-ui/issues)

</div>

---



## 🎯 About The Project

<div align="center">
  <img src="https://img.shields.io/badge/Week-1-blue?style=flat-square" alt="Week 1">
  <img src="https://img.shields.io/badge/Difficulty-Beginner-green?style=flat-square" alt="Beginner">
  <img src="https://img.shields.io/badge/Status-Complete-success?style=flat-square" alt="Complete">
</div>

<br>

This project is part of **Week 1: Basic Flutter Development and UI Building** course. It's designed to provide hands-on experience with Flutter's core concepts while building a production-ready login interface.

### 🎓 What Makes This Project Special?

- **📱 Real-World Application** - Implements industry-standard login UI patterns
- **✨ Clean Code** - Well-structured, documented, and maintainable
- **🎨 Modern Design** - Follows Material Design 3 guidelines
- **🔒 Secure Patterns** - Password visibility toggle and input validation
- **📚 Educational** - Extensively commented for learning purposes

### Built With

This project leverages the power of:

- **Flutter** - Google's UI toolkit for building natively compiled applications
- **Dart** - Client-optimized programming language
- **Material Design 3** - Latest design system from Google

## ✨ Features

<table>
  <tr>
    <td width="50%">
      
### 🔐 Authentication UI
- ✅ **Email Input Field**  
  Validates email format using RegEx pattern
  
- ✅ **Password Input Field**  
  Secure input with show/hide toggle
  
- ✅ **Forgot Password Link**  
  Interactive text button (UI ready for backend)
  
- ✅ **Login Button**  
  Animated button with loading states

    </td>
    <td width="50%">
      
### ✅ Form Validation
- ✅ **Real-time Validation**  
  Instant feedback on user input
  
- ✅ **Email Format Check**  
  RFC 5322 compliant validation
  
- ✅ **Required Fields**  
  Prevents empty submissions
  
- ✅ **Error Messages**  
  User-friendly validation feedback

    </td>
  </tr>
  <tr>
    <td width="50%">
      
### 🏠 Home Screen
- ✅ **Welcome Message**  
  Personalized greeting after login
  
- ✅ **User Email Display**  
  Shows logged-in user information
  
- ✅ **Navigation Handling**  
  Proper back button behavior

    </td>
    <td width="50%">
      
### 🎨 User Experience
- ✅ **Material Design 3**  
  Modern, clean interface
  
- ✅ **Responsive Layout**  
  Works on all screen sizes
  
- ✅ **Smooth Animations**  
  Polished transitions
  
- ✅ **Accessibility**  
  Screen reader compatible

    </td>
  </tr>
</table>

---

## 📚 Learning Objectives

<div align="center">

### Core Competencies Developed

</div>

| # | Objective | Status |
|---|-----------|--------|
| 1 | Understand Flutter project architecture and file structure | ✅ Complete |
| 2 | Build responsive UIs using Flutter widgets | ✅ Complete |
| 3 | Master core widgets: `Column`, `Row`, `Container`, `TextField`, `ElevatedButton` | ✅ Complete |
| 4 | Implement form validation logic with error handling | ✅ Complete |
| 5 | Manage state effectively with `StatefulWidget` | ✅ Complete |
| 6 | Navigate between screens using `Navigator` | ✅ Complete |
| 7 | Handle user input and events properly | ✅ Complete |
| 8 | Apply Material Design 3 principles | ✅ Complete |


## 🛠 Tech Stack

<div align="center">

### Core Technologies

| Technology | Version | Purpose |
|------------|---------|---------|
| ![Flutter](https://img.shields.io/badge/Flutter-v3.24+-02569B?logo=flutter) | 3.24+ | UI Framework |
| ![Dart](https://img.shields.io/badge/Dart-v3.5+-0175C2?logo=dart) | 3.5+ | Programming Language |
| ![Material](https://img.shields.io/badge/Material-3.0-757575?logo=material-design) | 3.0 | UI/UX Guidelines |

</div>

### 📦 Dependencies

```yaml
dependencies:
  flutter:
    sdk: flutter
  cupertino_icons: ^1.0.8  # iOS-style icons
  
dev_dependencies:
  flutter_test:
    sdk: flutter
  flutter_lints: ^4.0.0    # Recommended lints
```

### 🔧 Development Tools

- **IDE:** Android Studio / VS Code with Flutter extension
- **Version Control:** Git & GitHub
- **Testing:** Flutter DevTools
- **Emulator:** Android/iOS simulators or physical devices

---

## 📂 Project Structure

```
flutter-week1-login-app/
│
├── 📱 lib/                          # Application source code
│   ├── main.dart                    # App entry point & theme config
│   ├── 📄 screens/
│   │   ├── login_screen.dart        # Login UI & validation logic
│   │   └── home_screen.dart         # Post-login home screen
│   ├── 🧩 widgets/
│   │   ├── custom_text_field.dart   # Reusable text input widget
│   │   └── custom_button.dart       # Styled button component
│   ├── 🎨 constants/
│   │   ├── colors.dart              # App color palette
│   │   └── text_styles.dart         # Typography definitions
│   └── 🛠 utils/
│       └── validators.dart          # Input validation functions
│
├── 🖼 assets/
│   ├── images/                      # App images & illustrations
│   │   └── logo.png
│   └── icons/                       # Custom icon assets
│
├── 📸 screenshots/                   # Documentation screenshots
│   ├── login.png
│   ├── validation.png
│   └── home.png
│
├── 🤖 android/                       # Android platform files
├── 🍎 ios/                          # iOS platform files
├── 🌐 web/                          # Web platform files
│
├── 📋 pubspec.yaml                   # Project dependencies & assets
├── 📋 analysis_options.yaml          # Dart linting configuration
├── 📖 README.md                      # Project documentation
├── 📄 LICENSE                        # MIT License
└── 🚫 .gitignore                    # Git ignore rules
```

<details>
<summary>📖 File Descriptions</summary>

- **main.dart** - Application entry point with MaterialApp configuration
- **login_screen.dart** - Complete login interface with form validation
- **home_screen.dart** - Welcome screen displayed after successful login
- **validators.dart** - Email and password validation utility functions
- **colors.dart** - Centralized color scheme for consistent theming
- **text_styles.dart** - Typography definitions for uniform text styling

</details>

---

## 🚀 Getting Started

Follow these steps to get the project running on your local machine.

### Prerequisites

Before you begin, ensure you have the following installed:

- ✅ **Flutter SDK** (3.0 or higher)  
  ```bash
  flutter --version
  ```
  
- ✅ **Dart SDK** (included with Flutter)
  
- ✅ **Android Studio** or **VS Code**  
  With Flutter and Dart plugins installed
  
- ✅ **Git** for version control  
  ```bash
  git --version
  ```

### Installation

#### Step 1: Clone the Repository

```bash
# Using HTTPS
git clone https://github.com/Anmol-png/flutter-week1-login-app.git

# OR using SSH
git clone git@github.com:Anmol-png/flutter-week1-login-app.git
```

#### Step 2: Navigate to Project Directory

```bash
cd flutter-week1-login-ui
```

#### Step 3: Install Dependencies

```bash
flutter pub get
```

#### Step 4: Verify Flutter Installation

```bash
flutter doctor -v
```

Ensure all required components show a checkmark ✓

#### Step 5: Run the Application

```bash
# Run on connected device/emulator
flutter run

# Run on specific device
flutter devices  # List all available devices
flutter run -d <device_id>
```

### 🎉 Success!

Your app should now be running. You'll see the login screen on your device/emulator.

---

## 💻 Usage

### Running on Different Platforms

<table>
  <tr>
    <th>Platform</th>
    <th>Command</th>
    <th>Requirements</th>
  </tr>
  <tr>
    <td>🤖 Android</td>
    <td><code>flutter run</code></td>
    <td>Android Studio, Android SDK</td>
  </tr>
  <tr>
    <td>🍎 iOS</td>
    <td><code>flutter run</code></td>
    <td>Xcode, macOS</td>
  </tr>
  <tr>
    <td>🌐 Web</td>
    <td><code>flutter run -d chrome</code></td>
    <td>Chrome browser</td>
  </tr>
  <tr>
    <td>🪟 Windows</td>
    <td><code>flutter run -d windows</code></td>
    <td>Windows 10+, Visual Studio</td>
  </tr>
  <tr>
    <td>🍏 macOS</td>
    <td><code>flutter run -d macos</code></td>
    <td>macOS, Xcode</td>
  </tr>
  <tr>
    <td>🐧 Linux</td>
    <td><code>flutter run -d linux</code></td>
    <td>Linux, GTK+</td>
  </tr>
</table>

### 🧪 Testing Credentials

For development and testing purposes:

| Field | Test Value | Notes |
|-------|-----------|-------|
| **Email** | `test@example.com` | Any valid email format |
| **Email** | `demo@flutter.dev` | Alternative test email |
| **Password** | `password123` | Any non-empty string |
| **Password** | `Test@1234` | With special characters |

> ⚠️ **Important:** This is a UI-only implementation. No actual authentication backend is connected.

### 📱 Development Commands

```bash
# Hot reload (during development)
r

# Hot restart
R

# Open DevTools
flutter pub global activate devtools
flutter pub global run devtools

# Build APK
flutter build apk --release

# Build iOS
flutter build ios --release

# Run tests
flutter test

# Analyze code
flutter analyze
```

---

## 🗺 Roadmap

### ✅ Completed (Week 1)

- [x] Basic login UI design
- [x] Email and password validation
- [x] Navigation to home screen
- [x] Password visibility toggle
- [x] Form error handling

### 🔄 In Progress (Week 2)

- [ ] Backend integration (Firebase Auth)
- [ ] Registration screen
- [ ] Password recovery flow

**Made with ❤️ and Flutter**

*Happy Coding! 🚀*

</div>
