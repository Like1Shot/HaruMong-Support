<p align="center">
  <img src="docs/assets/images/app-icon.png" alt="HaruMong App Icon" width="120" height="120" style="border-radius: 24px;">
</p>

<h1 align="center">HaruMong</h1>

<p align="center">
  <strong>Your habit tracking companion with a virtual pet</strong>
</p>

<p align="center">
  <a href="https://apps.apple.com/app/harumong">
    <img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="50">
  </a>
</p>

---

## About

HaruMong helps you build lasting habits by combining habit tracking with a virtual pet experience. Complete your daily habits to keep your pet happy and healthy!

<p align="center">
  <img src="docs/assets/images/Sleepy_Ivory.png" alt="Sleepy Mongi" width="100">
  <img src="docs/assets/images/Default_Ivory.png" alt="Default Mongi" width="100">
  <img src="docs/assets/images/Excited_Ivory.png" alt="Excited Mongi" width="100">
</p>

<p align="center">
  <em>Your pet's mood changes based on your habit completion!</em>
</p>

## Features

- **Smart Habit Tracking** - Create simple or quantity-based habits
- **Virtual Pet Companion** - Care for your cute pet that reacts to your progress
- **Daily Check-ins** - Morning and evening reflections
- **Mood Tracking** - Log your daily mood and see patterns
- **Beautiful Widgets** - Track habits from your home screen
- **Detailed Statistics** - View your progress over time
- **HealthKit Integration** - Sync steps and mindfulness data
- **iCloud Sync** - Keep your data across devices
- **Localization** - English & Korean support

## Requirements

- iOS 17.0+
- Xcode 15.0+
- Swift 5.9+

## Build

1. Clone the repository
   ```bash
   git clone https://github.com/[username]/HaruMong.git
   ```

2. Open the project
   ```bash
   cd HaruMong
   open HaruMong.xcodeproj
   ```

3. Configure signing
   - Select the project in Xcode
   - Go to **Signing & Capabilities**
   - Select your development team

4. Build and run (⌘R)

## Project Structure

```
HaruMong/
├── App/                    # App entry point
├── Models/                 # Data models
├── Views/                  # SwiftUI views
│   ├── Habits/
│   ├── Pet/
│   ├── Stats/
│   ├── Settings/
│   └── Premium/
├── ViewModels/             # View models
├── Services/               # Business logic
├── Components/             # Reusable UI components
├── Extensions/             # Swift extensions
├── Utilities/              # Helper utilities
└── Resources/              # Assets & localization
```

## Tech Stack

- **SwiftUI** - UI framework
- **SwiftData** - Data persistence
- **WidgetKit** - Home screen widgets
- **StoreKit 2** - In-app purchases
- **HealthKit** - Health data integration
- **CloudKit** - iCloud sync

## Links

- [Privacy Policy](https://[username].github.io/HaruMong/privacy-policy)
- [Terms of Service](https://[username].github.io/HaruMong/terms-of-service)
- [Support & FAQ](https://[username].github.io/HaruMong/support)

## Contact

**Email:** [harumong.app@gmail.com](mailto:harumong.app@gmail.com)

---

<p align="center">
  Made with ❤️ for building better habits
</p>
