# FenixIRC

Modern Android IRC client built in Kotlin.

FenixIRC is an Android IRC client designed for secure communication, flexible customization, and practical moderation tools. The project is structured around a lightweight Lite build and a more complete Pro build, allowing users to choose the feature set they need without carrying unnecessary functionality.

## Overview

FenixIRC aims to provide a polished IRC experience for Android with a focus on:

- reliable chat and channel handling
- secure/private communication in the Pro build
- moderation tools for channel management
- support for bot and script-driven workflows
- responsive, modern Android UI
- open-source development and community contributions

## Features

### Core features
- Android IRC client in Kotlin
- Standard IRC channel and private messaging support
- Channel discovery and user interaction
- Moderation tools for managing channel activity
- Script support for automation and custom workflows
- Bot integration support
- Modern, customizable Android interface

### Lite / Pro model
- Lite build: focused on essential IRC functionality
- Pro build: includes advanced features such as enhanced private messaging and more complete tool support

### Security
- secure communication model for Pro functionality
- local data handling with Android app-level configuration
- architecture intended for incremental security improvements and safe extension

## Project status

This project is in active development.

The current repository is intended as a source-available Android project built with Android Studio and Gradle. It is suitable for development, testing, and community contribution.

## Requirements

- Android Studio
- Android SDK
- Kotlin toolchain
- Gradle

## Building the project

### Clone the repository

```bash
git clone https://github.com/drthands-apps/FenixIRC.git
cd FenixIRC
```

### Open in Android Studio

1. Open Android Studio
2. Choose "Open an existing project"
3. Select the cloned `FenixIRC` directory
4. Let Gradle sync
5. Build or run the project on a connected device or emulator

### Build from command line

```bash
./gradlew assembleDebug
```

For a release build:

```bash
./gradlew assembleRelease
```

## Project structure

```text
FenixIRC/
├── app/
│   ├── src/
│   ├── build.gradle.kts
│   └── .gitignore
├── gradle/
├── build.gradle.kts
├── settings.gradle.kts
├── gradlew
├── gradlew.bat
├── LICENSE
├── README.md
└── .gitignore
```

## Current application metadata

- Application package: `com.drthands.fenixirc`
- Minimum SDK: 24
- Target SDK: 37
- Version Code: 24
- Version Name: 0.99 rev4

## Development and contributions

Contributions are welcome. If you want to improve the project, report bugs, propose new features, or help with testing, please open an issue or submit a pull request.

### Suggested contribution areas
- feature development
- UI improvements
- IRC protocol handling
- moderation workflows
- security review
- documentation and localization

## Community and contact

- Website: https://fenixirc.com
- Main site: https://drthands.com
- Email: contacto@drthands.com
- Email: drthands@gmail.com
- GitHub: https://github.com/drthands-apps

## Support and sponsorship

The project is maintained by the developer community and contributors. Support can come in the form of:

- code contributions
- bug reports
- feature suggestions
- testing and validation
- sponsorship or donations if available

## License

This project is licensed under the GNU General Public License v3.0. See the [LICENSE](LICENSE) file for the full text.

## Disclaimer

This project is provided as-is without warranty. Users are responsible for complying with their local laws, IRC network rules, and the terms of the services they connect to.

---

FenixIRC is an open-source Android IRC client project intended for community-driven development and iterative improvement.
