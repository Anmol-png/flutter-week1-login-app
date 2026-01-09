# 🚀 Flutter Week 1 – Login UI App

A clean and modern Flutter application demonstrating fundamental Flutter development concepts, including UI building, form validation, and navigation.

<div align="center">

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Material Design](https://img.shields.io/badge/Material%20Design-757575?style=for-the-badge&logo=material-design&logoColor=white)

</div>

---

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Screenshots](#screenshots)
- [Learning Objectives](#learning-objectives)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

---

## 🎯 About

This project is part of **Week 1: Basic Flutter Development and UI Building**. It serves as a foundational project to understand Flutter's core concepts, widget composition, and basic app navigation patterns.

The app implements a fully functional login interface with validation, demonstrating best practices in Flutter UI development for beginners.

---

## ✨ Features

### 🔐 Authentication UI
- **Email Input Field** – Validates email format using RegEx
- **Password Input Field** – Secure input with show/hide toggle (visibility icon)
- **Forgot Password Link** – Interactive text button (UI only)
- **Login Button** – Validates form before navigation

### ✅ Form Validation
- Real-time email format validation
- Required field checks for both email and password
- User-friendly error messages
- Prevention of submission with invalid data

### 🏠 Home Screen
- Clean welcome screen after successful login
- Displays user email (optional)
- Back navigation handling

### 🎨 User Interface
- Material Design 3 principles
- Responsive layout for various screen sizes
- Smooth animations and transitions
- Accessible and intuitive design

---


---

## 📚 Learning Objectives

By completing this project, you will gain proficiency in:

- ✅ Understanding Flutter project architecture and file structure
- ✅ Building responsive UIs using Flutter widgets
- ✅ Working with core widgets: `Column`, `Row`, `Container`, `TextField`, `ElevatedButton`
- ✅ Implementing form validation logic
- ✅ Managing state with `StatefulWidget`
- ✅ Navigating between screens using `Navigator`
- ✅ Handling user input and events
- ✅ Applying Material Design principles

---

## 🛠 Technologies Used

| Technology | Purpose |
|------------|---------|
| **Flutter** | UI Framework |
| **Dart** | Programming Language |
| **Material Design** | UI/UX Guidelines |
| **Flutter SDK** | Development Kit |

**Dependencies:**
```yaml
dependencies:
  flutter:
    sdk: flutter
  cupertino_icons: ^1.0.2
```

---

## 📂 Project Structure

```
flutter-week1-login-app/
│
├── lib/
│   ├── main.dart                 # App entry point
│   ├── screens/
│   │   ├── login_screen.dart     # Login UI & logic
│   │   └── home_screen.dart      # Home screen after login
│   └── widgets/
│       └── custom_text_field.dart # Reusable text field (optional)
│
├── assets/
│   └── images/                   # App images/icons
│
├── screenshots/                  # App screenshots for README
│
├── android/                      # Android-specific files
├── ios/                          # iOS-specific files
├── web/                          # Web-specific files
│
├── pubspec.yaml                  # Dependencies & assets
├── analysis_options.yaml         # Dart linting rules
├── README.md                     # Project documentation
└── .gitignore                    # Git ignore rules
```

---

## 🚀 Installation

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install) (3.0 or higher)
- [Dart SDK](https://dart.dev/get-dart) (included with Flutter)
- [Android Studio](https://developer.android.com/studio) / [VS Code](https://code.visualstudio.com/) with Flutter extensions
- [Git](https://git-scm.com/)

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/flutter-week1-login-ui.git
   ```

2. **Navigate to project directory**
   ```bash
   cd flutter-week1-login-ui
   ```

3. **Install dependencies**
   ```bash
   flutter pub get
   ```

4. **Check Flutter setup**
   ```bash
   flutter doctor
   ```

5. **Run the application**
   ```bash
   flutter run
   ```

---

## 💻 Usage

### Running on Different Platforms

**Android/iOS:**
```bash
flutter run
```

**Web:**
```bash
flutter run -d chrome
```

**Windows/macOS/Linux:**
```bash
flutter run -d windows  # or macos, linux
```

### Testing Credentials

For development purposes, you can test with:
- **Email:** any valid email format (e.g., `test@example.com`)
- **Password:** any non-empty string (e.g., `password123`)

> **Note:** This is a UI-only implementation. No actual authentication is performed.

</div>
