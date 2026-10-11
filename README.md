# FenixIRC - Advanced Android IRC Client

**The most feature-rich IRC client for Android**

FenixIRC is a modern, secure, and highly customizable IRC client built for Android with Kotlin. It combines powerful functionality with an intuitive user interface, offering both lightweight (Lite) and feature-complete (Pro) versions.

## Features

### Core Features
- **Modern IRC Protocol Support** - Full compliance with IRC standards (RFC 1459)
- **Enhanced Security** - Reinforced encryption and secure authentication
- **Native Moderation Tools** - Built-in channel management and user controls
- **Script Support** - Execute custom IRC scripts for automation
- **Bot Integration** - Deploy and manage IRC bots directly from the app
- **Encrypted Private Messages** (Pro) - End-to-end encrypted messaging for Pro users
- **Aesthetic & Functional Customization** - Theme, layout, and behavior personalization

### User Interface
- **Clean, Intuitive Design** - Modern Android UI with Jetpack Compose
- **Responsive Layout** - Optimized for all Android devices
- **Real-time Chat** - Instant message delivery and notifications
- **Channel Discovery** - Browse and join public IRC channels
- **User Management** - Manage contacts, friends, and blocked users

### Dual Flavor System
- **Lite** - Essential IRC functionality for minimal storage footprint
- **Pro** - Complete feature set including encrypted messaging and advanced tools

## System Requirements

- **Minimum SDK**: Android 7.0 (API 24)
- **Target SDK**: Android 15 (API 37)
- **Language**: Kotlin
- **Build Tool**: Gradle 8.0+

## Installation

### From Source (Android Studio)

1. Clone the repository:
```bash
git clone https://github.com/drthands-apps/FenixIRC.git
cd FenixIRC
```

2. Open in Android Studio:
   - File → Open → Select the FenixIRC folder
   - Wait for Gradle to sync

3. Build and run:
   - Select your target device
   - Click "Run" (Shift + F10)

### Gradle Build

```bash
./gradlew assembleRelease  # Build release APK
./gradlew installDebug     # Install debug build
```

## Project Structure

```
FenixIRC/
├── app/
│   ├── src/main/java/com/personal/ircclient/
│   │   ├── core/              # IRC engine, services, network management
│   │   ├── data/              # Local database, entities, DAOs
│   │   ├── ui/                # UI screens and components
│   │   └── utils/             # Utility functions and helpers
│   ├── build.gradle.kts       # App-level Gradle configuration
│   └── src/                   # Resources and test files
├── gradle/                    # Gradle wrapper and configuration
├── build.gradle.kts           # Project-level Gradle configuration
├── settings.gradle.kts        # Gradle module settings
└── LICENSE                    # GPLv3 License
```

## Key Technologies

- **Kotlin** - Modern language for Android development
- **Jetpack Compose** - Declarative UI framework
- **Room Database** - Local data persistence
- **Coroutines** - Asynchronous programming
- **Gradle** - Build automation

## Configuration

### Application ID
- Lite: `com.drthands.fenixirc`
- Pro: `com.drthands.fenixirc.pro`

### Current Version
- Version Code: 24
- Version Name: 0.99 rev4

## Development & Contributions

FenixIRC is open-source and welcomes contributions from the community. Whether you're interested in:
- Bug fixes and improvements
- New feature development
- UI/UX enhancements
- Documentation
- Localization

Please consider joining our development community!

### Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -am 'Add feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Submit a pull request

## Community & Support

Join our growing community of IRC enthusiasts and developers:

- **Website**: [fenixirc.com](https://fenixirc.com)
- **Contact**: 
  - Email: [contacto@drthands.com](mailto:contacto@drthands.com)
  - Email: [drthands@gmail.com](mailto:drthands@gmail.com)
- **Main Site**: [drthands.com](https://drthands.com)
- **GitHub**: [github.com/drthands-apps](https://github.com/drthands-apps)

## Support & Sponsorship

FenixIRC is maintained by volunteers dedicated to keeping the project active and improving it regularly. If you find FenixIRC valuable and would like to support its development:

- **Contribute Code** - Help us build new features and fix bugs
- **Report Issues** - Help identify and document problems
- **Sponsor Development** - Consider supporting the project financially

Your support helps us:
- Maintain active development
- Sustain server infrastructure
- Expand features and capabilities
- Support the developer community

## License

This project is licensed under the **GNU General Public License v3.0** - see the [LICENSE](LICENSE) file for details.

### What this means:
- ✅ Free to use, modify, and distribute
- ✅ Source code must remain open
- ✅ Modifications must be shared under the same license
- ✅ No warranty provided

## Roadmap & Future

We're continuously working on:
- Performance optimizations
- Additional encryption methods
- Enhanced bot framework
- Extended scripting capabilities
- Community-driven features

## Credits

FenixIRC is built with dedication by the open-source community. Special thanks to:
- All contributors who have invested time in improving this project
- The IRC community for their continued support
- Users who provide feedback and suggestions

## Disclaimer

FenixIRC is provided "AS IS" without any warranty. Users are responsible for complying with IRC network policies and local laws when using this software.

---

**Status**: Active Development (v0.99)

*Last Updated: October 2026*

For the latest updates and releases, visit the [GitHub Repository](https://github.com/drthands-apps/FenixIRC).
