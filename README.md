# Moto Travel 🏍️

Moto Travel is a motorcycle-riding game prototype built with Flutter and Dart. It focuses on a simple mobile riding experience with motorcycle selection, movement controls, and obstacle avoidance.

> **Project status:** Learning and portfolio prototype. This repository describes a Flutter mobile game, not the separate Unity 3D concept.

## Gameplay Features

- Welcome screen and game entry flow.
- Motorcycle selection screen.
- Riding gameplay screen.
- Left and right movement controls.
- Acceleration and braking.
- Pause and restart options.
- Obstacle-avoidance gameplay.

## Technology Stack

| Area | Technology |
|---|---|
| Application | Flutter |
| Language | Dart |
| Target | Android and other Flutter-supported platforms |

## Getting Started

### Requirements

- Flutter SDK
- Dart SDK (included with Flutter)
- Android Studio or Visual Studio Code
- Android emulator or physical Android device

### Clone and run

```bash
git clone https://github.com/rahat-codes/moto-travel.git
cd moto-travel
flutter pub get
flutter analyze
flutter run
```

## Build an Android APK

Create a release APK with:

```bash
flutter build apk --release
```

The generated APK is available at:

```text
build/app/outputs/flutter-apk/app-release.apk
```

Install it on a compatible Android device for testing. This project is not published through Google Play.

## Engineering Roadmap

- [ ] Add gameplay screenshots and a short video demonstration.
- [ ] Document game-state management and control behavior.
- [ ] Add tests for navigation and core gameplay state.
- [ ] Improve responsive layout across phone aspect ratios.
- [ ] Add performance checks for sustained gameplay.
- [ ] Document asset sources and licenses.

## Author

**Rahat** · [GitHub](https://github.com/rahat-codes)

## License

This project is provided for learning and development purposes. Check the repository for any included third-party asset licenses before redistribution.
